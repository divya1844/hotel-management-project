# 🏨 Hotel Management System – Java OOP Project

A console-based **Hotel Management System** implemented using **Object-Oriented Programming (OOP)** in Java.  
This project simulates real hotel operations — room booking, food ordering, checkout, billing, and maintaining records — while demonstrating key concepts like inheritance, polymorphism, exception handling, file I/O, and multithreading.

---

## 🚀 Features

### 🛏 Room Booking
- Supports four room types:
  - Luxury Double Room
  - Deluxe Double Room
  - Luxury Single Room
  - Deluxe Single Room
- Tracks available vs. occupied rooms
- Custom `NotAvailable` exception prevents double-booking

### 🍽 Food Ordering
- Order food for any booked room
- Menu with multiple categories
- Stores all ordered items with prices

### 🧾 Billing System
- Generates final bill including:
  - Room cost
  - Food charges
  - Additional services
- Supports checkout and room unbooking

### 📂 Data Persistence (Save/Load)
- Saves hotel state using **serialization**
- Automatically loads previous saved data at program startup
- Prevents data loss between runs

### 🧵 Multithreading
- Uses a separate thread to log activity to a file
- Demonstrates concurrency and file handling

### 🛑 Exception Handling
- Handles invalid input and indices
- Custom exceptions for booking and availability

---

## 🏛 Object-Oriented Design

### ✔ Inheritance  
Shared behaviors for room types via parent-child class structure.

### ✔ Polymorphism  
Flexible handling of different room and food operations.

### ✔ Encapsulation  
Private fields with getters/setters for clean module separation.

### ✔ Interfaces  
Used to manage room and service charge behavior.

---

## 📁 Project Structure

├── Main.java
├── Hotel.java
├── Singleroom.java
├── Doubleroom.java
├── Food.java
├── Customer.java
├── NotAvailable.java
├── write.java
└── README.md


---

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/yourusername/hotel-management-system.git
cd hotel-management-system

javac Main.java

java Main

1. Check Room Availability
2. Book a Room
3. Order Food
4. Checkout & Generate Bill
5. Exit


| Concept             | Used In                            
| ------------------- | ---------------------------------- 
| Classes & Objects   | Room and customer models           
| Inheritance         | Room type hierarchy                
| Polymorphism        | Bill generation, ordering          
| Interfaces          | Charges calculations               
| Exception Handling  | Input validation                   
| Custom Exceptions   | Room availability (`NotAvailable`) 
| Serialization       | Saving/loading hotel state         
| Multithreading      | Logging thread                     
| Arrays & ArrayLists | Room storage and orders            

