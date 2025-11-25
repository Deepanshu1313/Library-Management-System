# 📚 Library Management System (JAVA)

A complete **Java-based Library Management System** built using **Object-Oriented Programming**, **Derby Embedded Database**, and **NetBeans Project Architecture**.  
This system automates the management of books, borrowers, librarians, loan transactions, and more — implemented using clean Java code and proper OOP structure.

---

## 🚀 Core Features
- Book Management (add/update/delete/search)
- Member & Staff Management
- Loan & Return Handling
- Hold Requests (FIFO queue)
- Full OOP Design: Inheritance, Polymorphism, Abstraction, Encapsulation
- Derby Embedded Database (no external DB setup)
- Clean project structure with reusable classes

---

## 🏛 Project Architecture
```
Project/
├── src/LMS/
│   ├── Book.java
│   ├── Borrower.java
│   ├── Clerk.java
│   ├── HoldRequest.java
│   ├── Librarian.java
│   ├── Library.java
│   ├── Loan.java
│   ├── Main.java
│   ├── Person.java
│   ├── Staff.java
│
├── Database/        # Derby DB files
├── images/          # Screenshots and diagrams
└── README.md
```

---

## 🖼 Screenshots (replace paths after upload)

### 📌 Class Diagram  
`images/diagram.PNG`

### 📌 Interface Screens  
- `images/interface.PNG`  
- `images/interface2.PNG`

### 📌 Procedural Steps  
- `images/step1.PNG`  
- `images/step2.PNG`  
- `images/step3.PNG`

### 📌 Final Output  
- `images/final.png`

---

## ⚙ How to Run

### **1️⃣ Import Project**
- Open **NetBeans**
- Click **File → Open Project**
- Select your downloaded folder

### **2️⃣ Run the Application**
- Open `Main.java`
- Press **Shift + F6**

### **3️⃣ Database Setup**
- No setup required  
- Derby DB loads automatically from the *Database* folder

---

## 🧠 OOP Concepts Used
- **Inheritance:** `Person → Staff → Clerk/Librarian`, `Person → Borrower`
- **Encapsulation:** Private attributes + getters/setters
- **Polymorphism:** Overridden methods in subclasses
- **Abstraction:** Parent classes (`Person`, `Library`)

---

## 📦 Technologies Used
- Java (JDK 8+)
- Derby Embedded Database
- NetBeans IDE

---

## 🌟 Future Enhancements
- GUI using Swing/JavaFX
- Admin dashboard
- Fine calculation system
- Automated reminders via email/SMS

---

## 👨‍💻 Authors
- **Deepanshu Chauhan**  
- **Abhay Upadhyay**  
- **Sumit Singh**

---

## ⭐ Support
If you like this project, please ⭐ star the repository!

