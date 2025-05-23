# 🏸 Smash Lab Database

Welcome to **Smash Lab**, a relational database system designed to modernize and streamline the operations of a cozy badminton restringing shop.

## 📌 Overview

Smash Lab houses all the core objects necessary to accurately identify stakeholders involved in racket stringing jobs, including:

- **Customers** placing stringing orders
- **Staff** fulfilling the jobs
- **Strings** used in the process
- **Orders** placed by the customers
-  **Stringing jobs** to be fulfilled by the staff

This database system also supports additional information that helps automate and facilitate the transaction process — with the goal of improving customer satisfaction and overall operability for shop owners.

## 🗂️ Project Structure

- **ER Diagram**: Visualizes all entities and relationships.
- **SQLite Schema**: SQL code to define tables, constraints, and indexes.
- **Sample Data**: Preloaded entries for customers, staff, strings, and jobs.
- **Indexes**: Optimize queries based on job status, order status, and locker usage.

## 📊 Core Entities

| Entity        | Description                                             |
|---------------|---------------------------------------------------------|
| `customers`   | Stores customer details like name, contact, and signup date. |
| `staff`       | Details of employees performing the stringing jobs.     |
| `strings`     | Catalog of available string types and specifications.   |
| `orders`      | Represents high-level orders containing one or more string jobs. |
| `string_job`  | Individual racket stringing jobs, each tied to an order. |

## ✅ Key Features

- Enforced constraints for data integrity (e.g., valid tension ranges, enum-like checks)
- Default values for job statuses
- Efficient search via indexes (e.g., job status, collection status)
- Designed to reflect real-world flow: from drop-off to collection

## 🛠 Tech Stack

- **Database**: SQLite
- **Tools**: DB Browser for SQLite, VS Code Terminal
