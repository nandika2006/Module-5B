# Pandas Program: Create and Display a DataFrame with Custom Index Labels

## 🎯 Aim

To create and display a **DataFrame** using the **Pandas** library in Python from a given dictionary, and apply specific index labels to the rows.

---

## 🧠 Algorithm

1. **Import Libraries**: Import the required libraries – `pandas` and `numpy`.
2. **Create Dictionary**: Define a dictionary `exam_data` with keys: `'name'`, `'score'`, `'attempts'`, and `'qualify'`.
3. **Index Labels**: Create a list of custom index labels called `labels`.
4. **Create DataFrame**: Use `pd.DataFrame()` to create the DataFrame by passing the dictionary and index labels.
5. **Display Output**: Display the DataFrame using `print()` or by simply calling the DataFrame variable.

---

## 💻 Program :

    import pandas as pd
    data1 = {'s_id': ['S1', 'S2', 'S3', 'S4', 'S5'],'name': ['Dan', 'Ryder', 'Bryce', 'Bernal', 'Kwame'], 'marks': [200, 210, 190, 222, 199]}
    data2 = { 's_id': ['S4', 'S5', 'S6', 'S7', 'S8'], 'name': ['Scart', 'Willy', 'Dani', 'Kaise', 'Madeeha'], 'marks': [201, 200, 198, 219, 201]}
    df1 = pd.DataFrame(data1)
    df2 = pd.DataFrame(data2)
    print("Original DataFrames:")
    print(df1)
    print("-------------------------------------")
    print(df2)
    print()
    result = pd.concat([df1, df2], axis=1)
    print("Join the said two dataframes along columns:")
    print(result)

## Output :
<img width="1155" height="771" alt="image" src="https://github.com/user-attachments/assets/b3cd63b1-8ce8-4759-9938-4da2f4627ebd" />

## Result :
Thus the Pandas program to join the two given dataframes along columns and assign all data is executed successfully.
