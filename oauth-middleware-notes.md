# OAuth + Middleware Notes (May 3, 2025)

## What is OAuth?
- A protocol that lets users log in using a third-party service (like Google or GitHub)
- It grants access without sharing passwords

## What is Middleware?
- Functions that run before the route handler
- Used for authentication, validation, logging, and error handling

## 🔐 OAuth Basics

### 🧠 Key Roles:
- **Resource Owner** – the user who owns the data
- **Client** – the app requesting access
- **Authorization Server** – verifies identity & issues access tokens
- **Resource Server** – holds the protected data (e.g. Google APIs)

### 📦 What You Need to Integrate OAuth:
- **Client ID** – public identifier for your app
- **Client Secret** – private key for secure verification
- **Redirect URI** – where the OAuth provider sends the user after auth
- **Scopes** – define what access is being requested
- **Authorization Endpoint** – where the user logs in
- **Token Endpoint** – where your app exchanges code for a token
- **Access Token** – credential used to access protected resources

---

## 🧩 Middleware Overview

### 🔁 What is Middleware?
- A function that runs **before** your route/controller
- Common uses: auth, logging, error handling, request validation

### 🌐 REST API Methods:
- `GET` – read data
- `POST` – create data
- `PUT` – replace data
- `PATCH` – update part of data
- `DELETE` – remove data
- `HEAD`, `OPTIONS`, `TRACE` – metadata, preflight, debugging

---

## ⚙️ Other Concepts

- **MQ (Message Queues)** – ensures each message is processed once; supports async workflows
- **Robotic Middleware** – software layers for communication between robotic components
- **Microservices** – small, independent services forming a larger system

---

🗒️ _Session recap: Watched tutorial, created GitHub repo, reviewed OAuth flow and middleware foundations._
