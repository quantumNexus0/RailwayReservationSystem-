
---

# 🚆 Railway Reservation System  

A GUI-based desktop application for managing railway reservations with features like **Reservation** and **Add Train**. Built using **Java (JFrame)** and **MySQL**, this project provides a seamless experience for both passengers and administrators.  

---

## 📌 Features  

### User Features  
- **Train Reservation**: Book train tickets with ease.  
- **Cancel Booking**: Modify or cancel reservations effortlessly.  

### Admin Features  
- **Add Train**: Manage train schedules, routes, and details.  
- **Database Management**: Reliable and secure storage using MySQL.  

### General Features  
- **User-Friendly Interface**: A desktop application built with an intuitive Java Swing GUI.  
- **Efficient Operations**: Quick processing and database interactions via JDBC.  

---

## 🛠️ Technology Stack  

- **Frontend**: Java (JFrame)  
- **Development IDE**: NetBeans  
- **Database**: MySQL, managed with XAMPP  
- **Connectivity**: JDBC (Java Database Connectivity)  

---

## 🚀 Getting Started  

### Prerequisites  
1. Install **NetBeans IDE**.  
2. Set up **XAMPP** and start the MySQL service.  

### Installation  

1. Clone the repository:  
   ```bash  
   git clone https://github.com/your-username/railway-reservation-system.git  
   ```  

2. Open the project in NetBeans.  

3. Import the database:  
   - Open phpMyAdmin from XAMPP.  
   - Create a new database (e.g., `railway_db`).  
   - Import the provided SQL file (`railway_db.sql`) into the new database.  

4. Update the database connection settings in the project’s source code:  
   ```java  
   String url = "jdbc:mysql://localhost:3306/railway_db";
   String user = "root";
   String password = "your_password";
   ```  

5. Run the project in NetBeans.  

---

## 📸 Screenshots 

### Login page
![Login page](src/Login.png)

### Main Page
![Main page](src/Main.png)

### Reservation Page  
![Reservation Page ](src/Reservation.png)

### Add Train Page  
 ![Add Train Page](src/AddTrain.png)

---

## 🤝 Contributing  

Contributions are welcome!  

1. Fork the repository.  
2. Create a new branch:  
   ```bash  
   git checkout -b feature-name  
   ```  
3. Commit your changes:  
   ```bash  
   git commit -m "Add feature description"  
   ```  
4. Push to the branch:  
   ```bash  
   git push origin feature-name  
   ```  
5. Submit a pull request.  

---

## 📝 License  

This project is licensed under the **MIT License**.  

---
