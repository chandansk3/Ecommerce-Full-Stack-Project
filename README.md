# 🛒 Ecommerce Full Stack Web Application

A complete full-stack ecommerce platform built using React.js (frontend), Spring Boot (backend), and MySQL (database). Designed for users to browse products, register/login, and place orders — while allowing admins to manage categories, products, and users.

---

## 🔗 GitHub Repository Links

- 🔸 **Frontend:** [https://github.com/chandansk3/Ecommerce-Full-Stack-Project](https://github.com/chandansk3/Ecommerce-Full-Stack-Project)
  (Folder: `ecommerce-frontend-main`)
  
- 🔸 **Backend:** [https://github.com/chandansk3/Ecommerce-Full-Stack-Project](https://github.com/chandansk3/Ecommerce-Full-Stack-Project)
  (Folder: `Ecommerce-backend-main`)

---

## 🌐 Hosted URLs

- ✅ **Frontend (GitHub Pages):**  
  [https://chandansk3.github.io/Ecommerce-Full-Stack-Project/](https://chandansk3.github.io/Ecommerce-Full-Stack-Project/)

- ✅ **Backend (Render):**  
  [https://ecommerce-full-stack-project-oiqd.onrender.com](https://ecommerce-full-stack-project-oiqd.onrender.com)

---

## 📦 Module: Category Management

### 🎯 Objective:
Allow admin users to Create, Read, Update, and Soft Delete product categories.

### 🔑 Features:
- View all categories in a list
- Add new categories
- Edit category names
- Soft delete categories (mark as inactive)

---

### 🛠️ How to Use:

1. Log in as Admin
2. Go to **Admin Dashboard**
3. Click on **“Category”** in the sidebar
4. To add:
   - Enter category name → Click **Add Category**
5. To update:
   - Click **Edit** icon → Update name → Click **Update**
6. To delete:
   - Click **Delete** icon → Marks as inactive (soft delete)

---

### 🔗 API Endpoints (Spring Boot)

| Method | Endpoint                      | Description              |
|--------|-------------------------------|--------------------------|
| GET    | `/category/`                  | Get all categories       |
| POST   | `/category/add`               | Add a category           |
| PUT    | `/category/update/{id}`       | Update a category        |
| DELETE | `/category/delete/{id}`       | Soft delete a category   |

---

## 🧪 Screenshots

> Add screenshots of the key pages here (optional)

- Home Page  
- Admin Dashboard  
- Category Form  
- Product Form  
- Product Listing  
- User Registration/Login  

---

## ⚙️ Tech Stack

- **Frontend:** React.js, Axios, Bootstrap, GitHub Pages
- **Backend:** Spring Boot, Spring MVC, Spring Data JPA
- **Database:** MySQL (local or hosted)
- **Deployment:** Render (backend), GitHub Pages (frontend)

---

## 🚀 How to Run Locally

### 📦 Frontend
```bash
cd ecommerce-frontend-main
npm install
npm start


📂 MySQL Setup
Create DB: ecommerce

Run schema.sql (if any)

Update application.properties:

properties
Copy
Edit
spring.datasource.url=jdbc:mysql://localhost:3306/ecommerce
spring.datasource.username=root
spring.datasource.password=your-password
