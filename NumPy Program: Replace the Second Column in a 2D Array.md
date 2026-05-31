# NumPy Program: Replace the Second Column in a 2D Array

## 🎯 Aim
To write a **NumPy** program that deletes the second column from a given 2D array and inserts a new column at the same position.

## 🧠 Algorithm
1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Get a 2D NumPy array and a new column (as another array) from the user.
3. **Delete Column**: Use `np.delete()` to remove the second column (index 1) from the original array.
4. **Insert Column**: Use `np.insert()` to insert the new column at the second column's original position.
5. **Display Result**: Print the updated array with the replaced column.

## 🧾 Program

mport numpy as np

x = np.array([5, 2, 9, 7])
y = np.array([3, 2, 8, 10])

indices = np.where(x >= y)

print("Array x:", x)
print("Array y:", y)
print("Indices where x >= y:", indices[0])

## Output
<img width="1532" height="988" alt="image" src="https://github.com/user-attachments/assets/5f222c46-2843-4331-b0d8-e5e7c2441041" />


## Result
The NumPy program successfully finds the indices where elements in array x are greater than or equal to their corresponding elements in array y.
