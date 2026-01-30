# 🛒 E-Commerce Backend – Spring Boot

A **basic eCommerce backend application** built using **Spring Boot**.
This project demonstrates **CRUD operations**, **RESTful APIs**, and **layered architecture** for learning purposes.

---

## 📌 Project Overview

This backend application provides core functionality for a simple eCommerce system.
It allows managing products and customers through REST APIs and follows standard Spring Boot project structure.

---

## 🛠 Tech Stack

* **Java**
* **Spring Boot**
* **Spring Data JPA**
* **Hibernate**
* **MySQL / H2**
* **Maven**
* **Git**

---

## 🔗 API Endpoints

### Product APIs

```
GET    /api/products
POST   /api/products
GET    /api/products/{id}
PUT    /api/products/{id}
DELETE /api/products/{id}
```

### Customer APIs

```
GET    /api/customers
POST   /api/customers
GET    /api/customers/{id}
PUT    /api/customers/{id}
DELETE /api/customers/{id}
```

---

## 🗂 Project Structure

```
src/main/java
└── com.eCommerce
├── ECommerceApplication.java
│
├── controller
│ ├── CustomerController.java
│ ├── ProductController.java
│ ├── OrderController.java
│ └── OrderItemController.java
│
├── entity
│ ├── Customer.java
│ ├── Product.java
│ ├── Order.java
│ └── OrderItem.java
│
├── repository
│ ├── CustomerRepository.java
│ ├── ProductRepository.java
│ ├── OrderRepository.java
│ └── OrderItemRepository.java
│
└── service
│  ├── CustomerService.java
│  ├── ProductService.java
│  ├── OrderService.java
│  └── OrderItemService.java
src/main/resources
│  └── application.properties

---

## ⚙️ How to Run Locally

### Prerequisites
* Java 11 or Java 17
* Maven
* MySQL (optional if using H2)
* IDE (IntelliJ IDEA / Eclipse / VS Code)

---

### Steps

1. Clone the repository:
   ```bash
   git clone <your-github-repo-url>
   ```
2. Open the project in your IDE as a **Maven project**
3. Configure database details in `application.properties`
4. Run the **main Spring Boot application class**
5. Server starts at:
   ```
   http://localhost:8080
   ```

---

## 📚 Learning Purpose

This project is created for learning and practice to understand:
- Spring Boot basics
- RESTful API development
- CRUD operations
- Layered backend architecture

---

## 🚀 Project Status

* ✅ Basic backend implemented
* ✅ Product and Customer CRUD APIs
* 🚧 More features planned

---

## 👤 Author

Your Name
