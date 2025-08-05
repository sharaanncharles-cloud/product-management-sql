
# product-management-sql
A beginner SQL project based on Agile &amp; Scrum. Work in progress. 


# 🧠 AI Tools - Product Management SQL

A beginner SQL project based on Agile & Scrum. This project simulates the database side of a product management platform using MySQL. It allows tracking of products, customers, teams, features, sprints, releases, issues, and tasks—tailored for AI-driven product decision-making and agile collaboration.

---

## 📁 Project Structure


---


## 🧩 Database Design

📌 Main Entities:

| Entity                | Description                                        |
| --------------------- | -------------------------------------------------- |
| **products**          | Stores product info (name, price, release status)  |
| **releases**          | Tracks product version releases with dates         |
| **customers**         | Holds customer details                             |
| **orders**            | Customer orders with order date                    |
| **order\_items**      | Product quantity per order                         |
| **product\_managers** | Product owners with department info                |
| **features**          | Product features and development status            |
| **sprints**           | Sprint details (name, duration)                    |
| **sprint\_features**  | Maps features to sprints (many-to-many)            |
| **tasks**             | Work items assigned to sprints and employees       |
| **issues**            | Bug or issue tracking with severity and resolution |

---

## 💡 Features

- 📦 Product Tracking: Manage product releases, versions, and pricing.
- 👥 Team Performance: Track tasks per employee and analyze performance.
- 🧩 Sprints & Features: Link sprints with features and track progress.
- 📈 Reporting: Predefined SQL queries for insights (e.g., top customers, task backlog).
- 🧑‍💻 Issue Tracking: Manage and resolve bugs with severity & resolution time.
- 💬 Customer Orders: Analyze customer activity and product orders.

---

## 🛠️ Technologies Used

- **MySQL**
- SQL (DDL + DML + complex queries)
- Git + GitHub

---


🔗 ER Diagram (Visual)

This diagram represents all key tables and their relationships—like customers placing orders, product managers managing features, and tasks linked to sprints.


<img width="1024" height="1024" alt="Diagrama de Relación de Entidades" src="https://github.com/user-attachments/assets/083ce3fb-3d16-4ef5-866d-fd553425dfa6" />


---


## 🚀 Getting Started

1. Clone this repo:
   ```bash
   git clone https://github.com/sharaanncharles-cloud/product-management-sql.git
