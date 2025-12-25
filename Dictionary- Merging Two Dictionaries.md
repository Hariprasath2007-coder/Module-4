## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program

Add code here
```
dict1 = {
    "name": "Alice",
    "age": 25,
    "city": "New York"
}

dict2 = {
    "age": 30,
    "country": "USA"
}

def merge(d1, d2):
    merged_dict = {**d1, **d2}  
    return merged_dict


result = merge(dict1, dict2)
print(result)
```
## Output
<img width="1003" height="208" alt="image" src="https://github.com/user-attachments/assets/7bc0301c-804c-4d89-aee5-4a74cdab78c6" />

## Result
Thus the program is executed successfully.
