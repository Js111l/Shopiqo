# :convenience_store: Shopiqo

![logo jpg](https://github.com/user-attachments/assets/e0ed9215-5d68-49fe-b2cb-35dd12a6bf24)

## General info
Shopiqo is a full-stack e-commerce store project. The platform supports product listings, simple products filtering, a shopping cart, secure transactions, and user authentication. 
The backend is built in microservice architecure consisting of four core services: SecurityService, ProductService, FinancialTransactionsService and GatewayService - which serves as an API gateway. 
Services has been implemented using Java and Spring Boot, except for FinancialTransactionsService, which was developed using Scala.


### Screenshots
![login-view jpg](https://github.com/user-attachments/assets/cdf03c65-03ed-4b52-8117-ffc968ed8312)
![payment-view jpg](https://github.com/user-attachments/assets/2732bb31-cc2a-4889-9273-3784268df3e7)
![checkout-view](https://github.com/user-attachments/assets/d4aeaedb-79e5-442e-840f-1ad3c2530c5c)
![products-list jpg](https://github.com/user-attachments/assets/d1dbe980-5436-4358-899f-210a340944c2)


## 🚀 **Full Tech Stack of the Project**

#### **Backend**  
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)  ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat&logo=springboot&logoColor=white)  ![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat&logo=spring&logoColor=white)  ![Spring Data](https://img.shields.io/badge/Spring%20Data-6DB33F?style=flat&logo=spring&logoColor=white)  ![Spring Cloud](https://img.shields.io/badge/Spring%20Cloud-6DB33F?style=flat&logo=spring&logoColor=white)  ![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=flat&logo=hibernate&logoColor=white)  ![MapStruct](https://img.shields.io/badge/MapStruct-0052CC?style=flat&logoColor=white)  ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)  ![OpenFeign](https://img.shields.io/badge/OpenFeign-FF7F50?style=flat&logoColor=white)  ![JJWT](https://img.shields.io/badge/JJWT-000000?style=flat&logo=jwt&logoColor=white)  
![Scala](https://img.shields.io/badge/Scala-DC322F?style=flat&logo=scala&logoColor=white)  ![Akka HTTP](https://img.shields.io/badge/Akka%20HTTP-4B4F56?style=flat&logoColor=white)  ![Slick](https://img.shields.io/badge/Slick-4B4F56?style=flat&logoColor=white)  ![Guice](https://img.shields.io/badge/Guice-00897B?style=flat&logoColor=white)  ![Spray-JSON](https://img.shields.io/badge/Spray--JSON-FF5722?style=flat&logoColor=white)  

#### **Database & Migrations**  
![Flyway](https://img.shields.io/badge/Flyway-CC0000?style=flat&logoColor=white)  ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white)  

#### **Frontend**  
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)  ![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=flat&logo=javascript&logoColor=F7DF1E)  


## Functionalities

* User login and registration
* Payment integration with Stripe API.
* Products list
* User wishlist
* Basic product filtering (e.g., by category, price, color)
* User session management using Redis cache
* JWT authentication for communication between microservices
  
## Project status - :arrows_counterclockwise: In Development

The project is currently in development, with the main focus on improving the current user experience and building an admin panel. Planned functionalities for the admin panel include:

* Homepage with a specific dashboards
* Special reports
* CRUD operations for product management
* Support for importing products via CSV files
* Promotion management for products (introducing a separate PriceService)

### Code
* Frontend - https://github.com/Js111l/Ecommerce-UI
* SecurityService - https://github.com/Js111l/Security_Service
* ProductService - https://github.com/Js111l/Product_Service
* FinancialTransactionsService - https://github.com/Js111l/Financial_Transactions_Service
* GatewayService - https://github.com/Js111l/Gateway_service
