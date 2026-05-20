# 🥗 Ingredient Management System

A simple and efficient **Ingredient Management System built in C** to organize, store, and manage inventory data. This project demonstrates the use of core programming concepts such as structures, file handling, searching, sorting, and dynamic memory management.

---

## 🚀 Overview

This project allows users to manage ingredients within an inventory system by supporting operations such as adding, updating, deleting, and searching for ingredients. The system is designed to simulate a lightweight inventory database while reinforcing foundational computer science concepts.

---

## ✨ Features

- Add new ingredients
- Delete ingredients from inventory
- Update ingredient information
- Search ingredients by name or ID
- Display all ingredients
- Store inventory data using files
- Organize inventory efficiently

---

## 🧠 Key Concepts

- Structures (`struct`)
- Arrays and pointers
- Dynamic memory allocation
- File I/O in C
- Searching and sorting algorithms
- Modular programming

---

## 📂 Data Representation

Each ingredient contains:

- Ingredient name
- Quantity
- Category/type
- Unique ID

Example structure:

```c
typedef struct {
    int id;
    char name[50];
    int quantity;
    char category[50];
} Ingredient;
```

---

## ⚙️ Functionalities

### ➕ Add Ingredient
Stores a new ingredient in the inventory system.

### 🔍 Search Ingredient
Find ingredients quickly using:
- Name
- ID

### ✏️ Update Ingredient
Modify ingredient details such as:
- quantity
- category
- name

### ❌ Delete Ingredient
Remove ingredients safely from the system.

### 📋 Display Inventory
Display all ingredients in a clean and organized format.

---

## ▶️ How to Run

1. Compile the program:

```bash
gcc ingredient_system.c -o ingredient_system
```

2. Run the executable:

```bash
./ingredient_system
```

---

## 🧪 Sample Output

```text
==== Ingredient Inventory ====

1. Tomatoes
   Quantity: 25
   Category: Vegetables

2. Milk
   Quantity: 10
   Category: Dairy
```

---

## ⏱ Time Complexity

| Operation | Complexity |
|----------|------------|
| Add Ingredient | O(1) |
| Search Ingredient | O(n) |
| Delete Ingredient | O(n) |
| Display Inventory | O(n) |

---

## 📂 Project Structure

```text
├── ingredient_system.c    # Main implementation
├── data.txt               # Stored inventory data
├── README.md
```

---

## 📌 Notes

- This project focuses on applying foundational programming concepts in C.
- Designed as a lightweight inventory management system.
- Can be extended with:
  - database integration
  - GUI support
  - barcode scanning
  - expiry notifications

---

## 🔮 Future Improvements

- Add login/authentication system
- Implement linked lists or hash maps for optimization
- Export inventory reports
- Add expiry-date tracking
- Build a graphical interface

---

## 👨‍💻 Author

**Yuvraj Kapoor**  
Computer Science Student
