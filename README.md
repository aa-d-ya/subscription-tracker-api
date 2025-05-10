# 🚀 Subscription TrACKER API

## 🧾 Introduction
The **Subscription Management System API** is a robust, production-ready backend system designed to handle **real users**, **real payments**, and **real business logic**. It enables secure user authentication, seamless database integration, and efficient subscription workflows — all while ensuring scalability and maintainability.

---

## 🛠 Tech Stack
- ⚙️ **Node.js** – Backend runtime environment  
- 🧩 **Express.js** – Web framework  
- 🍃 **MongoDB** – NoSQL database  
- 🧬 **Mongoose** – MongoDB ORM  
- 🔐 **JWT** – Authentication  
- 🛡️ **Arcjet** – Advanced rate limiting and bot protection  
- ✉️ **Upstash** – Email workflow and reminder automation  

---

## ✨ Features

- 🔐 **JWT Authentication**  
  Secure user login, registration, and session management using JSON Web Tokens.

- 🛡️ **Advanced Rate Limiting & Bot Protection**  
  Integrated Arcjet to secure endpoints and prevent abuse by bots.

- 🗃️ **MongoDB & Mongoose Models**  
  Structured and scalable database models to handle complex relationships and queries.

- 📦 **Subscription Management**  
  Flexible logic to create, update, cancel, and manage subscriptions efficiently.

- ❗ **Global Error Handling**  
  Unified error responses and validation through middleware for consistent developer and client experience.

- 📬 **Email Reminder Workflows**  
  Automated and scheduled email notifications for subscription reminders using Upstash.

- 🪵 **Logging & Debugging**  
  Built-in logging mechanisms for easier debugging and production monitoring.

- 🧱 **Modular Architecture**  
  Clean folder structure and reusable code components make the system scalable and maintainable.

---

## 📫 API Endpoints Overview

- `POST /api/auth/register` – 📝 Register a new user  
- `POST /api/auth/login` – 🔐 User login  
- `GET /api/subscription` – 📄 Retrieve current user subscriptions  
- `POST /api/subscription` – ➕ Create a new subscription  
- `PUT /api/subscription/:id` – 🔄 Update a subscription  
- `DELETE /api/subscription/:id` – ❌ Cancel a subscription  
