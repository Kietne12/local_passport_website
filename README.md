# Test local_passport_website

1. Register  
POST http://localhost:3000/register  
username: thekiet
password: 12345
![Register Page](public/results/register.png)
![User in Mongo after Register](public/results/user_db.png)


2. Login  
POST http://localhost:3000/login  
username = thekiet
password = 12345
![Login Page](public/results/login.png)
![Cookie](public/results/cookie.png)

3. Profile (sau khi login)  
GET http://localhost:3000/profile  
![Profile Page](public/results/profile.png)

4. Logout  
GET http://localhost:3000/logout  
![Logout Page](public/results/logout.png)

5. Profile sau khi logout  
GET http://localhost:3000/profile  
![Profile After Logout](public/results/profile_after_logout.png)

