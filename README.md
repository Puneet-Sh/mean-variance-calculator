# 📊 Matrix Statistics Calculator

### Author: Puneet Sharma

This Python script takes a list of 9 numbers and performs various statistical calculations by reshaping the list into a 3x3 matrix using NumPy.

---

## ✅ Features

For a given list of 9 numbers, the script computes:

- **Mean**
- **Variance**
- **Standard Deviation**
- **Maximum**
- **Minimum**
- **Sum**

Each of the above statistics is calculated:
- Across rows
- Across columns
- For the entire matrix (flattened)

---

## 🧮 Example

```python
from this import calculate

result = calculate([1, 2, 3, 4, 5, 6, 7, 8, 9])
print(result)

Sample Output:

{
  'mean': [[4.0, 5.0, 6.0], [2.0, 5.0, 8.0], 5.0],
  'variance': [[6.0, 6.0, 6.0], [0.666..., 0.666..., 0.666...], 6.666...],
  'standard deviation': [[2.449..., 2.449..., 2.449...], [0.816..., 0.816..., 0.816...], 2.581...],
  ...
}
'''
