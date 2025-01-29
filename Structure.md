# Bookstore
структурой проекта: 

bookstore/ 

├── src/ 

│ ├── main/ 

│ │ ├── java/com/bookstore.bookstore/ 

│ │ │ ├── BookstoreApplication.java 

│ │ │ ├── config/ 

│ │ │ │ └── AppConfig.java 

│ │ │ ├── controller/ 

│ │ │ │ ├── BookController.java 

│ │ │ │ ├── CategoryController.java 

│ │ │ │ └──UserController.java 

│ │ │ ├── model/ 

│ │ │ │ ├── Book.java 

│ │ │ │ ├── Category.java 

│ │ │ │ └── User.java 

│ │ │ ├── repository/ 

│ │ │ │ ├── BookRepository.java 

│ │ │ │ ├── CategoryRepository.java 

│ │ │ │ └── UserRepository.java 

│ │ │ ├── service/ 

│ │ │ │ ├── imple/ 

│ │ │ │ │ ├── BookServiceImpl.java 

│ │ │ │ │ ├── CategoryServiceImpl.java 

│ │ │ │ │ └── UserServiceImpl.java 

│ │ │ │ ├── BookService.java 

│ │ │ │ ├── CategoryService.java 

│ │ │ │ └── UserService.java 

│ │ │ ├── dto/ 

│ │ │ │ ├── BookDto.java 

│ │ │ │ ├── CategoryDto.java 

│ │ │ │ └── UserDto.java 

│ │ │ ├── exception/ 

│ │ │ │ ├── BookNotFoundException.java 

│ │ │ │ ├── CategoryNotFoundException.java 

│ │ │ │ ├── UserNotFoundException.java 

│ │ │ │ └── GlobalExceptionHandler.java 

│ │ │ └── util/ 

│ │ │ │ └── ModelMapperConfig.java 

│ │ └── resources/ 

│ │ │ ├── application.properties 

│ │ │ ├── static/ 

│ │ │ └── templates/ 

│ └── test/ 

│ │ ├── Java 

│ │ │ ├── com.bookstore.bookstore 

│ │ │ │ ├── BookstoreApplicationTests.java 

├──.mvn/ 

│ └── wrapper/ 

│ │ └── maven-wrapper 

└── pom.xml
