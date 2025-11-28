# NumPy Program: Replace the Second Column in a 2D Array

## 🎯 Aim
To write a **NumPy** program that deletes the second column from a given 2D array and inserts a new column at the same position.

## 🧠 Algorithm
1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Get a 2D NumPy array and a new column (as another array) from the user.
3. **Delete Column**: Use `np.delete()` to remove the second column (index 1) from the original array.
4. **Insert Column**: Use `np.insert()` to insert the new column at the second column's original position.
5. **Display Result**: Print the updated array with the replaced column.

## 🧾 Program :

    import numpy as np
    arr = np.array(eval(input()))
    a=arr.reshape(4,3)
    column_sums=sum(a[:,1])
    print(a)
    print(column_sums)

## Output :
<img width="1095" height="494" alt="image" src="https://github.com/user-attachments/assets/f792ba35-f4f8-406b-b371-8c936a7d17ef" />


## Result :
Thus the python program to find the sum of Second column in a given numpy array is executed successfully.
