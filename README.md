# FMZtronic - Electronic Store Database System 📱💻

## 📌 Project Overview
**FMZtronic** is a database system designed for managing an online electronics store. It handles products (phones, laptops, accessories), customer data, order processing, and delivery tracking.

## 🚀 Key Features
- **User Specialization:** Uses Enhanced Entity-Relationship (EER) to distinguish between **Customers** and **Delivery Agents** through a shared `Person` supertype.
- **Order Management:** Tracks order status, payment methods, and generates bill serial numbers.
- **Product Tracking:** Manages electronics by category, description, and price.
- **Discount System:** Integrated Coupon system linked to customers with validity dates.

---

## 📊 Database Design Phases

### 1️⃣ Conceptual Design (EER Diagram)
In this phase, I designed the EER diagram to handle the shared attributes between customers and delivery agents efficiently.
![EER Diagram](https://github.com/user-attachments/assets/d82e8c6b-4625-4173-aa84-1cb0e846ea2f)

### 2️⃣ Logical Design (Relational Mapping)
The transformation of the EER model into a relational schema, ensuring data integrity and proper foreign key relationships.
![Mapping](https://github.com/user-attachments/assets/d3370c96-b898-423f-8438-78ff0008345b)

### 3️⃣ Physical Design (MySQL Workbench)
The final implementation in MySQL Workbench, ready for SQL script generation and database creation.
![MySQL Workbench](https://github.com/user-attachments/assets/2f5a29ce-12de-468f-bd3b-52e02891226e)

---

## 🛠️ Tech Stack
- **Database:** MySQL
- **Modeling Tool:** MySQL Workbench
- **Language:** SQL

**Created by: [Mennatullah Mahmoud]**
