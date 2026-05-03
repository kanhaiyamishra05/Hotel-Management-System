# 🏨 Hotel Management System (Console-Based Java Application)

A comprehensive **Hotel Management System** developed in **Java** using object-oriented programming principles. This console-based application automates essential hotel operations such as room booking, food ordering, billing, checkout, and room availability management.

It is designed to demonstrate practical implementation of core Java concepts including **OOP, inheritance, exception handling, file handling, serialization, multithreading, and collections**.

---

## ✨ Features

* 🛏️ Room booking and reservation
* 👤 Customer check-in and check-out
* 🍽️ Food ordering system
* 💳 Automatic bill generation
* 📋 Real-time room availability tracking
* 💾 Persistent data storage using file serialization
* ⚡ Multithreaded backup system
* 🔒 Exception handling for robust operation

---

## 🏢 Room Types Available

1. **Luxury Double Room** – ₹4000/day
2. **Deluxe Double Room** – ₹3000/day
3. **Luxury Single Room** – ₹2200/day
4. **Deluxe Single Room** – ₹1200/day

---

## 🍴 Food Menu

| Item     | Price |
| -------- | ----- |
| Sandwich | ₹50   |
| Pasta    | ₹60   |
| Noodles  | ₹70   |
| Coke     | ₹30   |

---

## 🛠️ Technologies Used

* **Java**
* **Object-Oriented Programming (OOP)**
* **Collections Framework (ArrayList)**
* **File Handling**
* **Serialization**
* **Multithreading**
* **Exception Handling**

---

## 📂 Project Structure

```text
Main.java
├── Food
├── Singleroom
├── Doubleroom
├── NotAvailable
├── holder
├── Hotel
└── write
```

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/Hotel-Management-System.git
```

2. Navigate to the project directory:

```bash
cd Hotel-Management-System
```

3. Compile the program:

```bash
javac Main.java
```

4. Run the application:

```bash
java Main
```

---

## 📌 Main Functionalities

* Display room details
* Check room availability
* Book rooms
* Order food for booked rooms
* Generate bill during checkout
* Save hotel data automatically on exit

---

## 💾 Data Persistence

The application automatically saves hotel records into a backup file using Java serialization. When restarted, it restores previous booking data.

---

## 🎯 Learning Outcomes

This project demonstrates:

* Real-world use of Java OOP concepts
* File serialization and deserialization
* Thread-based background data saving
* Menu-driven console application design
* Exception handling and custom exceptions

---

## 📷 Sample Console Output

```text
Enter your choice:
1. Display room details
2. Display room availability
3. Book
4. Order food
5. Checkout
6. Exit
```

---

## 👨‍💻 Author

**Kanhaiya Kumar**

---

## 📜 License

This project is open-source and available under the MIT License.
