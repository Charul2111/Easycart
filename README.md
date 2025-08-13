# EasyCart 🛒

A full-stack e-commerce web application built with:

- **Frontend:** React
- **Backend:** Spring Boot
- **Database:** PostgreSQL

## **Tech Stack**
- **Frontend:** React, Axios
- **Backend:** Spring Boot, Java, Maven
- **Database:** PostgreSQL

## **Installation, Setup & Usage**
```bash
# 1. Clone the repo
git clone https://github.com/Charul2111/Easycart.git

# 2. Frontend setup
cd frontend
npm install
npm run dev

# 3. Backend setup
cd ../backend
mvn spring-boot:run

# 4. Database Setup
- Install PostgreSQL
- Create a database: `createdb mydb`
- Run the schema SQL file in `backend/src/main/resources/db/migration/` (or wherever your SQL is)
- Update `application.properties` with your DB username/password

# 5. Usage
- Open frontend at http://localhost:5173 (or your dev port)
- Backend runs on http://localhost:8080
