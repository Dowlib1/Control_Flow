# Control_Flow
if(s) are used in control floews other; else, elif, case, fi, case and esac
# Control Flow in Scripting
-----------------------
# For Loop Examples in Shell Scripting
??//
# For Loop Examples in Shell Scripting

This README demonstrates basic usage of `for` loops in shell scripting, as well as how to use control flow statements like `if`, `elif`, and `else`. Each example includes a space to insert relevant screenshots for every step: editing with `vim`, making the script executable with `chmod +x`, running the script, and the script as shown inside the vim editor.

---

## Example 1: Using an If-Else Statement to Check a Number

**Script:**
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

#### 1. Open the script in vim
- Command:  
  ```bash
  vim check_number.sh
  ```
- _**Insert screenshot here**_

#### 2. Inside the vim editor (editing the script)
- _**Insert screenshot here**_

#### 3. Make the script executable
- Command:  
  ```bash
  chmod +x check_number.sh
  ```
- _**Insert screenshot here**_

#### 4. Run the script
- Command:  
  ```bash
  ./check_number.sh
  ```
- _**Insert screenshot here**_

---

## Example 2: Printing Numbers from 1 to 5 with a For Loop

**Script:**
```bash
#!/bin/bash

for i in 1 2 3 4 5
do
  echo "Number: $i"
done
```

### Steps

#### 1. Open the script in vim
- Command:  
  ```bash
  vim for_loop_1.sh
  ```
- _**Insert screenshot here**_

#### 2. Inside the vim editor
- _**Insert screenshot here**_

#### 3. Make the script executable
- Command:  
  ```bash
  chmod +x for_loop_1.sh
  ```
- _**Insert screenshot here**_

#### 4. Run the script
- Command:  
  ```bash
  ./for_loop_1.sh
  ```
- _**Insert screenshot here**_

---

## Example 3: Iterating Over a List of Strings

**Script:**
```bash
#!/bin/bash

for fruit in apple banana orange
do
  echo "Fruit: $fruit"
done
```

### Steps

#### 1. Open the script in vim
- Command:  
  ```bash
  vim for_loop_2.sh
  ```
- _**Insert screenshot here**_

#### 2. Inside the vim editor
- _**Insert screenshot here**_

#### 3. Make the script executable
- Command:  
  ```bash
  chmod +x for_loop_2.sh
  ```
- _**Insert screenshot here**_

#### 4. Run the script
- Command:  
  ```bash
  ./for_loop_2.sh
  ```
- _**Insert screenshot here**_

---

## Example 4: For Loop with C-style Syntax

**Script:**
```bash
#!/bin/bash

for ((i=1; i<=5; i++))
do
  echo "Counter: $i"
done
```

### Steps

#### 1. Open the script in vim
- Command:  
  ```bash
  vim for_loop_3.sh
  ```
- _**Insert screenshot here**_

#### 2. Inside the vim editor
- _**Insert screenshot here**_

#### 3. Make the script executable
- Command:  
  ```bash
  chmod +x for_loop_3.sh
  ```
- _**Insert screenshot here**_

#### 4. Run the script
- Command:  
  ```bash
  ./for_loop_3.sh
  ```
- _**Insert screenshot here**_

---

## Notes

- Replace each `filename.sh` with your actual script's filename in the commands above.
- Insert your screenshots in the indicated sections for thorough documentation.

---

Happy scripting!


//??
---

## Example 1: Printing Numbers from 1 to 5

**Script:**
```bash
#!/bin/bash

for i in 1 2 3 4 5
do
  echo "Number: $i"
done
```

### Steps

#### 1. Open the script in vim
_**Insert screenshot here**_

#### 2. Inside the vim editor
_**Insert screenshot here**_

#### 3. Make the script executable
```bash
chmod +x filename.sh
```
_**Insert screenshot here**_

#### 4. Run the script
```bash
./filename.sh
```
_**Insert screenshot here**_

---

## Example 2: Iterating Over a List of Strings

**Script:**
```bash
#!/bin/bash

for fruit in apple banana orange
do
  echo "Fruit: $fruit"
done
```

### Steps

#### 1. Open the script in vim
_**Insert screenshot here**_

#### 2. Inside the vim editor
_**Insert screenshot here**_

#### 3. Make the script executable
```bash
chmod +x filename.sh
```
_**Insert screenshot here**_

#### 4. Run the script
```bash
./filename.sh
```
_**Insert screenshot here**_

---

## Example 3: For Loop with C-style Syntax

**Script:**
```bash
#!/bin/bash

for ((i=1; i<=5; i++))
do
  echo "Counter: $i"
done
```

### Steps

#### 1. Open the script in vim
_**Insert screenshot here**_

#### 2. Inside the vim editor
_**Insert screenshot here**_

#### 3. Make the script executable
```bash
chmod +x filename.sh
```
_**Insert screenshot here**_

#### 4. Run the script
```bash
./filename.sh
```
_**Insert screenshot here**_

---







----------------------
This repository, **@Dowlib1/Control_Flow**, contains an assignment focused on demonstrating control flow concepts in shell scripting. The main goal of this assignment is to illustrate how conditional statements can be used to make decisions based on user input in a Bash script.

## Assignment Overview

The assignment presents a simple script that reads a number from the user and determines whether the number is positive, negative, or zero. This is achieved using `if`, `elif`, and `else` control flow structures in Bash.

### Example Script

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

### How It Works

1. The script prompts the user to enter a number.
2. It evaluates the input:
    - If the number is greater than 0, it prints "The number is positive."
    - If the number is less than 0, it prints "The number is negative."
    - Otherwise, it prints "The number is zero."

This simple example showcases the usage of conditional statements in shell scripting, which are essential for implementing logic and decision-making in scripts.

## Screenshots

Screenshots demonstrating the script's execution are available in this repository.

## Getting Started

To run the script:

1. Clone this repository.
2. Save the script to a file, e.g., `check_number.sh`.
3. Make the script executable:
   ```bash
   chmod +x check_number.sh
   ```
4. Run the script:
   ```bash
   ./check_number.sh
   ```

## Learning Objectives

- Understand the basics of control flow in shell scripting.
- Learn how to use `if`, `elif`, and `else` statements.
- Practice reading user input and making decisions based on that input.

---

Feel free to explore the script and screenshots to deepen your understanding of control flow in scripting!
