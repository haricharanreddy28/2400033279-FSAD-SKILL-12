# SKILL 12 - Full-Stack CRUD Application using React & Spring Boot
## KL University | FSAD Course

### Project Structure
```
skill12/
├── backend/    → Spring Boot REST API
└── frontend/   → React Application
```

### Backend Setup
1. Navigate to `backend/`
2. Run: `mvn spring-boot:run`
3. API runs at: http://localhost:8080

### Frontend Setup
1. Navigate to `frontend/`
2. Run: `npm install`
3. Run: `npm start`
4. App runs at: http://localhost:3000

### API Endpoints
| Method | Endpoint          | Description          |
|--------|-------------------|----------------------|
| POST   | /students         | Add a new student    |
| GET    | /students         | Get all students     |
| GET    | /students/{id}    | Get student by ID    |
| PUT    | /students/{id}    | Update student       |
| DELETE | /students/{id}    | Delete student       |

### H2 Console
- URL: http://localhost:8080/h2-console
- JDBC URL: jdbc:h2:mem:studentdb
