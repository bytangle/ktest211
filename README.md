## 1. Nested Object Flattening

**Problem:**  
Write a function to flatten a deeply nested JavaScript object into a single-level object with dot-separated keys.

### Example

```ts
Input:
{
  a: {
    b: {
      c: 5
    }
  },
  d: 10
}

Output:
{
  "a.b.c": 5,
  "d": 10
}
```

## 2. Find Missing Number

**Problem:**  
You are given an array of `n` unique integers where each integer is between `1` and `n+1` (inclusive), but one number is missing. Return the missing number.  
Your solution should run in **O(n)** time and **O(1)** space.

---

### Example 1

**Input:**  
`[1, 2, 4, 5, 6]`

**Expected Output:**  
`3`

---

### Example 2

**Input:**  
`[2, 3, 4, 5, 6, 7, 8]`

**Expected Output:**  
`1`

## 3. String Permutation Validator

**Problem:**  
Write a function that checks whether two strings are permutations of each other.  
Two strings are permutations if they contain the same characters with the same frequency, in any order.

---

### Example 1

**Input:**  
`"listen", "silent"`

**Expected Output:**  
`true`

---

### Example 2

**Input:**  
`"hello", "world"`

**Expected Output:**  
`false`
