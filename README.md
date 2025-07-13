# JustTravel - Travel Listing Website

Welcome to **JustTravel**, a travel listing platform hosted at [https://justtravel-mern-project.onrender.com/listings](https://justtravel-mern-project.onrender.com/listings). This project is a full-stack web application built using **JavaScript**, **Node.js**, **Express.js**, and **MongoDB**. It allows users to explore, create, edit, and manage travel listings seamlessly.

---

## ✨ Features

- 🔍 View all travel listings
- ➕ Create new listings
- ✏️ Edit/update existing listings
- ❌ Delete listings
- 🔐 Authentication & Authorization using **Passport.js**
- ⚙️ RESTful API design
- ⚠️ Basic error handling

---

## 🧰 Tech Stack

- **Frontend**: HTML, CSS, JavaScript, EJS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: Passport.js (local strategy)
- **API Architecture**: REST

---

## 🔐 Authentication & Authorization

Implemented using **Passport.js** to:
- Register and log in users
- Restrict edit/delete functionality to authorized users only
- Maintain secure session handling

---

## 🔄 REST API Endpoints

| Method | Route             | Description              |
|--------|------------------|--------------------------|
| GET    | `/listings`       | Show all listings        |
| GET    | `/listings/:id`   | Show specific listing    |
| POST   | `/listings`       | Create a new listing     |
| PUT    | `/listings/:id`   | Update an existing listing |
| DELETE | `/listings/:id`   | Delete a listing         |

---

## 🛠️ Error Handling

Basic error messages are shown for:
- Invalid inputs
- Unauthorized access
- Missing or deleted listings

---


