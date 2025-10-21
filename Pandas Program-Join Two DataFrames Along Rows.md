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

## 💻 Program
```
import pandas as pd
import numpy as np
std1 = {
    'name': ['Alice', 'Bob', 'Charlie'],
    'score': [85, 92, 78],
    'attempts': [1, 3, 2,],
    'qualify': ['yes', 'yes', 'no']
}
std2 = {
    'name': ['David', 'Eva'],
    'score': [ 90, 88],
    'attempts': [3, 1],
    'qualify': [ 'yes', 'yes']
}
d1=pd.DataFrame(std1)
d2=pd.DataFrame(std2)
print(pb.concat(d1,d2))
```

Add code here

## Output
![alt text](<Screenshot (63).png>)
## Result