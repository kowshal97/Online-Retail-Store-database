# Online Retail Store – Database

![Status](https://img.shields.io/badge/Project-Completed-brightgreen)
![Database](https://img.shields.io/badge/Database-PostgreSQL-blue)
![Modeling](https://img.shields.io/badge/ERD-Logical%20%7C%20Physical-purple)

Database design project for an **Online Retail Store**.  
Includes **business definition, ER modeling, normalization, SQL implementation, and validation**.

---

## 📂 Deliverable
- [📥 Download Presentation (PPTX)](https://github.com/kowshal97/Online-Retail-Store-database/raw/main/OnlineRetailStore.pptx)

---

## 📌 Overview
This project demonstrates **logical and physical database design** for an online retail system.

### 🔹 Project Scope
- **Business Definition Table**
- **Entities & Attributes**
- **Normalization** applied to database design
- **Relationships (cardinality examples)**
  - Customers → Orders (1:N)
  - Orders → Order Items (1:N)
  - Order Items → Products (N:1)
  - Products → Inventory (1:1)
  - Products → Reviews (1:N)
  - Customers → Reviews (1:N)
- **ERD Models** (Conceptual/Logical/Physical)
- **SQL Implementation**: table creation & data inserts
- **Validation**: query execution and results

---

## 🛠️ Tech Stack
- **PostgreSQL** (RDS / pgAdmin)
- **ERD modeling** (draw.io / diagrams.net)
- **SQL** (DDL & DML)

---

## 📸 Screenshots
*(Images live in `/diagrams` — click to view full size.)*

- **ERD**  
  [![ERD](./diagrams/ERD%20model%20-%20online.png)](./diagrams/ERD%20model%20-%20online.png)

- **Logical Model**  
  [![Logical Model](./diagrams/Logical%20model%20-%20online.png)](./diagrams/Logical%20model%20-%20online.png)

- **Create Table Queries**  
  [![Create Tables](./diagrams/create%20table%20queries_online.png)](./diagrams/create%20table%20queries_online.png)

- **Insert Data – Queries**  
  [![Insert Data Queries](./diagrams/inserting%20data%20queries_online.png)](./diagrams/inserting%20data%20queries_online.png)

- **Insert Data – Execution**  
  [![Insert Data Execution](./diagrams/inserting%20data%20execution.png)](./diagrams/inserting%20data%20execution.png)

- **Table View / Execution**  
  [![Table Execution](./diagrams/online%20table%20execution.png)](./diagrams/online%20table%20execution.png)

- **Join Queries**  
  [![Join Queries](./diagrams/Joint%20queries-online.png)](./diagrams/Joint%20queries-online.png)

---

## 🔗 Quick Links
- Diagrams folder: [`/diagrams`](./diagrams/)

