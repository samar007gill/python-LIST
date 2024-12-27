
---

# 🔁 **Python reverse() Method**

The `reverse()` method reverses the order of elements in a list.

### 👣 **Steps Explained:**

1. **Define the List:**  
   We start with this list of numbers:  
   ```python
   list = [10, 20, 30, 40, 50] 📑
   ```
   We want to reverse the order of these numbers.

2. **Call the reverse() Method:**  
   We use `reverse()` to reverse the order:  
   ```python
   list.reverse() 🔄
   ```

3. **Output the Result:**  
   After reversing, we print the list:  
   ```python
   print(list) 🖨️
   ```
   The output will be:  
   ```python
   [50, 40, 30, 20, 10] 🔃
   ```
   The list is now reversed.

---

### 🔍 **What Happens Internally:**

The `reverse()` method changes the order of elements in the list. It works in place, meaning it directly modifies the original list. 🔧

### 📌 **Important Notes:**

- The `reverse()` method modifies the list in place and does not return a new list.  
- If the list is empty or contains one element, it will stay the same. 🚫  
- It only works on **mutable lists** (like Python lists). 🛠️
