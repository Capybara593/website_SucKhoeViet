# website_SucKhoeViet
# Cấu trúc thư mục
src/main/java/com/example/elearning/
├── config/                  # Cấu hình Spring Boot, Security, etc.
├── controller/              # Các REST controller và MVC controller
│   ├── api/                 # REST API controllers
│   └── view/                # View controllers (cho Thymeleaf)
├── model/                   # Các entity và model class
│   ├── entity/              # JPA entities
│   └── enums/               # Các enum
├── repository/              # Spring Data JPA repositories
├── service/                 # Business logic
│   ├── impl/                # Các implementation của service interface
│   └── interfaces/          # Service interfaces
├── dto/                     # Data Transfer Objects
│   ├── request/             # Request DTOs
│   └── response/            # Response DTOs
├── exception/               # Custom exception và exception handlers
├── security/                # Spring Security config, JWT utils, etc.
│   ├── config/              # Security configuration 
│   ├── jwt/                 # JWT related classes
│   └── service/             # Security services
├── util/                    # Các utility class
└── ElearningApplication.java # Main application class
/////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
Chức năng:
