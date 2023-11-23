# Transaction_service

Problem Statement
Build a microservices based User and Transaction Management system for a fintech company. 
The system should allow users to register, manage their user accounts, and perform financial 
transactions. You should implement this using Spring Boot, Spring Data JPA, and MongoDB for 
data storage.
1. User Service 
• Create a microservice called “UserService” responsible for user registration and 
management.
• Implement RESTful APIs for user registration and retrieving user details.
• Store user account data in MongoDB using Spring Data JPA.
• Implement basic user authentication.
2. Transaction Service
• Create a microservice called “TransactionService” responsible for managing financial 
transactions.
• Implement RESTful APIs for creating transactions (e.g., deposits, withdrawals).
• Store transaction data in MongoDB using Spring Data JPA.
• Ensure proper validation for transaction data.
• Implement security for transaction APIs.
3. Service Discovery and API Gateway
• Use Eureka for service registration and discovery.
• Implement an API Gateway to route requests to the appropriate microservices.
4. Data Validation
• Implement validation for user and transaction data.
• Handle validation errors gracefully.
2
5. User Authentication
• Implement authentication and authorization using Spring Security.
• Secure user related operations.
Additional Requirements
• Implement error handling for API requests.
• Secure sensitive data storage (e.g., user passwords) properly.
• Follow clean coding practices.
