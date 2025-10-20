# NumPy Program: Column-wise Sorting of a 2D Array

## 🎯 Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

## 🧠 Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

## 🧾 Program
import numpy as np

a=eval(input())

b=np.array(a)

print(f"Given array \n {b}")

print()

print(np.sort(b,axis=0))

## Output
<img width="1096" height="778" alt="Screenshot (96)" src="https://github.com/user-attachments/assets/5855d2a9-323c-4225-a1e1-0c33bdf195dc" />

## Result
Thus the program is executed successfully.
