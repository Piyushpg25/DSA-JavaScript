
# Problem-Solving Approach

## 4 Steps to Solve a Problem

### 1. Understand the Problem

Identify the input and expected output.

### 2. Analyze an Example

Solve the problem manually using a small example.

### 3. Build the Logic

Create a step-by-step approach before writing code.

### 4. Implement and Test

Write the code, perform a dry run, and check edge cases.

---

## Example: Sum of Array

### Problem

Calculate the sum of all elements in an array.

### Input

[12, 8, 20, 5, 15]

### Output

60

### Approach

1. Initialize sum = 0.
2. Traverse the array using a loop.
3. Add each element to sum using sum += arr[i].
4. Print sum after the loop.

### JavaScript

let arr = [12, 8, 20, 5, 15];
let sum = 0;

for (let i = 0; i < arr.length; i++) {
  sum += arr[i];
}

console.log(sum);

### Output

60
