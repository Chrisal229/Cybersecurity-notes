# ⚔️ Web Attacks Explained

## 🔥 XSS (Cross-Site Scripting)
- Injecting malicious JS into web pages
- Types:
  - Stored
  - Reflected
  - DOM-based

Example:
<script>alert('XSS')</script>

Impact:
- Cookie theft
- Session hijacking

---

## 💉 SQL Injection
- Manipulating database queries

Example:
' OR '1'='1

Impact:
- Data leakage
- Authentication bypass

---

## 🧠 CSRF (Cross-Site Request Forgery)
- Trick user into performing actions

Example:
- Changing password without user consent

Protection:
- CSRF Tokens
- SameSite cookies

---

## 🔐 Authentication vs Authorization

Authentication:
- Who you are

Authorization:
- What you can access

Cookies:
-Cookies store small data on the client and are automatically sent with every HTTP request to maintain state

Session:
-Data stored on the server, not in browser
