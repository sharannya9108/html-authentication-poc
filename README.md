# HTML Authentication POC

## 📌 Project Description

This project is a simple Proof of Concept (POC) for an authentication flow built using only plain HTML.  
It demonstrates basic page navigation and redirection using anchor tags and form actions.

⚠️ No CSS or JavaScript is used as per assignment instructions.

---

## 📂 Project Structure

The project contains the following files:

- login.html
- register.html
- forgot-password.html
- reset-password.html
- dashboard.html
- README.md

---

## 🔄 Authentication Flow

### 1️⃣ Login Page (login.html)
- Fields:
  - Username
  - Password
- Login button redirects to: `dashboard.html`
- "Forgot Password?" link redirects to: `forgot-password.html`
- "Create New Account" link redirects to: `register.html`

---

### 2️⃣ Register Page (register.html)
- Fields:
  - Name
  - Email
  - Phone Number
  - Password
  - Confirm Password
- Register button redirects to: `login.html`
- "I already have an account" link redirects to: `login.html`

---

### 3️⃣ Forgot Password Page (forgot-password.html)
- Field:
  - Email
- "Send Password Reset Link" button redirects to: `login.html`
- "Back to Login" link redirects to: `login.html`

---

### 4️⃣ Reset Password Page (reset-password.html)
- Fields:
  - New Password
  - Confirm Password
- "Update Password" button redirects to: `login.html`
- "Back to Login" link redirects to: `login.html`

---

### 5️⃣ Dashboard Page (dashboard.html)
- Displays: "Welcome to My Dashboard"
- Logout button redirects to: `login.html`

---

## 🚀 How to Run the Project

### Option 1: Direct Method (Recommended)
1. Download or clone the repository.
2. Open the project folder.
3. Double-click `login.html`.
4. Test all page redirections.

---

### Option 2: Using XAMPP
1. Move the project folder to:
   C:\xampp\htdocs\
2. Start Apache in XAMPP.
3. Open browser and navigate to:
   http://localhost:8080/html-authentication-poc/login.html
4. Test all redirections.

---

## 🛠 Technologies Used

- HTML5
- Anchor Tags
- Form Redirection

No CSS  
No JavaScript  
No Backend  

---

## 🎯 Assignment Requirements Covered

✅ All 5 HTML pages created  
✅ Proper redirections implemented  
✅ No CSS or JavaScript used  
✅ README.md included  
✅ Repository is Public  

---

## 👩‍💻 Author

Sharanya Ram  
