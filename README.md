<p align="center">
  <img src="Bluewave Luxury Resort.jpg" width="600">
</p>

# Project: BlueWave Luxury Resort Database

## 1. Introduction

This project is focused on designing a relational database for a luxury hospitality organization named **BlueWave Luxury Resort**.  
The database is created to support the day-to-day operational activities of the resort such as managing guests, room bookings, staff details, payments, and additional services like spa and laundry.

The design is kept simple, structured, and aligned with real-world resort operations.

---

## 2. Objective of the System

The primary objectives of this database system are to:

- Store and manage guest information in a centralized manner  
- Handle room categorization and room availability  
- Process and manage bookings efficiently  
- Maintain payment records associated with bookings  
- Manage staff and departmental details  
- Track additional services availed by guests  

This database enables smooth coordination between different functional areas of the resort.

---

## 3. Scope of the Database

The scope of the database includes the following operational areas:

- Guest registration and personal information  
- Room and room-type management  
- Booking and reservation handling  
- Payment processing and status tracking  
- Staff and department management  
- Additional service management such as spa or laundry  

The system is designed to minimize redundancy and ensure data consistency.

---

## 4. Entities and Their Descriptions

### 1. Guest
Stores information related to resort guests such as name, phone number, email, and city.

### 2. Room_Type
Contains details about room categories including type name, base price, and maximum occupancy.

### 3. Room
Stores individual room details like room number, floor, status, and room type.

### 4. Booking
Records reservation details including check-in date, check-out date, number of guests, and booking status.

### 5. Payment
Stores payment information related to bookings such as amount, payment date, method, and payment status.

### 6. Department
Maintains information about various departments within the resort.

### 7. Staff
Stores staff details including role, contact information, department association, and employment status.

### 8. Service
Contains information about additional services offered by the resort, such as spa or laundry.

### 9. Service_Booking
Records services availed by guests during their stay along with quantity and total amount.

---

## 5. Database Design Logic

- The database is designed using a relational model  
- Each table has a primary key for unique identification  
- Foreign keys are used to establish relationships between tables  
- Data redundancy is reduced using normalization principles  
- The structure reflects the real-world workflow of a luxury resort  

The design ensures data integrity and efficient data retrieval.

---

## 6. Assumptions

- A guest can make multiple bookings  
- Each booking is linked to one guest and one room  
- A room belongs to only one room type  
- A booking can have multiple payment records  
- A guest can avail multiple services during a stay  
- Each staff member belongs to one department  

---

## 7. Conclusion

This database design provides a structured and efficient solution for managing the core operations of **BlueWave Luxury Resort**.  
It integrates guest management, bookings, staff administration, payments, and services into a unified system, making it suitable for academic learning as well as real-world understanding of hospitality database systems.

