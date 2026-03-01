# 🔐 Spring Security Roadmap
**From Core Security Concepts to Spring Security Implementations**

This repository/document provides a structured roadmap to understand **Security in applications** and its implementation using **Spring Security**, starting from fundamentals and moving to real authentication mechanisms.

---

## 🛡️ 1. Security Fundamentals

### 🔑 Authentication
**Who are you?**  
Authentication is the process of verifying the identity of a user.

Examples:
- Username + Password
- OTP
- Token-based login (JWT)
- Biometric

---

### 🛂 Authorization
**What are you allowed to do?**  
Authorization determines user permissions after authentication.

Examples:
- Admin can delete users
- User can view profile
- Manager can approve requests

---

## 🌱 2. Spring Security (Framework Layer)

Spring Security is the **security framework** in the Spring ecosystem that provides:

- Authentication mechanisms
- Authorization mechanisms
- Session management
- CSRF protection
- CORS handling
- Password encryption
- Security filters
- Token support (JWT, OAuth2)

### Core Components:
- `SecurityFilterChain`
- `AuthenticationManager`
- `AuthenticationProvider`
- `UserDetailsService`
- `PasswordEncoder`
- `SecurityContextHolder`

---

## 🧱 3. Authentication Mechanisms in Spring Security

Spring Security provides multiple authentication types:

### 🔹 A. Form Authentication (Form Login)

**UI-based authentication**