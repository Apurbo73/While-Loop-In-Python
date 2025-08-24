# While-Loop-In-Python

Let’s break down your code step by step:

```python
i = 1                # Start with i = 1

n = int(input())     # Take input from the user (convert it into an integer)

while i <= n:        # Keep looping as long as i is less than or equal to n
    if (i % 2 != 0):   # Check if i is odd (remainder after division by 2 is not 0)
        print(i, "- This is a odd number")

    else:              # Otherwise, i must be even
        print(i, "- This is an even number")

    i = i + 1          # Increase i by 1 (so the loop moves toward stopping)
```

---

### What it does:

1. Starts at `i = 1`.
2. Runs a loop until `i` becomes greater than `n`.
3. Inside the loop:

   * If `i % 2 != 0` → means `i` is **odd**, so it prints `"odd number"`.
   * Else → means `i` is **even**, so it prints `"even number"`.
4. After each step, `i` increases by 1, so the loop eventually ends.

---

### Example run:

If the user enters `n = 5`:

* `i = 1` → odd → prints `1 - This is a odd number`
* `i = 2` → even → prints `2 - This is an even number`
* `i = 3` → odd → prints `3 - This is a odd number`
* `i = 4` → even → prints `4 - This is an even number`
* `i = 5` → odd → prints `5 - This is a odd number`
* Loop stops because `i = 6` is now greater than `n`.

**Output:**

```
1 - This is a odd number
2 - This is an even number
3 - This is a odd number
4 - This is an even number
5 - This is a odd number
```

---

👉 In short:
This program prints **all numbers from 1 to n** and labels each as **odd** or **even**.


