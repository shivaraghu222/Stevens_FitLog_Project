
# 🏋️‍♂️ Stevens FitLog – Full-Stack Fitness Tracking Application

FitLog is a full-stack fitness and health tracking platform that allows users to log workouts, track running/cycling activity, monitor calories, view diet recommendations, and visualize weekly averages.  
The backend is built with **Node.js, Express, MongoDB Atlas**, and **Mongoose**, with a simple HTML/CSS frontend served from the backend.

---

## 🚀 Features

### 🔐 **User Authentication**
- Secure registration & login  
- Password hashing using **bcrypt**  
- JWT-based authentication (tokens required for protected routes)

### 🏋️ **Fitness Modules**
- Create and manage fitness plans  
- Log **running** and **cycling** activities  
- Track **daily calories**  
- Browse **diet recommendations** (auto-loaded on first use)

### 📊 **Analytics**
- Weekly averages for:
  - Running distance  
  - Cycling distance  
  - Calorie intake  
- Combined weekly wellness score  
- Dashboard UI with charts & tables

### 🌐 **Backend + Frontend Integration**
- Backend serves HTML frontend pages  
- Auto-opens browser on server start  
- Public assets hosted through Express (`/public`)

### ☁️ **MongoDB Atlas Integration**
- Cloud-hosted MongoDB database  
- Mongoose models & schema validation  
- Automatic seeding of diet data on first server start

---

## 🗂️ Project Structure

Backend/
│── index.js # Main server file
│── package.json
│── models/ # Mongoose schemas
│── routes/ # Auth & fitness routes
│── public/ # Frontend assets (HTML/CSS/JS)
└── (HTML files in root directory)



---

## 🧰 Technologies Used

### **Backend**
- Node.js  
- Express.js  
- Mongoose  
- MongoDB Atlas  
- JWT (jwt-simple)  
- bcrypt  
- body-parser  
- cors  

### **Frontend**
- HTML  
- CSS  
- JavaScript  
- Bootstrap  

---

## ⚙️ Installation & Setup

### **1. Clone the repository**
git clone https://github.com/yourusername/Stevens-Fitlog.git
cd Stevens-Fitlog/Backend

2. Install dependencies
   npm install

3. Add your MongoDB connection string
    In index.js, update: 
    const connection_string =
    "mongodb+srv://<username>:<password>@cluster0.xxxxx.mongodb.net/FitLogDB?retryWrites=true&w=majority&appName=Cluster0";

4. Running the Server
   node index.js

   Server is running on port 8000!!

OR

1. Open Visual Studio.
2. Open the Stevens-Fitlog project.
3. Select the backend only option.
4. In the index.js file, open the terminal and type "npm i" to install the required dependencies.
5. Once the installation is complete, type "node index" in the terminal to start the server.
6. After connecting to the server, you will be directly connected to the Stevens-Fitlog website.
7. Or else, Open a web browser and go to http://localhost:8000/ to access the Stevens-Fitlog website.
