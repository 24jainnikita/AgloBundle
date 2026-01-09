# AlgoBundle📚

AlgoBundle is a curated repository of Data Structures and Algorithms solutions designed to strengthen problem-solving skills and algorithmic thinking for coding interview preparation.

# ✨Features

## Frontend

🖥️ React-based UI for an interactive user experience.

📊 Dynamic progress tracker for visualizing solved, attempted, and remaining questions.

📝 User-friendly forms for adding, editing, and deleting questions.

✅ Toggle switch to mark questions as solved.

🔍 Search and filter functionality based on topics and difficulty.

## Backend

🚀 Developed using Spring Boot.

🌐 RESTful APIs for CRUD operations on questions.

🗄️ Database integration with MySQL for persistent data storage.

⚙️ Custom exception handling for improved API responses.

📈 Progress metrics API to provide real-time progress updates.

# 💻Tech Stack

## Frontend

React.js

Axios for API requests

Bootstrap CSS for styling

## Backend

Java Spring Boot

MySQL

Maven for project management

Lombok for reducing boilerplate code

# 🛠️Installation and Setup

## Prerequisites

Node.js and npm installed

Maven installed (or use the included Maven Wrapper mvnw)

MySQL server running

## Frontend

Clone the repository: git clone https://github.com/24jainnikita/AlgoBundle.git

Navigate to the frontend directory: cd algobundle-fe

Install dependencies: npm install

Start the development server: npm start

## Backend

Navigate to the backend directory: cd algobundle

Update MySQL credentials in application.properties:

spring.datasource.url=jdbc:mysql://localhost:3306/algobundle
spring.datasource.username=yourUsername
spring.datasource.password=yourPassword

Run the backend application: ./mvnw spring-boot:run

# API Endpoints

DSA Question Management

GET /api/dsa: Retrieve all questions

GET /api/dsa/{id}: Retrieve a question by ID

POST /api/dsa: Add a new question

PUT /api/dsa/{id}: Update an existing question

DELETE /api/dsa/{id}: Delete a question

Progress Tracker

GET /api/dsa/progress: Get progress metrics (total, solved, attempted, remaining questions)

# 📸Screenshots
![image](https://github.com/user-attachments/assets/a389f270-685c-4f56-83d6-406d3e9ac347)
![image](https://github.com/user-attachments/assets/3c813f02-7d99-435c-ad66-6197fe227037)
![image](https://github.com/user-attachments/assets/384a723f-1707-43a0-bcd0-4b76c4ab5022)
![image](https://github.com/user-attachments/assets/cc8b86a7-8d30-4c0f-aa14-a1b7239c9b48)

# 🤝Contributing

welcome contributions! Follow these steps:

Fork the repository.

Create a new branch: git checkout -b feature-name

Commit your changes: git commit -m "Added new feature"

Push to the branch: git push origin feature-name

Open a pull request.

# 📧Contact

For any questions or suggestions:

Email: 247jainnikita@gmail.com

LinkedIn: https://www.linkedin.com/in/24jainnikita/

GitHub: https://github.com/24jainnikita

# Thank you for visiting AlgoBundle! Happy Coding! 🧑‍💻
