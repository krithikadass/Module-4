# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(key_value.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(key_value.items(), key=lambda kv: kv[1], kv[0])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
```
def dictionairy(): 
key_value ={} 
key_value[2] = 56       
key_value[1] = 2 
key_value[5] = 12 
key_value[4] = 24 
key_value[6] = 18      
key_value[3] = 323 
print ("Keys and Values sorted in alphabetical order by the key") 
print(sorted(key_value.items(), key = lambda kv:(kv[1], kv[0])))
```
## Sample Output
![442492387-121ab2ac-a1ee-499d-8612-4a12c7c9a811](https://github.com/user-attachments/assets/12dcafb1-d204-4bb0-b02b-6f88baa6ccc3)

## Result
Thus, the program has been successfully executed.
