# Salon Appointment Booking

## 📌 Overview
The **Salon Appointment Booking** system is a comprehensive platform designed to streamline salon scheduling, manage customer bookings, and integrate secure payment processing. Built on a **microservices architecture**, this project ensures **scalability, reliability, and flexibility** for modern salon businesses.

---

## 🛠️ Microservices Architecture
The system follows a **distributed architecture** where different functionalities operate as independent microservices. This approach allows for better maintainability and scalability.

---

## 💻 Backend Development
The backend is developed using **Spring Boot**, ensuring a robust and efficient system. Key technologies include:

- 🌟 **Spring Boot**: To build powerful backend APIs and microservices.
- 🔒 **Keycloak**: Handles authentication and authorization securely.
- 🔑 **JWT (JSON Web Token)**: Ensures token-based security.
- 🗄️ **MySQL**: Stores and manages structured data efficiently.
- ⚡ **RabbitMQ**: Enables real-time, event-driven communication between services.
- 🔔 **WebSocket**: Facilitates real-time notifications for users.

---

## 🎨 Frontend Development
The frontend leverages modern web technologies to provide a seamless user experience:

- ⚛️ **React**: Builds a dynamic and responsive UI.
- 📊 **Redux**: Manages application state efficiently.
- 📝 **Formik**: Simplifies form handling and validation.
- 🔗 **Axios**: Enables seamless API integration with clean request handling.

---

## ⚙️ DevOps Essentials
Deployment and infrastructure management are streamlined using:

- 🐳 **Docker**: Simplifies development and deployment with containerized applications.

---

## 💵 Payment Integration
Secure and reliable payment gateways are implemented using:

- **Razorpay**
- **Stripe**

These services ensure secure transactions and seamless payment processing.

---

## 🚀 Getting Started
### Prerequisites
- Java 17+
- Node.js 18+
- Docker & Docker Compose
- MySQL database setup

### Installation
```sh
# Clone the repository
git clone https://github.com/your-repo/salon-booking.git
cd salon-booking

# Start backend services
cd backend
./mvnw spring-boot:run

# Start frontend
cd frontend
npm install
npm start

# Run services using Docker
docker-compose up --build
```


