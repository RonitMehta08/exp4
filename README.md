# 📘 Study of Sets in Python

**File:** `exp4.ipynb`  
**Experiment:** Study of Sets in Python
**Name:** Ronit Mehta
**PRN:** 25070123094

---

## 🎯 Aim
To study and implement **Python Sets** and perform operations such as creation of sets, handling duplicate values, adding and removing elements, performing set operations, understanding `frozenset`, and solving real-life problems using sets.

---

## 📖 Theory
A **set** in Python is an unordered collection of **unique elements**, written inside curly braces `{}`.

### Key properties of Python sets:
- Do not allow duplicate values
- Elements are unordered
- Sets are mutable (elements can be added or removed)
- Indexing is not supported
- Support mathematical operations like:
  - Union
  - Intersection
  - Difference
  - Symmetric Difference

Python also provides **`frozenset`**, which is an immutable version of a set and cannot be modified after creation.

Sets are commonly used for duplicate removal, membership testing, and solving problems involving relationships between groups.

---

## 🧠 Algorithm (Cell-wise)

### Cell 1 – Creating a Set
1. Create a set of elements.
2. Display the set.
3. Attempt to access an element using indexing to show that sets do not support indexing.

---

### Cell 2 – Mixed Data Types in Set
1. Create a set containing different data types.
2. Display the set to observe how elements are stored uniquely.

---

### Cell 3 – Handling Duplicate Elements
1. Create a set with duplicate values.
2. Display the set.
3. Observe that duplicate elements are automatically removed.

---

### Cell 4 – Adding Elements to a Set
1. Create a set.
2. Add a new element using the `add()` method.
3. Display the updated set.

---

### Cell 5 – Removing Elements from a Set
1. Create a set.
2. Remove an element using the `remove()` method.
3. Display the modified set.

---

### Cell 6 – Set Operations
1. Create two sets with numeric values.
2. Perform:
   - Union
   - Intersection
   - Difference
   - Symmetric Difference
3. Display the results using operators and methods.

---

### Cell 7 – Frozenset
1. Create a `frozenset`.
2. Display its type.
3. Attempt to modify it to demonstrate immutability.

---

### Cell 8 – Removing Duplicates Using Set
1. Create a list containing duplicate elements.
2. Convert the list into a set.
3. Display the unique elements.

---

### Cell 9 – Finding Common Elements
1. Create multiple sets.
2. Find common elements using intersection.
3. Display the result.

---

### Cell 10 – Sports Club Membership
1. Create sets representing different sports clubs.
2. Find:
   - Students playing both sports
   - Students playing only one sport
3. Display the results.

---

### Cell 11 – Attendance Management
1. Create a set of all students.
2. Create a set of present students.
3. Find absent students using set difference.
4. Display the result.

---

### Cell 12 – Remove vs Discard
1. Create a set of elements.
2. Remove an element using `remove()`.
3. Remove another element using `discard()`.
4. Observe the difference in behavior.

---

## ✅ Conclusion
This experiment demonstrates the effective use of **Python Sets** for handling unique data and performing mathematical set operations. It highlights how sets simplify tasks such as duplicate removal, comparison between groups, and real-life problem solving.

The experiment also clarifies the difference between **mutable sets** and **immutable frozensets**, making sets a powerful and efficient data structure in Python.

---
