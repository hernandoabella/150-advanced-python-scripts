# Check if a Number is Even or Odd  

```python
num = int(input("Enter a number: "))

if num % 2 == 0:
    print("The number is Even")
else:
    print("The number is Odd")
```

This script checks whether a given number is **even or odd** by using the **modulus operator (`%`)**.

---

## Walkthrough

### Step 1: Take User Input  
We first ask the user to input a number:

```python
num = int(input("Enter a number: "))
```
- `input()` takes user input as a string.  
- `int()` converts it into an integer.

---

### Step 2: Check if the Number is Even or Odd  
We use the modulus operator (`%`) to check if the number is divisible by `2`:

```python
if num % 2 == 0:
    print("The number is Even")
else:
    print("The number is Odd")
```

#### How does it work?  
- If `num % 2 == 0`, the number is even.  
- Otherwise, it's odd.

---

### Step 3: Print the Result  
After checking, the script prints whether the number is **Even** or **Odd**.

#### Example Runs  
```
Enter a number: 8
The number is Even
```
```
Enter a number: 13
The number is Odd
```

---

## Next Steps  
Try modifying the script to:  
- Handle negative numbers.  
- Check for zero separately.  
- Allow the user to enter multiple numbers in one run.