## 🔐 Login & Register Page – Level 6 Authentication (OAuth + Session-Based Authentication)

This project extends Level 5 Authentication by adding Google OAuth 2.0 login. Users can log in either with their email/password or via their Google account. The application uses Node.js, Express, EJS, PostgreSQL, Passport.js, and environment variables for secure configuration.

---
Features:

- Users can register with email and password (Level 5 auth).
- Users can log in using their Google account via OAuth 2.0.
- Session-based authentication ensures users stay logged in across pages.
- Protected routes like /secrets are accessible only to authenticated users.
- Database credentials and session secrets are securely stored in a `.env` file.

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


<img src="./imgg/oa1.png" width="1000">  
<img src="./imgg/oa2.png" width="1000">  
<img src="./imgg/oa3.png" width="1000">  
<img src="./imgg/oa4.png" width="1000">  
<img src="./imgg/oa5.png" width="1000"> 
<img src="./imgg/oa6.png" width="1000"> 
<img src="./imgg/oa7.png" width="1000"> 
<img src="./imgg/oa8.png" width="1000"> 
<img src="./imgg/oa9.png" width="1000">  
<img src="./imgg/oa10.png" width="1000"> 
<img src="./imgg/oa11.png" width="1000"> 
<img src="./imgg/oa12.png" width="1000">  
<img src="./imgg/oa13.png" width="1000"> 


4️⃣ Edit .env file:
    as give in the .ENV.txt


5️⃣ Run Server:
```bash
node index.js
```
---
👉 [Open App on Localhost](http://localhost:3000)
