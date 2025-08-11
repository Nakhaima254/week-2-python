# Python List Operations Example

This project demonstrates basic operations on a Python list, including adding, inserting, extending, removing, and sorting elements.

## 📜 Code Overview

```python
my_list = []
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)
my_list.insert(1, 15)  # Insert 15 at index 1
my_list.extend([50, 60, 70])  # Extend the list with multiple values
my_list.pop()  # Remove the last item from the list
my_list.sort()  # Sort the list in ascending order

print(my_list[3])  # Print the item at index 3
```

## 🔹 Step-by-Step Explanation

1. **Initialize an Empty List**

   ```python
   my_list = []
   ```

   Creates an empty list to store numbers.

2. **Append Elements**

   ```python
   my_list.append(10)
   my_list.append(20)
   my_list.append(30)
   my_list.append(40)
   ```

   Adds elements to the end of the list.

3. **Insert an Element**

   ```python
   my_list.insert(1, 15)
   ```

   Inserts `15` at index `1`.

4. **Extend the List**

   ```python
   my_list.extend([50, 60, 70])
   ```

   Adds multiple elements at once.

5. **Remove the Last Element**

   ```python
   my_list.pop()
   ```

   Removes the last element (`70`).

6. **Sort the List**

   ```python
   my_list.sort()
   ```

   Sorts the list in ascending order.

7. **Access an Element by Index**

   ```python
   print(my_list[3])
   ```

   Prints the element at index `3` in the sorted list.

## 📌 Expected Output

When you run the script, the output will be:

```
30
```

## 🛠 How to Run

1. Save the code in a file, for example:

   ```
   list_operations.py
   ```
2. Run it in a terminal:

   ```bash
   python list_operations.py
   ```
