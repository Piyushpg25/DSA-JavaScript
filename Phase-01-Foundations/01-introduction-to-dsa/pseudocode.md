
# Pseudocode

## What is Pseudocode?

Pseudocode is a simple, language-independent way of
describing the steps of an algorithm.

It helps us understand and design the logic before
writing actual code.

## Why Use Pseudocode?

- Understand the problem.
- Plan the solution.
- Avoid syntax distractions.
- Convert logic into code more easily.

## Example: Find the Smallest Element

### Problem

Find the smallest element in an array.

### Input

[7, 2, 15, 4, 9]

### Output

2

### Pseudocode

1. Take the array.
2. Assume the first element is the minimum.
3. Traverse the remaining elements.
4. If the current element is smaller than the minimum,
   update the minimum.
5. Print the minimum after the loop.

### JavaScript Solution

let arr = [7, 2, 15, 4, 9];

let min = arr[0];

for (let i = 1; i < arr.length; i++) {
  if (arr[i] < min) {
    min = arr[i];
  }
}

console.log(min);

### Output

2
