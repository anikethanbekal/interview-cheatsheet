---
title: Sum of all elements in an array
tags:
  - java
  - python
  - numbers
  - array
  - easy
categories:
  - Programming
  - Coding
difficulty: easy
background: bg-[#e0f2fe]
badge_color: text-blue-800 bg-blue-100
topic: number-manipulation
date: 2025-07-01
author: Anikethan Bekal
intro: |
   Summing all elements in an array is a basic interview problem, testing iteration and aggregation logic.
---

# 🧠 Problem: Sum of all elements in an array

Given an array of integers, return the sum of all elements.

**Category**: Numbers  
**Difficulty**: Easy  
**Tags**: numbers, array, sum

---

## ✅ Requirements
- **Input**: Array of integers
- **Output**: Integer, sum of all elements
- **Constraints**: Array is non-empty

---

## 🧪 Example(s)
```text
Input: [3, 7, 2, 9, 4]
Output: 25
```

---

## ☕ Java Solution
```java
// Method 1: Iterative
public static int sumArray(int[] arr) {
    int sum = 0;
    for (int num : arr) {
        sum += num;
    }
    return sum;
}

// Method 2: Using Java Streams
public static int sumArrayStream(int[] arr) {
    return Arrays.stream(arr).sum();
}
```

## 🔵🟡 Python Solution
```python
# Method 1: Iterative
def sum_array(arr):
    total = 0
    for num in arr:
        total += num
    return total

# Method 2: Using built-in
def sum_array_builtin(arr):
    return sum(arr)
```

---

## 🔍 Explanation
- Iterate through the array and add each element to the sum.
- Can also use built-in functions for simplicity.

---

## ⏱️ Time & Space Complexity
| Language | Time Complexity | Space Complexity | Notes |
|----------|-----------------|------------------|-------|
| Java     | O(n)            | O(1)             | n = array length |
| Python   | O(n)            | O(1)             | n = array length |

---

## ⚠️ Interview Tips / Notes
- Discuss edge cases (empty array, single element).
- Built-in functions are preferred for readability.

---

## 🏷 Tags
`numbers`, `python`, `java`, `sum`, `easy`, `interview`, `array`
--- 