

---

# 📝 **Python Lists**

Lists in Python store multiple items in a single variable. They are ordered, changeable, and allow duplicates.

### 📋 **Basic Example**

```python
numbers = [1, 2, 3, 4, 5]
print(numbers)
```

✨ **Output:**

```python
[1, 2, 3, 4, 5]
```

### 🛠️ **Key Features**

1. **Dynamic Size:** Lists can grow or shrink by adding or removing items.
   ```python
   numbers.append(6)  # Add
   numbers.remove(2)  # Remove
   ```

2. **Heterogeneous Elements:** Lists can hold different types of data.
   ```python
   mixed = [1, "apple", 3.14, True]
   ```

3. **Mutability:** You can change list elements.
   ```python
   numbers[0] = 10  # Change the first element
   ```

4. **Slicing:** Extract part of a list.
   ```python
   part = numbers[1:4]
   ```

5. **List Comprehensions:** Create lists in one line.
   ```python
   squares = [x**2 for x in range(1, 6)]
   ```

### 🔄 **Looping Through Lists**

You can use loops to go through list items:

```python
for number in numbers:
    print(number)
```

### 🔧 **List Operations**

- **Sorting:** `numbers.sort()`
- **Reversing:** `numbers.reverse()`
- **Nested Lists:** Lists inside lists.
  ```python
  nested = [[1, 2], [3, 4]]
  ```

### 💡 **Tips**

- Use list comprehensions for cleaner code.
- Avoid naming your list `list` to prevent confusion.

---

### 🌟 **Happy Coding!**

