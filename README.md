# Data Structures in Java

## 📌 Project Overview
This project contains **basic and exam-friendly Java implementations** of common data structures.
All codes are written in a **simple, easy-to-understand format**, suitable for learning, labs, and viva/exams.

---

## 📂 Included Implementations

### 1️⃣ Stack using Queue (Dequeue Friendly)
**Class:** `StackQueueDequeueFriendly`

- Stack implemented using **two queues**
- **Pop operation:** O(1)
- **Push operation:** O(n)

**Operations:**
- `push(int x)` – Insert element into stack  
- `pop()` – Remove top element  

---

### 2️⃣ Array Circular Queue
**Class:** `ArrayCircularQueue`

- Queue implemented using an **array**
- Uses **circular indexing** to efficiently utilize space
- Prevents unused memory slots

**Operations:**
- `enqueue(int x)` – Insert element
- `dequeue()` – Remove element

---

### 3️⃣ Singly Linked List
**Class:** `SinglyLinkedList`

- Each node stores data and a reference to the next node
- Dynamic memory allocation

**Operations:**
- `insert(int x)` – Insert at beginning
- `delete()` – Delete from beginning
- `display()` – Display list elements

---

### 4️⃣ Doubly Linked List
**Class:** `DoublyLinkedList`

- Each node contains **previous and next references**
- Allows traversal in both directions

**Operations:**
- `insert(int x)` – Insert at beginning
- `delete()` – Delete from beginning
- `display()` – Display list elements

---

## 🛠 Technologies Used
- Java
- Java Collections Framework (for Queue-based stack)

---

## 🎯 Purpose
- Learn core data structure concepts
- Practice Java implementations
- Prepare for **exams, labs, and interviews**

---

## 🚀 How to Run
1. Open the project in any Java IDE (IntelliJ / Eclipse / NetBeans)
2. Compile the required `.java` file
3. Run the `main()` method

---

## ✍️ Author
**Nimz**

---

## 📌 Future Enhancements
- Add stack using array
- Add queue using linked list
- Add comments for time complexity
- Add menu-driven programs
