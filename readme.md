# Worker Contract Management

Simple Java project created to practice **composition**, **enumerations (enum)**, and basic **Object-Oriented Programming** principles.

## 🔷 UML Diagram

<img width="1727" height="859" alt="image" src="https://github.com/user-attachments/assets/51bdee18-2dc4-4377-84e7-949613337159" />



## 📁 Project Structure

    src/
     ├── application/
     │    └── Program.java
     ├── entities/
     │    ├── Worker.java
     │    ├── Department.java
     │    └── HourContract.java
     └── entities/enums/
          └── WorkerLevel.java

---

## 🧱 Features

- Department registration  
- Worker creation with level (enum)  
- Association of multiple hourly contracts  
- Monthly income calculation (base salary + contracts for the given month)  
- Data input via standard console (Scanner)

---

## ▶️ How to Run

Compile and run the program using the terminal:

`javac application/Program.java`  

Or simply run it through IntelliJ IDEA or any Java IDE.

---

## 🧪 Example Usage

The program asks for:

- Department name  
- Worker data (name, level, base salary)  
- Number of contracts  
- Contract date, value per hour, and duration  
- Month and year to calculate income  

And then displays:

- Worker name  
- Department  
- Income for the selected month  

---

## 🛠 Technologies

- **Java 17+**  
- **IntelliJ IDEA**

---
