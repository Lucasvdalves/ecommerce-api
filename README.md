# 🛒 Ecommerce API

## 📌 About the Project
This project is a RESTful API developed with Java and Spring Boot to simulate the backend of an ecommerce platform. It handles products, categories, and basic cart logic, enabling developers to integrate a simple ecommerce service.

## 💡 Features
- CRUD operations for products and categories
- Add/remove products to/from a simulated shopping cart
- Basic input validation
- In-memory database (H2)

## 🛠️ Technologies Used
- Java 17
- Spring Boot
- Spring Data JPA
- H2 Database
- Maven
- Lombok

## 📁 Folder Structure
```
├── src
│   ├── main
│   │   ├── java
│   │   │   └── com.ecommerce
│   │   └── resources
│   │       └── application.properties
```

## 🚀 Getting Started
1. Clone the repository
2. Open the project in your IDE
3. Run `EcommerceApiApplication.java`

```bash
git clone https://github.com/Lucasvdalves/ecommerce-api.git
```

## 🔍 API Endpoints
- `GET /products`
- `POST /products`
- `PUT /products/{id}`
- `DELETE /products/{id}`
- `GET /categories`

## 🎯 Future Improvements
- Integrate with frontend
- Connect to a persistent database
- Add payment processing logic

## 📄 License
MIT License

