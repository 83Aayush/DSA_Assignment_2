# 📚 Library Book Management System (Python)

## 🧠 Overview
This project is a simple **Library Book Management System** implemented in **Python** using:
- **Linked List** (for book records)
- **Stack** (for transaction history and undo feature)

It allows the librarian to:
- Add, delete, search, and display books  
- Issue and return books  
- Undo the last transaction  
- View recent transactions

---

## 🧩 Data Structures Used

### 1️⃣ **Linked List**
Used to manage the list of books.  
Each node (BookNode) contains:
- Book ID  
- Title  
- Author  
- Status (Available/Issued)

### 2️⃣ **Stack**
Used to record all transactions (Issue / Return).  
Helps implement the **Undo Last Transaction** feature.

---

## ⚙️ Features

| Function | Description |
|-----------|--------------|
| Add Book | Adds a new book to the linked list |
| Delete Book | Removes a book using its ID |
| Search Book | Finds a book by ID |
| Display All Books | Shows all books currently in the system |
| Issue Book | Marks a book as “Issued” |
| Return Book | Marks a book as “Available” |
| Undo Last Transaction | Reverses the last Issue/Return |
| View Transactions | Displays all recent transactions |

---

## 🧮 Classes & Methods

### 📗 `BookNode`
- Represents a book in the library.
- Stores book details and pointer to the next book.

### 📘 `BookLinkedList`
- Manages all book operations:
  - `insertBook()`
  - `deleteBook()`
  - `searchBook()`
  - `displayBooks()`

### 📕 `Stack`
- Handles transactions.
  - `push()`, `pop()`, `is_empty()`, `display()`

### 📙 `TransactionSystem`
- Controls the library operations:
  - `issueBook()`
  - `returnBook()`
  - `undoTransaction()`
  - `viewTransactions()`

