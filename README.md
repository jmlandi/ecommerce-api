# 🛍️ E-commerce CRUD with Spring Boot

Welcome to the **E-commerce CRUD** project! This application is a portfolio project built with **Spring Boot**, **PostgreSQL**, and **Docker**, focusing on creating a robust backend system for managing an e-commerce platform.

---

## 🚀 Project Overview
This project implements a backend for an e-commerce application, featuring:

- **📦 Product Management**: Handle parent and child products with attributes like size, color, price, images and stock.
- **🛒 Order System**: Manage orders and associated items.
- **👤 User Profiles**: Store user data, including personal information.
- **🚚 Address System**: Manage user addresses for diferent orders.
- **🔒 Relationships**: Ensure proper data linkage between tables for consistency and efficiency.

---

## 🛠️ Tech Stack

### **Backend**
- [Spring Boot](https://spring.io/projects/spring-boot): Framework for building Java applications.
- [PostgreSQL](https://www.postgresql.org/): Relational database.
- [Spring Data JPA](https://spring.io/projects/spring-data-jpa): ORM for database interactions.

### **Infrastructure**
- [Docker](https://www.docker.com/): Containerization for database setup.

---

## 📋 Features

### 🏷️ **Products**
- Create and manage parent products with shared attributes.
- Create child products with variations (e.g., size, color, price).

### 🛍️ **Orders**
- Create and track user orders.
- Add multiple items to each order.
- Add any address registered for the user.

### 👤 **Users**
- Manage user profiles with essential details like name, email, and document number.
- Manage multiple addresses.

---

## 📂 Database Schema
The application follows a relational database structure:

1. **Brands**
2. **Categories**
3. **Parent Products**
4. **Product Images**
5. **Child Products**
6. **Users**
7. **User Addresses**
8. **Orders**
9. **Order Items**

![E-commerce API](https://github.com/user-attachments/assets/a7d139cf-f83b-470f-8a7f-ded409c41ffb)
[Check it out on the dbdiagram.io](https://dbdiagram.io/d/E-commerce-API-6758bacce9daa85aca4e888e).

---

## 🚀 Getting Started

### Prerequisites
- Java 17+
- Docker
- PostgreSQL
- Maven

### Running the Application

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/ecommerce-crud.git
   cd ecommerce-crud
   ```

2. **Start the Database**:
   ```bash
   docker run --name ecommerce-db -e POSTGRES_USER=admin -e POSTGRES_PASSWORD=admin -e POSTGRES_DB=ecommerce -p 5432:5432 -d postgres
   ```

3. **Run the Application**:
   ```bash
   ./mvnw spring-boot:run
   ```

4. Access the application at `http://localhost:8080`.

---

## 📖 Future Enhancements

- Add user authentication and authorization.
- Implement a frontend interface.
- Add more advanced product filtering and searching.
- Introduce payment gateway integration.

---

## 🤝 Contributing

Feel free to fork the repository, make improvements, and submit pull requests. All contributions are welcome!

---

## 💬 Contact

For any questions or suggestions, reach out at [joaomarcospsnbr@gmail.com](mailto:joaomarcospsnbr@gmail.com).

## May the Java be with you! 🍵✨

<img src="https://i.giphy.com/Dmydf2Zf2kOys.webp" style="width: 100%;">

