## 🔐 Login & Register Page – Level 6 Authentication (OAuth + Session-Based Authentication)

This project builds on Level 5 and adds Google OAuth 2.0 login, so users can log in using their Google account. It uses Node.js, Express, EJS, PostgreSQL, Passport.js, and environment variables.
---
Features:

Users can register with email/password (Level 5 auth).
Users can log in via Google OAuth 2.0.
Session-based authentication persists across pages using express-session.
Protected routes like /secrets are accessible only if authenticated.
Database credentials and session secrets are stored in .env.
---
🔑 Levels of Authentication:<br><br>
Level 1: Basic Cipher (Caesar, Hill, Playfair, etc.)<br>
Level 2: Hashing (MD5, SHA, etc.)<br>
Level 3: Hashing + Salt Rounds (bcrypt)<br>
Level 4: Session-Based Authentication (bcrypt + Passport.js + Cookies)<br>
Level 5: Environment Variables + Session-Based Authentication<br>
Level 6: OAuth (Open Authorization) 

---
## 📷 Gallery

| SignUp Page | Login Page |
|-------------|------------|
| ![lgl1](./imgg/lgl1.png) | ![ld1](./imgg/ld1.png) |

| Register Page | Secret Page |
|---------------|-------------|
| ![hl2](./imgg/hl2.png) | ![hl](./imgg/hl.png) |

| DataBase |
|---------------|
| ![ld6](./imgg/ld6.png) |



---

## ⚙️ Setup Instructions

 1️⃣ Create Table in PostgreSQL(users):
 <br><br>
as given in the query.sql
 <br>
 
2️⃣ Install Dependencies:
```bash
npm i
npm i pg express ejs body-parser
```
3️⃣Google OAuth Credentials set up: 


<img src="./imgg/oa1.png" width="800">  
<img src="./imgg/oa2.png" width="300">  
<img src="./imgg/oa3.png" width="300">  
<img src="./imgg/oa4.png" width="300">  
<img src="./imgg/oa5.png" width="300">  
<img src="./imgg/oa6.png" width="300">  
<img src="./imgg/oa7.png" width="300">  
<img src="./imgg/oa8.png" width="300">  
<img src="./imgg/oa9.png" width="300">  
<img src="./imgg/oa10.png" width="300">  
<img src="./imgg/oa11.png" width="300">  
<img src="./imgg/oa12.png" width="300">  
<img src="./imgg/oa13.png" width="300">


4️⃣ Run Server:
```bash
node index.js
```
---
👉 [Open App on Localhost](http://localhost:3000)
