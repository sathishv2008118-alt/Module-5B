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

## 💻 Program
```
import pandas as pd
l1=eval(input())
df=pd.DataFrame(l1)
print(df)
```

## Output
<img width="816" height="342" alt="530351774-4c53171e-fd38-4023-a171-ce552550a4c2" src="https://github.com/user-attachments/assets/b8bbf577-691c-491c-8580-104ea138d1f0" />


## Result
The program successfully creates a Pandas DataFrame from a dictionary and applies custom index labels. The DataFrame displays all columns (name, score, attempts, qualify) along with the specified row indices (a, b, c, d, e). ``# 🧪 Pandas Program: Join Two DataFrames Along Rows
