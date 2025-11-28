# 🧪 Pandas Program: Join Two DataFrames Along Rows

## 🎯 AIM

To write a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame.

---

## 🧠 ALGORITHM

1. **Import Libraries**: Import the `pandas` library.
2. **Create First DataFrame**: Use a dictionary to create `student_data1`.
3. **Create Second DataFrame**: Use another dictionary to create `student_data2`.
4. **Concatenate DataFrames**: Use `pd.concat()` with `axis=0` to concatenate both DataFrames row-wise.
5. **Display Result**: Print the new combined DataFrame.

---

## 💻 Program :

    import pandas as pd
    d=eval(input())
    df=pd.DataFrame(d)
    print("Original Dataframe",end='\n ')
    print(df)
    new=eval(input())
    df.loc[len(df)]=new
    print("combined Dataframe",end='\n ')
    print(df)

## Output :

<img width="1176" height="892" alt="image" src="https://github.com/user-attachments/assets/0bc6ddc2-a4e4-4229-8115-e3cc4eacb7ae" />


## Result :
Thus the Python program using Pandas to join two DataFrames along rows is executed successfully.
