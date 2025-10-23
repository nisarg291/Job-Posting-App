# 💼 Job Posting Application

A **Spring Boot RESTful API** for managing job postings — built with Java and Spring Boot.  
This backend service provides endpoints to **create, read, update, delete, and search** job posts, and is designed to integrate easily with a frontend (e.g., React).

---

## 🚀 Features

- ✅ Create new job postings  
- 📋 Fetch all available jobs  
- 🔍 Search job posts by keyword  
- ✏️ Update existing job postings  
- ❌ Delete job postings  
- 📦 Preload sample data for testing  

---

## 🧰 Tech Stack

| Layer | Technology |
|--------|-------------|
| Language | Java 17+ |
| Framework | Spring Boot |
| REST API | Spring Web |
| Data Layer | Spring Data JPA / Hibernate |
| Database | H2 (in-memory) / MySQL (configurable) |
| Build Tool | Maven |
| CORS | Enabled for `http://localhost:3000` (React frontend) 

---
## ⚙️ Configuration

'src/main/resources/application.properties'
'''properties'''
spring.application.name=job-posting-app
server.port=8081

# H2 Database (default)
spring.datasource.url=jdbc:h2:mem:jobsdb
spring.datasource.driverClassName=org.h2.Driver
spring.datasource.username=sa
spring.datasource.password=
spring.jpa.hibernate.ddl-auto=update
spring.h2.console.enabled=true

---

## ▶️ Running the Application

# 🧩 Prerequisites

Java 17+

Maven

(Optional) Frontend running at http://localhost:3000

---

## 🏃 Run Locally
# Clone the repository
git clone https://github.com/your-username/job-posting-app.git
cd job-posting-app

# Build and run
mvn spring-boot:run

---

## Application will start on:

http://localhost:8081
