# 🍽️ FoodIQ

**FoodIQ** is an intelligent food industry management system that streamlines the handling of customers, inventory, and orders. With built-in authentication, role-based access control, and MySQL integration, FoodIQ is designed to help restaurant or store managers operate efficiently and securely. Powered by **Spring Boot** and **Thymeleaf**, it offers a responsive and intuitive interface for admins and staff.

---

## 📸 Screenshots

> *(Add actual images or markdown links when pushing to GitHub)*

* Dashboard View
* Manage Customers
* Track Inventory
* Process Orders
* Admin Login & Permissions

---

## ✨ Features

* 👥 **Customer Management**
  Add, view, update, or remove customer details quickly.

* 📦 **Inventory Control**
  Keep an accurate log of stock, prices, and availability.

* 🛒 **Order Management**
  Create, update, and track customer orders with ease.

* 🔐 **Secure Login System**
  Authentication for both admin and staff members.

* 🛡️ **Role-Based Access Control**
  Permissions based on user roles (Admin / Staff).

* 🧩 **Thymeleaf Integration**
  Dynamic and modern HTML templates.

* 🗃️ **MySQL Database Integration**
  Persistent, scalable data handling with Hibernate.

---

## 🛠️ Technology Stack

* **Backend:** Spring Boot, Java 8, Spring MVC, Spring Data JPA (Hibernate)
* **Frontend:** Thymeleaf, HTML, CSS, JavaScript
* **Database:** MySQL
* **IDE:** Eclipse or Spring Tool Suite (STS)

---

## ✅ Prerequisites

Make sure the following are installed:

* Java 8
* MySQL
* Maven
* Eclipse or Spring Tool Suite (STS)

---

## 🚀 Setup Instructions

1. **Clone the repository:**

```bash
git clone https://github.com/Pavan143Kundeti/FoodApp_SpringBoot
```

2. **Navigate to the project directory:**

```bash
cd FoodIQ
```

3. **Configure the MySQL Database:**

* Create a new database named `foodiq`.
* Update `application.properties` with your credentials:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/foodiq
spring.datasource.username=root
spring.datasource.password=root
spring.jpa.hibernate.ddl-auto=update
```

4. **Run the application:**

```bash
mvn spring-boot:run
```

5. **Access it in your browser:**

```
http://localhost:8080
```

---

## 🗂️ Project Structure

```
src/
├── main/
│   ├── java/
│   │   └── com.example.foodiq/
│   │       ├── controller/      # Handles HTTP requests
│   │       ├── model/           # Entity classes
│   │       ├── repository/      # JPA repositories
│   │       └── service/         # Business logic
│   ├── resources/
│   │   ├── templates/           # Thymeleaf HTML views
│   │   ├── static/              # CSS/JS files
│   │   └── application.properties  # Configurations
│   └── webapp/
│       └── WEB-INF/
│           └── views/           # Additional views (if used)
└── test/                        # Unit/integration tests
```

---

## 📬 Contributing

Contributions and suggestions are welcome! Fork the repository, make your changes, and submit a pull request.


