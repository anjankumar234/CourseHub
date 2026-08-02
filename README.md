# 📚 CourseHub

CourseHub is a full-stack online learning platform that allows users to browse, enroll in, and manage courses. The application provides a seamless learning experience with secure authentication, course management, and an interactive user interface.

---

## Features

- User registration and login
- Secure authentication and authorization
- Browse available courses
- Enroll in courses
- User dashboard
- Course management
- Search and filter courses
- Responsive design

---

## Tech Stack

### Frontend

- Thymeleaf
- HTML5
- CSS3
- JavaScript

### Backend

- Java
- Spring Boot
- Spring MVC
- Spring Security
- Hibernate / JPA

### Database

- MySQL

### Tools

- Git & GitHub
- Maven
- Postman

---

## Project Structure

```text
CourseHub/
│
├── src/
│   ├── main/
│   │   ├── java/
│   │   ├── resources/
│   │   │   ├── static/
│   │   │   │   ├── css/
│   │   │   │   ├── js/
│   │   │   ├── templates/
│   │   │   └── application.properties
│
└── pom.xml
```

---

## Installation

### Clone the repository

```bash
git clone https://github.com/anjankumar234/CourseHub.git
```

### Navigate to the project

```bash
cd CourseHub
```


### Configure the database

Update the `application.properties` file:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/coursehub

spring.datasource.username=your_username

spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update
```

### Run the application

```bash
mvn spring-boot:run
```

Open your browser and visit:

```text
http://localhost:8080
```

---


## Screenshots

- Home page
 <img width="1600" height="847" alt="image" src="https://github.com/user-attachments/assets/3bc30156-05b2-494b-9d1b-9cadd47bebfa" />

- SignUp page
 <img width="1600" height="859" alt="image" src="https://github.com/user-attachments/assets/e18c60eb-6bf4-49b0-9060-77000f958e43" />

- Student Dashboard
 <img width="1600" height="848" alt="image" src="https://github.com/user-attachments/assets/ecf667eb-8d67-4a44-9c49-3240bcd5edac" />

- Trainers Dashboard
 <img width="1600" height="844" alt="image" src="https://github.com/user-attachments/assets/919c733f-d4aa-4fff-b28f-eadc7a0fe284" />

- Admin's Dashboard
 <img width="1600" height="845" alt="image" src="https://github.com/user-attachments/assets/1a36c3fd-60fb-4256-b6b7-58ddca9876fe" />
---

## Future Enhancements

- Course completion certificates
- Payment integration
- Video lectures
- Admin dashboard
- Notifications
- Rating and review system

---

## Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Added new feature"
```

4. Push the changes

```bash
git push origin feature-name
```

5. Create a Pull Request

---

## Author

**Anjan Kumar**

- GitHub: https://github.com/anjankumar234
- LinkedIn: www.linkedin.com/in/anjan-kumar-kantepalli-a60940253

---

## 📜 License

This project is licensed under the MIT License.
