
Payment_Gateway/
├── src/main/java/com/example/Payment_Gateway/
│   ├── PaymentGatewayApplication.java  # Main class
│   ├── controller/PaymentController.java
│   ├── service/PaymentService.java
│   ├── dto/Payment.java
│   ├── repository/PaymentRepository.java
│   └── exception/PaymentFailedException.java
├── src/main/resources/
│   ├── static/                         # Frontend files
│   │   ├── index.html
│   │   
│   │   
│   └── application.properties
└── pom.xml

**Digital Payment Portal** is a comprehensive full-stack web application that simulates real-world online payment processing, built with Java Spring Boot for the backend and HTML/CSS/JavaScript for the frontend. This project enables users to initiate secure digital payments through an intuitive interface by entering dealer ID, transaction amount, and selecting payment methods like Credit Card, Debit Card, UPI, or Net Banking. The system processes payments asynchronously—first marking them as "PENDING" before automatically updating to "SUCCESS" after a simulated 5-second processing period—while providing real-time status tracking where users can retrieve complete transaction details anytime. Featuring a responsive design with form validation, loading animations, and color-coded status indicators, the application demonstrates end-to-end development skills including REST API design, MySQL database integration, Spring Data JPA implementation, and modern frontend practices. The complete solution showcases practical payment gateway functionality with a clean separation of concerns between backend business logic and frontend user experience, making it an ideal portfolio project that mirrors commercial payment systems while being fully functional for educational and demonstration purposes.
