🧠 Proctor AI – Intelligent Exam Monitoring System
Proctor AI is a cutting-edge learning application designed to ensure secure and fair online assessments using artificial intelligence. The platform is built using a microservices architecture, ensuring scalability, modularity, and ease of maintenance.

🔍 Key Features
🎥 Live Proctoring using webcam stream analysis
🧠 AI-based Cheat Detection (e.g., multiple faces, phone usage, background noise)
📚 Learning Platform Integration (LMS compatibility)
📊 Real-Time Reports for examiners
🧪 Face and voice recognition
🏗️ Tech Architecture
This project uses Microservices to separate responsibilities across different services, improving reliability and performance:

🧩 Services Overview:
Service	Description	Framework
Auth Service	Handles user login, JWT token generation, and permissions	Flask
Exam Service	Manages exams, questions, timing, and scheduling	FastAPI
Proctoring Service	Handles webcam/video stream processing with AI/ML models	Flask
Notification Service	Sends alerts and results via email/SMS	FastAPI
Monitoring Dashboard	Admin UI to view exam status, logs, and reports	React (or your choice)
🛠️ Tech Stack
Languages: Python
Frameworks: Flask, FastAPI
Database: PostgreSQL, MongoDB
Message Broker: RabbitMQ / Redis (for inter-service communication)
Containerization: Docker & Docker Compose
Deployment: AWS (EC2, S3), GitHub Actions (CI/CD)
🚀 Why Flask and FastAPI?
Flask was used in services that needed flexibility, lightweight routes, and easier integration with AI/ML models.
FastAPI was used for services where performance and auto-generated docs (Swagger/OpenAPI) were essential, like exam management and notifications.
