# 🏩 College Infrastructure Management System

## 📌 Overview
The **College Infrastructure Management System** is a **DBMS-based project** designed to help **students and teachers** efficiently find and book classrooms and halls as per their needs. It provides a **complete list of available rooms** along with details about their **facilities, capacity, and availability status**.  

This system ensures a **hassle-free experience** by streamlining the booking process, reducing scheduling conflicts, and optimizing space utilization within the college.

---

## 🚀 Features
### ✅ Room & Hall Booking
- Users can **search for available rooms** and **book them** based on time slots.
- Provides a **real-time availability status** to avoid double booking.

### 📌 Comprehensive Classroom Directory
- Displays a **detailed list of all rooms** present in the college.
- Includes information like **room capacity, facilities (projector, AC, whiteboard, etc.), and availability**.

### 🔍 Advanced Search & Filters
- Users can **filter rooms based on various criteria**:
  - **Capacity** (e.g., Small, Medium, Large)
  - **Facilities** (e.g., AC, Projector, Smart Board)
  - **Availability** (e.g., Currently Free, Reserved)
  
### 👥 Role-Based Access Control
- **Students**: Can search and book available rooms.  
- **Teachers**: Can **approve/cancel** student bookings and create reservations for **lectures or events**.

### 📅 Booking History & Notifications
- Users can view their **past and upcoming bookings**.  
- Notifications are sent when **a booking is confirmed, modified, or canceled**.

### 🏩 College-Wide Resource Optimization
- Ensures **efficient utilization** of available classrooms and halls.
- Helps in **reducing scheduling conflicts**.

---

## 🛠 Tech Stack
| **Technology** | **Description** |
|---------------|----------------|
| **Database** | MySQL |
| **Backend** | Node.js (Express) / Flask / |
| **Frontend** | React.js / HTML-CSS-JS  |

---

## 🚀 Installation & Setup
### 🔹 Clone the Repository
```bash
git clone <repo-link>
cd college-infrastructure
```

### 🔹 Install Dependencies
For **Node.js Backend**:
```bash
npm install
```
For **Python Backend**:
```bash
pip install -r requirements.txt
```

### 🔹 Set Up the Database
1. **Create a database** in MySQL/PostgreSQL.
2. Run the provided SQL script to set up tables.
   ```bash
   mysql -u username -p database_name < schema.sql
   ```
3. Update the **database configuration** in the `.env` file.

### 🔹 Start the Server
For **Node.js (Express.js)**:
```bash
npm start
```
For **Flask/Django**:
```bash
python app.py  # or python manage.py runserver
```

### 🔹 Access the Application
Once the server is running, open your browser and go to:
```
http://localhost:3000  # Adjust port if necessary
```

---

## 🔮 Future Enhancements
- **📊 Admin Dashboard** for **better room management** & analytics.
- **📅 Calendar View** for **easier booking visualization**.
- **🔔 Email & SMS Notifications** for confirmed bookings.
- **📱 Mobile App Integration** for easier access.

---
## 👥 Co-Authors
Thanks to the following people for their contributions:

- [@neha-shetty-17](https://github.com/neha-shetty-17)
- [@nehashaju1907](https://github.com/nehashaju1907)

---
## Author

Meiha
