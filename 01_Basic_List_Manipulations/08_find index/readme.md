

---

# 🔍 **Python index() Method**

The `index()` method in Python helps you find the position (index) of an element in a list.

### 👣 **Steps Explained:**

1. **Define the List:**  
   We start with a list of numbers:  
   ```python
   list = [10, 20, 30, 40, 50] 📝
   ```
   We want to find the index of the number `40`.

2. **Call the index() Method:**  
   We use `index()` to find the position of `40`:  
   ```python
   result = list.index(40) 📍
   ```

3. **Output the Result:**  
   After calling `index(40)`, we print the result:  
   ```python
   print(result) 📃
   ```
   The output will be:  
   ```python
   3
   ```
   This means `40` is at index 3.

---

### 🔍 **What Happens Internally:**

The `index()` method checks each item in the list from the start and returns the index of the **first occurrence** of the element.

### 📌 **Important Notes:**

- The `index()` method returns the **first** index of the specified element.  
- If the element is not found, it raises a `ValueError`. ⚠️  
- The index starts at `0`, so the first element has index `0`, the second has index `1`, and so on. 🔢
