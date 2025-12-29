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
```
import numpy as np
val=eval(input())
arr=np.array(val)
print("Printing Input Array")
print(arr)
print("\nPrinting array of items in the third column from all rows")
print(arr[:,2])
```
## Output
<img width="816" height="364" alt="530351597-a4a246f1-b0db-4bf5-b4b6-3f1615eaf09a" src="https://github.com/user-attachments/assets/4ad23d0e-41d1-498d-9bcb-5b01d393e4d2" />

## Result
The program successfully takes a 2D NumPy array, deletes the second column (index 1), and inserts a new column at the same position.
