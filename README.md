
## 🛒 E-Commerce Platform (Spring Boot – Backend Practice)

Hi, I’m Ashish Kumar Pandey.
This repository is part of my learning journey in Spring Boot backend development. I have built this project to understand how a real e-commerce backend works step by step — starting 
from controllers, service layer, REST APIs, and Postman testing.

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

---

## 🧠 Concepts I Learned

* Spring Boot project structure
* @RestController, @Service annotations
* Request mapping (GET, POST, PUT, DELETE)
* How JSON is mapped to Java objects (Jackson serialization)
* Service layer responsibility
* Basic error handling
* How backend APIs work before connecting to DB

---

## 🛠 Tech Stack

* Java
* Spring Boot
* REST API
* Postman (API Testing)

---

## 🚀 Next Plan

I will continue this project by adding:

1. Database integration (MySQL + JPA + Hibernate)
2. Repository layer
3. Validation & exception handling
4. Proper DTO structure
5. Frontend connection later


## 💡 Purpose of This Repo

This is a **learning repository**, not a production project.
My goal is to:

* Understand backend deeply
* Build confidence in Spring Boot
* Relate theory (System Design, DBMS, Networking) with real implementation

---

### 🙏 Thank You



If you want, I can also help you:

* Add **API screenshots section**
* Add **project structure diagram**
* Convert this into more “resume-friendly” version later 🔥
