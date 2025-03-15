## swap_two_variables.md

```
a, b = 5, 10
a, b = b, a

print("a =", a)
print("b =", b)
```

This script demonstrates **how to swap the values of two variables** in Python **without using a temporary variable**.
  
### 📖 Walkthrough:

### Step 1: Define Two Variables 
First, we assign values to two variables:

```
a, b = 5, 10
```

### Step 2: Swap the Values
We can swap values in a **single line** using **tuple unpacking**:

```
a, b = b, a
```
**What happens here?**
-   Python **simultaneously** swaps the values of `a` and `b`.
-   This means `b` takes `a`'s value, and `a` takes `b`'s value.

**No temporary variable is needed!**

### Step 3: Print the Swapped Values
 Now, we print the values to verify the swap:
```
print("a =", a)
print("b =", b)
```
