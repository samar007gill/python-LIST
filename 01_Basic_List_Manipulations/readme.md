

---

#### ***📚 Python Lists Guide 📚***






---

### 📜 **__Table of Contents__**
- [🔍 **__What is a List?__**](#what-is-a-list)
- [⚡ **__Important Points__**](#important-points)
- [🛠️ **__Common List Functions__**](#common-list-functions)
    - 📌 `append()`
    - 📌 `clear()`
    - 📌 `copy()`
    - 📌 `count()`
    - 📌 `extend()`
    - 📌 `index()`
    - 📌 `insert()`
    - 📌 `pop()`
    - 📌 `remove()`
    - 📌 `reverse()`
    - 📌 `sort()`
- [🔄 **__List Equality__**](#list-equality)
- [📊 **__Indexing & Slicing__**](#indexing-slicing)
- [➕ **__Modifying & Combining Lists__**](#modifying-combining-lists)
- [🧩 **__Nested Lists__**](#nested-lists)
- [✏️ **__Changing List Items__**](#changing-list-items)
- [➕ **__List Operations__**](#list-operations)
- [🔄 **__Iterating Over Lists__**](#iterating-over-lists)
- [➕ **__Adding Items__**](#adding-items)
- [❌ **__Removing Items__**](#removing-items)
- [⚙️ **__Changing and Deleting Items__**](#changing-deleting-items)
- [🔀 **__Sorting Lists__**](#sorting-lists)

---

### 🔍 **__What is a List?__**
A list is an ordered collection of items, capable of holding various data types (numbers, strings, etc.), and it’s **mutable**, meaning its content can be changed.

Example:
```python
my_list = ["Alice", 25, "Engineer"]
```

---

### ⚡ **__Important Points__**
- **Ordered**: The sequence of items is preserved.
- **Mutable**: You can modify the content.
- **Flexible**: Different data types can be stored.

---

### 🛠️ **__Common List Functions__**

#### 📌 `append(x)`
Adds an item `x` at the end of the list.
```python
numbers = [1, 2, 3]
numbers.append(4)  # [1, 2, 3, 4]
```

#### 📌 `clear()`
Removes all items in the list.
```python
numbers.clear()  # []
```

#### 📌 `copy()`
Creates a shallow copy of the list.
```python
original = [1, 2, 3]
copied = original.copy()  # [1, 2, 3]
```

#### 📌 `count(x)`
Counts how many times `x` appears in the list.
```python
numbers = [1, 2, 2, 3]
numbers.count(2)  # 2
```

#### 📌 `extend()`
Adds elements from another iterable to the list.
```python
lst1 = [1, 2]
lst1.extend([3, 4])  # [1, 2, 3, 4]
```

#### 📌 `index(x)`
Returns the first index of item `x`.
```python
lst = [10, 20, 30]
lst.index(20)  # 1
```

#### 📌 `insert(i, x)`
Inserts item `x` at index `i`.
```python
lst = [1, 3]
lst.insert(1, 2)  # [1, 2, 3]
```

#### 📌 `pop(i=-1)`
Removes and returns the item at index `i`.
```python
lst = [1, 2, 3]
lst.pop()  # 3
```

#### 📌 `remove(x)`
Removes the first occurrence of item `x`.
```python
lst = [1, 2, 3]
lst.remove(2)  # [1, 3]
```

#### 📌 `reverse()`
Reverses the order of items in the list.
```python
lst = [1, 2, 3]
lst.reverse()  # [3, 2, 1]
```

#### 📌 `sort()`
Sorts the list in ascending or descending order.
```python
lst = [3, 1, 2]
lst.sort()  # [1, 2, 3]
```

---

### 🔄 **__List Equality__**
To check if two lists are equal, you can use the equality operator (`==`).
```python
lst1 = [1, 2, 3]
lst2 = [1, 2, 3]
print(lst1 == lst2)  # True
```

---

### 📊 **__Indexing & Slicing__**
Use indexes to access elements. Negative indexes start from the end.

```python
lst = [1, 2, 3]
print(lst[0])  # 1
print(lst[-1])  # 3
print(lst[1:])  # [2, 3]
```

---

### ➕ **__Modifying & Combining Lists__**

You can combine lists using the `+` operator and modify them using indexes.
```python
lst1 = [1, 2]
lst2 = [3, 4]
combined = lst1 + lst2  # [1, 2, 3, 4]

lst1[0] = 100
print(lst1)  # [100, 2]
```

---

### 🧩 **__Nested Lists__**
Lists can contain other lists (i.e., nested lists).
```python
nested = [[1, 2], [3, 4]]
print(nested[0])  # [1, 2]
```

---

### ✏️ **__Changing List Items__**
You can modify list items directly using indexes.
```python
lst = [10, 20, 30]
lst[1] = 25
print(lst)  # [10, 25, 30]
```

---

### ➕ **__List Operations__**

#### Multiplying Lists:
```python
lst = [1, 2]
lst = lst * 3  # [1, 2, 1, 2, 1, 2]
```

#### Concatenating Lists:
```python
lst1 = [1, 2]
lst2 = [3, 4]
lst = lst1 + lst2  # [1, 2, 3, 4]
```

---

### 🔄 **__Iterating Over Lists__**
Use a `for` loop to iterate through list items.
```python
lst = ["apple", "banana", "cherry"]
for item in lst:
    print(item)
```

---

### ➕ **__Adding Items__**
You can add new items to the list using `append()`.
```python
lst = [1]
lst.append(2)  # [1, 2]
```

---

### ❌ **__Removing Items__**
Use `remove()` to delete an item.
```python
lst = [1, 2, 3]
lst.remove(2)  # [1, 3]
```

---

### ⚙️ **__Changing and Deleting Items__**

To modify or delete items, you can use assignments and the `del` statement.
```python
lst = [1, 2, 3]
lst[1] = 10
del lst[0]
print(lst)  # [10, 3]
```

---

### 🔀 **__Sorting Lists__**

Sort lists in ascending or descending order using `sort()`.
```python
lst = ["banana", "apple", "cherry"]
lst.sort()  # ["apple", "banana", "cherry"]
```

---

