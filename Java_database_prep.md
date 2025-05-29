# Java + Database Interview Preparation (3 YOE)

A complete reference guide for Java developers (3 years experience) focusing on database concepts, integration, tools, and interview questions.

---

## 🧱 1. Core Database Concepts

### 📖 Explanation

Relational databases store data in structured formats using tables. Key concepts:

* **Normalization**: 1NF, 2NF, 3NF
* **Joins**: `INNER`, `LEFT`, `RIGHT`, `FULL`
* **Constraints**: Primary key, foreign key, unique
* **Transactions**: ACID properties
* **Views & Indexes**: Logical representation & performance enhancement

### ❓ Interview Questions

* What is normalization? Explain 1NF, 2NF, 3NF.
* What are ACID properties?
* Difference between different types of JOINs?
* How do indexes impact performance?

---

## 🔌 2. JDBC (Java Database Connectivity)

### 📖 Explanation

Standard Java API for accessing databases.

* Core classes: `DriverManager`, `Connection`, `Statement`, `PreparedStatement`, `ResultSet`
* Use `PreparedStatement` for safe parameterized queries
* Connection pooling with HikariCP

### ❓ Interview Questions

* How to connect to a DB using JDBC?
* Why prefer `PreparedStatement` over `Statement`?
* What is connection pooling?

---

## 🛠️ 3. ORM with JPA & Hibernate

### 📖 Explanation

Maps Java objects to relational DB tables.

* Key annotations: `@Entity`, `@Table`, `@Id`, etc.
* Lazy vs Eager fetching
* JPQL vs Native SQL
* Entity life cycle

### ❓ Interview Questions

* What is the difference between `merge()` and `persist()`?
* What are fetching strategies?
* How do you solve N+1 problem?

---

## 🌱 4. Spring Data JPA

### 📖 Explanation

Abstraction over JPA for CRUD operations.

* Interfaces: `JpaRepository`, `CrudRepository`
* Query derivation and `@Query`
* Pagination and sorting

### ❓ Interview Questions

* How does Spring generate queries?
* What is `@Modifying`?

---

## 🧪 5. Database Design & Modeling

### 📖 Explanation

Designing schemas and modeling data.

* Relationships: 1:1, 1\:N, M\:N
* Choosing correct data types
* Surrogate vs Natural keys

### ❓ Interview Questions

* How to model a many-to-many relationship?
* Tradeoffs between normalization and denormalization?

---

## ⚙️ 6. Performance Tuning & Optimization

### 📖 Explanation

Improving performance via indexes and optimized queries.

* Avoid `SELECT *`
* Use `EXPLAIN` to analyze
* Index only necessary columns

### ❓ Interview Questions

* How to optimize a slow query?
* What are composite indexes?

---

## 🔄 7. Transaction Management

### 📖 Explanation

Managing atomic operations.

* Spring's `@Transactional`
* Isolation levels
* Deadlock prevention

### ❓ Interview Questions

* What is `@Transactional`?
* Explain isolation levels with examples.

---

## 🗃️ 8. NoSQL Basics

### 📖 Explanation

Non-relational data storage (MongoDB, Redis).

* Key-value, Document models
* Use cases: scalability, flexible schema

### ❓ Interview Questions

* When to use NoSQL over RDBMS?
* Differences between MongoDB and PostgreSQL?

---

## 🤕 9. Integration & Testing

### 📖 Explanation

* Use H2 in-memory DB
* `@DataJpaTest` for repository layer
* DB migration: Flyway or Liquibase

### ❓ Interview Questions

* What is `@DataJpaTest`?
* How do you run migrations?

---

## 🔧 10. Tools & Platforms

### 📖 Explanation

* SQL Clients: DBeaver, pgAdmin
* Migration Tools: Flyway, Liquibase
* Dockerize DBs for local testing

### ❓ Interview Questions

* What tools do you use for database management?
* How do you run PostgreSQL in Docker?

---

## 🐃 11. PostgreSQL-Specific Knowledge

### 📖 Explanation

PostgreSQL features and syntax.

* Data Types: `UUID`, `JSONB`, `ARRAY`
* Indexes: B-tree, GIN, GiST, BRIN
* Functions, CTEs, Window Functions
* Extensions: `uuid-ossp`, `pg_stat_statements`

### ❓ Interview Questions

* What is the difference between JSON and JSONB?
* When would you use GIN indexes?
* How does PostgreSQL implement MVCC?
* How do you write a stored procedure?

---

## ✅ Summary Checklist

| Topic               | Covered | Interview Ready |
| ------------------- | ------- | --------------- |
| Core SQL & Joins    | ✅       | ✅               |
| JDBC                | ✅       | ✅               |
| JPA & Hibernate     | ✅       | ✅               |
| Spring Data JPA     | ✅       | ✅               |
| Database Design     | ✅       | ✅               |
| Transactions        | ✅       | ✅               |
| Optimization        | ✅       | ✅               |
| PostgreSQL Features | ✅       | ✅               |
| Testing & H2 DB     | ✅       | ✅               |
| Flyway/Liquibase    | ✅       | ✅               |

---

> Next: Add example code (`.java`, `.sql`) and ER diagrams to the repository structure.
