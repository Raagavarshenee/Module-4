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
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
# Original dictionary
d = {'c': 3, 'a': 1, 'd': 4, 'b': 2}

# Sort by keys
sorted_by_keys = dict(sorted(d.items()))

# Sort by values
sorted_by_values = dict(sorted(d.items(), key=lambda item: item[1]))

# Display results
print("Original Dictionary:", d)
print("Dictionary Sorted by Keys:", sorted_by_keys)
print("Dictionary Sorted by Values:", sorted_by_values)

## Sample Output
Original Dictionary: {'c': 3, 'a': 1, 'd': 4, 'b': 2}
Dictionary Sorted by Keys: {'a': 1, 'b': 2, 'c': 3, 'd': 4}
Dictionary Sorted by Values: {'a': 1, 'b': 2, 'c': 3, 'd': 4}

## Result
program is executed successfully.

