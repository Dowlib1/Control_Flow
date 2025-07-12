# Shell Scripting: Control Flow & For Loop Examples

This repository demonstrates foundational concepts in shell scripting, focusing on control flow (if/elif/else statements) and for loops. Each example includes a step-by-step guide, with designated spaces for you to insert screenshots for better documentation and learning.

---

## Table of Contents

1. [Control Flow Example: Checking a Number](#control-flow-example-checking-a-number)
2. [For Loop Example 1: Printing Numbers 1–5](#for-loop-example-1-printing-numbers-1-5)
3. [For Loop Example 2: Iterating Over Strings](#for-loop-example-2-iterating-over-strings)
4. [For Loop Example 3: C-Style For Loop](#for-loop-example-3-c-style-for-loop)

---

## Control Flow Example: Checking a Number

This script reads a number from the user and prints whether the number is positive, negative, or zero.

```bash
#!/bin/bash

read -p "Enter a number: " num

if [ $num -gt 0 ]; then
    echo "The number is positive."
elif [ $num -lt 0 ]; then
    echo "The number is negative."
else
    echo "The number is zero."
fi
```

### Step-by-Step Guide

1. **Open the script in vim**  
    ```bash
    vim control_flow.sh
    ```
    ![Screenshot](Contouch.png)

2. **Inside the vim editor (editing the script)**  
    ![Screenshot](Contouch.png)
3a. Insert your script by presssing "i" key to enter INSERT mode.
     ![Screenshot](commmod.png)
   3b. press "Esc" key followed by ":wq" to save and exit the editor.

4. **Make the script executable**  
    ```bash
    chmod +x control_flow.sh
    ```
    ![Screenshot](commpermisssion.png)
5. **Run the script**  
    ```bash
    ./control_flow.sh
    ```
    ![Screenshot](commente.png)
enter a number: for example 4
  ![Screenshot](issuereolve.png)
---
6 To use Elif  comnnand use 'vim' to edit the file again and add
```
#!/bin/bash
read -p "Enter a number: " num
echo "You have entered the number $num"

if [ $num -gt 0 ]; then
    echo "The number is positive."
elif [ $num -lt 0 ]; then
    echo "The number is negative."
fi
```

![Screenshot](elifadded.pnf)

8 Run the file gain and enter a negative number this time.
enter both negative and positive numbers (2, 3, -2) on each run.
![Screenshot](commpositive.pnf)
![Screenshot](elif.pnf)



## For Loop Example 1: Printing Numbers 1–5

This script prints numbers from 1 to 5 using a for loop.

```bash
#!/bin/bash

for i in 1 2 3 4 5
do
  echo "Number: $i"
done
```

### Step-by-Step Guide

1. **Open the script in vim**  
    ```bash
    vim loop.sh
    ```
    ![Screenshot](loop1.png)

2. **Inside the vim editor (editing the script)**  
    ![Screenshot](loop.png)

3. **Make the script executable**  
    ```bash
    chmod +x loop.sh
    ```
    ![Screenshot](loop2perm.png)

4. **Run the script**  
    ```bash
    ./loop.sh
    ```
    ![Screenshot](loop3.png)

---
## For Loop Example 2: Iterating Over Strings

This script demonstrates iterating over a list of strings.

```bash
#!/bin/bash

for fruit in apple banana orange
do
  echo "Fruit: $fruit"
done
```

### Step-by-Step Guide

1. **Open the script in vim**  
    ```bash
    vim loopExample2.sh
    ```
    ![Screenshot](loopexampleperm.png)

2. **Inside the vim editor (editing the script)**  
    ![Screenshot](loopcounting.png)

3. **Make the script executable**  
    ```bash
    chmod +x loopExample2.sh
    ```
   ![Screenshot](loopexampleperm.png)
4. **Run the script**  
    ```bash
    ./loopExample2sh
    ```
    ![Screenshot](loopsuccess.png)

---

## For Loop Example 3: C-Style For Loop

This script uses the C-style syntax for `for` loops.

```bash
#!/bin/bash

for ((i=1; i<=5; i++))
do
  echo "Counter: $i"
done
```

### Step-by-Step Guide

1. **Open the script in vim**  
    ```bash
    vim whileloop.sh
   ```
**And make it executable**
    ![Screenshot](loopexampleperm.png)

 **Inside the vim editor (editing the script)**  
    ![Screenshot](elif2.png)


 **Run the script**  
    ```bash
    ./whileloop.sh
    ```
    ![Screenshot](elifwork.png)

---

1. **Other examples**  
   

 **Inside the vim editor (editing the script)**  
    ![Screenshot](forloopout.png)

**And make it executable**
    ![Screenshot](forloopout.png)

    
 
    ![Screenshot](elifwork.png)
     
      ![Screenshot](cstyle.png)
        edit
        ![Screenshot](forcsyntax.png)
        **Run the script**  
          ![Screenshot](cstylesucc.png)

---
