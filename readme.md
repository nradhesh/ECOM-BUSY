# ECOM-READY -- Springboot 

**ECOM-READY** is a full-stack e-commerce application. It consists of two main components:

1. **Backend**: Developed using Spring Boot with an H2 in-memory database for persistence.
2. **Frontend**: Built using React and styled with Bootstrap.

![alt text](<Screenshot 2024-12-27 171405.png>) ![alt text](<Screenshot 2024-12-27 171540.png>) ![alt text](<Screenshot 2024-12-27 171518.png>) ![alt text](<Screenshot 2024-12-27 171507.png>) ![alt text](<Screenshot 2024-12-27 171428.png>) ![alt text](<Screenshot 2024-12-27 171414.png>)


## Project Structure

```
ECOM-READY/
|-- ecom-frontend/    # Frontend React application
|-- ecom-backend/     # Backend Spring Boot application
```


---

## Backend: ecom-backend

### Technologies Used

- **Spring Boot**: Backend framework.
- **H2 Database**: In-memory database for persistence.
- **Hibernate**: ORM framework for database interaction.
- **Lombok**: Reduces boilerplate code.

### Prerequisites

- Java 17
- Maven

### Installation and Usage

1. Navigate to the `ecom-backend` folder:

   ```bash
   cd ecom-backend
   ```

2. Build and run the application:

   ```bash
   mvn spring-boot:run
   ```

3. The backend server will start on `http://localhost:8080/`.

4. The H2 console can be accessed at:

   ```
   http://localhost:8080/h2-console
   ```

   - **JDBC URL**: `jdbc:h2:mem:testdb`
   - **Username**: `sa`
   - **Password**: (leave blank)

### Default Database Configuration

- The application uses H2 as the default database.
- Hibernate is configured for automatic schema generation.

---
## Frontend: ecom-frontend

### Technologies Used

- **React**: Frontend library for building the user interface.
- **Bootstrap**: For styling and responsive design.
- **Vite**: Tool for fast development and building.
- **Axios**: For handling HTTP requests.
- **React Router DOM**: For routing.

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn package manager

### Installation and Usage

1. Navigate to the `ecom-frontend` folder:

   ```bash
   cd ecom-frontend
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm run dev
   ```

4. Build the application for production:

   ```bash
   npm run build
   ```

5. Preview the production build:

   ```bash
   npm run preview
   ```
---

## Key Scripts and Commands

### Frontend

- **Development**: `npm run dev`
- **Build**: `npm run build`
- **Preview**: `npm run preview`

### Backend

- **Run Application**: `mvn spring-boot:run`

---

## License

This project is licensed under the MIT License.