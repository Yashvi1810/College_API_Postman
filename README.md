# College Student API – Manual API Testing (Postman)

## 📌 Project Overview
This project demonstrates *manual API testing using Postman* for a *College Student Management API*.  
The API works with student data in *JSON format* and supports complete *CRUD operations*.

The objective of this project is to validate API functionality, responses, and data handling using Postman without automation.

---

## 🛠 Tools Used
- *Postman*
- *JSON*
- *GitHub*

---

## 🔗 API Operations Tested

| HTTP Method | Description |
|------------|------------|
| GET | Retrieve student data |
| POST | Create new student record |
| PUT | Update existing student record |
| DELETE | Delete student record |

---

## ✅ Testing Scope

The following aspects were manually tested for each API request:

- ✔ Status Codes validation  
- ✔ Response Body verification  
- ✔ Response Time validation  
- ✔ Headers validation  
- ✔ Cookies validation  
- ✔ JSON data structure  
- ✔ CRUD functionality  

---

## 🌍 Variables Used in Postman

The project includes proper usage of Postman variables: GLOBAL,ENVIRONMENT,LOCAL

### 1️⃣ Global Variables
- Used for commonly shared values across requests

### 2️⃣ Environment Variables
- Used for environment-specific values (e.g., base URL, student ID)

### 3️⃣ Local Variables
- Used within individual requests

### Variable Functions Used:
- set
- get
- unset

---

## 📂 Project Contents

- 📁 Postman Collection (JSON)
- 📄 README.md
- 📄 Sample Student JSON Data

---

## 📑 Sample Student JSON
```json
{
  "students": [
    {
      "id": "1",
      "name": "Nidhi Updated (PATCH)",
      "branch": "IT",
      "course": "B.Tech",
      "language": [
        "Java",
        "Python"
      ],
      "college": "New College Name",
      "city": "New City Name",
      "country": "India",
      "phone": "9999999999"
    },
