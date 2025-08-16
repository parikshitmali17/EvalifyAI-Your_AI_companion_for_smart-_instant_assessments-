# Quizzy

> A full-stack web app for teachers to generate, customize and deploy AI-powered quizzes, and for students to take them with on-demand explanations.

---

## 📚 Table of Contents

1. [Dependencies](#dependencies)
2. [Getting Started](#getting-started)
3. [Boilerplate](#boilerplate)
4. [Authentication Boilerplate](#authentication-boilerplate)
5. [Error Handling](#error-handling)
6. [Scripts](#scripts)
7. [Environment Variables](#environment-variables)

---

## 📦 Dependencies

- **Runtime**
  - `express`
  - `mongoose`
  - `passport` & `passport-local`
  - `jsonwebtoken`
- **Dev**
  - `nodemon`
  - `dotenv`

Install with:

```bash
npm install express mongoose passport passport-local jsonwebtoken dotenv
npm install --save-dev nodemon
```

---

## 🚀 Getting Started

1. Install dependencies:

   ```bash
   npm install
   npm install --save-dev nodemon
   ```

2. Create a `.env` file (see [Environment Variables](#environment-variables)).

3. Run in development:

   ```bash
   npm run dev
   ```

---



## 🔑 Environment Variables

Create a `.env` file at project root:

```env
MONGODB_URI=<your_mongo_connection_string>
JWT_SECRET=<your_jwt_secret>
PORT=5000
```
