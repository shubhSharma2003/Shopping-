# 🛒 E-Commerce Platform

A **Spring Boot–based e-commerce application** that provides basic product management features using REST APIs. This project demonstrates a layered architecture with controllers, services, repositories, and models.

---

## 🚀 Features

* Add, view, and manage products
* RESTful API endpoints for CRUD operations
* Spring Data JPA integration with database
* Preloaded sample data via `data1.sql`
* Lightweight configuration with `application.properties`

---

## 🏗️ Tech Stack

* **Backend:** Java 17, Spring Boot
* **Database:** H2 / MySQL (configurable)
* **Build Tool:** Maven
* **Testing:** JUnit

---

## 📂 Project Structure

```
ecom-proj-master/
 ┣ src/main/java/com/telusko/ecom_proj/
 ┃ ┣ controller/   # REST controllers (e.g., ProductController)
 ┃ ┣ model/        # Entity classes (e.g., Product.java)
 ┃ ┣ repo/         # Spring Data JPA repositories
 ┃ ┣ service/      # Business logic services
 ┃ ┗ EcomProjApplication.java # Main entry point
 ┣ src/main/resources/
 ┃ ┣ application.properties   # App configuration
 ┃ ┣ data1.sql                # Sample data
 ┣ pom.xml                     # Maven dependencies
```

---

## ⚙️ Setup & Run

### Prerequisites

* Install [Java 17+](https://adoptium.net/)
* Install [Maven](https://maven.apache.org/)

### Steps

1. Clone the repository

   ```bash
   git clone https://github.com/your-username/Shopping-.git
   cd Shopping-
   ```
2. Build the project

   ```bash
   mvn clean install
   ```
3. Run the application

   ```bash
   mvn spring-boot:run
   ```
4. Access the API at:

   ```
   http://localhost:8080/products
   ```

---

## 📌 API Endpoints

| Method | Endpoint         | Description                |
| ------ | ---------------- | -------------------------- |
| GET    | `/products`      | Get all products           |
| GET    | `/products/{id}` | Get product by ID          |
| POST   | `/products`      | Add a new product          |
| PUT    | `/products/{id}` | Update an existing product |
| DELETE | `/products/{id}` | Delete product by ID       |

---

## 🧪 Testing

Run tests using:

```bash
mvn test
```

---

## 🤝 Contributing

Contributions are welcome! Feel free to open issues and submit pull requests.

---

## 📜 License

This project is licensed under the MIT License.


