
## 🛒 E-Commerce Platform (Spring Boot – Backend Practice)

Author: Ashish Kumar Pandey

This project is a Spring Boot backend implementation of an e-commerce category management module. 
It follows a layered architecture and exposes RESTful APIs with proper separation of public and admin endpoints. 
All APIs are tested using Postman.

<img width="632" height="907" alt="image" src="https://github.com/user-attachments/assets/6ce4cb41-b520-4a46-8d9a-2f3eafb02300" />

This project focus on:
* Client → Server communication
* REST API design
* Layered architecture (Controller → Service → Model)
* CRUD operations using in-memory storage
* Understanding how Spring Boot handles requests and responses

---

## 📌 What I Have Implemented

### ✅ Category Module (In-Memory)

* Create Category → **POST /api/admin/categories**
* Get All Categories → **GET /api/public/categories**
* Update Category → **PUT /api/admin/categories/{id}**
* Delete Category → **DELETE /api/admin/categories/{id}**

Access Policy:
- Public: GET endpoints only
- Admin: POST, PUT, DELETE operations under /api/admin


All APIs are tested using **Postman**.

<img width="1448" height="872" alt="image" src="https://github.com/user-attachments/assets/5c878547-18f8-4dcb-973d-7b56c32d9745" />


## 🧱 Architecture Used

Layered Architecture:
Controller → Service → Repository → Model

Responsibilities:

Controller handles HTTP requests

Service contains business logic

Repository manages data operations

Model represents domain entities

JSON ↔ Java mapping using Jackson

Unique ID management for entities

Structured REST responses

End-to-end API testing with Postman



---

## 🛠 Tech Stack

Java

Spring Boot

REST APIs

Lombok

Postman for API Testing

---

## 📂 Project Structure

controller/ – REST endpoints

service/ – business logic

repositories/ – data handling layer

model/ – entity classes


## 🎯 Outcome

Successfully built working backend APIs for category management

Implemented proper separation of public and admin routes

Validated complete request flow using Postman

Followed industry-standard layered design


---

### 🙏 Thank You

