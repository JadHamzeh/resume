# Jad Hamzeh project repository

## Tech Stack
- **Backend**: Spring Boot, Spring MVC, Spring Data JPA, Spring Security
- **Frontend**: Thymeleaf, HTML, CSS, HTMX
- **Build**: Apache Maven
- **Database**: JPA/Hibernate ORM
- **Security**: BCrypt password encryption
- **Deployment**: Docker, CI/CD with GitHub Actions

## Current Project Status

### Completed Features
- **User Authentication**: Secure user registration and login with encrypted passwords


## How to Run the Application

### Prerequisites
- Git
- Java JDK 21
- Apache Maven
- Docker (optional, for containerized deployment)

### Option 1: Run Locally with Maven

1. **Clone the repository:**
   ```bash
   git clone https://github.com/JadHamzeh/resume.git
   cd perk-manager
   ```

2. **Build and Test:**
   ```bash
   ./mvnw clean install
   ```

3. **Run the application:**
   ```bash
   ./mvnw spring-boot:run
   ```
   
   Or run the JAR directly:
   ```bash
   java -jar target/perk-manager-0.0.1-SNAPSHOT.jar
   ```

4. **Access the application:**
   - Navigate to `http://localhost:8081`
   - Demo account: username `demo`, password `demo123`



## Development Workflow

### Testing
Run all tests with:
```bash
./mvnw test
```

**Live Application URL**: tbd




