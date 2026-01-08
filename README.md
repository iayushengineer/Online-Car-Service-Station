# Online Car Service Station

This repository contains the backend and frontend for the Online Car Service Station project.

## Repository structure

- `project-online-car-service-station-master-car-service-backend/`
  - `car-service-backend/` — Spring Boot backend (Maven)
- `project-online-car-service-station-master-car-service-frontend/`
  - `car-service-frontend/` — React frontend (npm)

## Getting started

### Backend (Java / Spring Boot)

1. Open a terminal and change directory:

   ```bash
   cd project-online-car-service-station-master-car-service-backend/car-service-backend
   ```

2. Run with the included Maven wrapper:

   ```bash
   ./mvnw spring-boot:run
   ```

3. Build the project:

   ```bash
   ./mvnw package
   ```

4. Run tests:

   ```bash
   ./mvnw test
   ```

Configuration for the backend (database, ports, etc.) is located in `src/main/resources/application.properties`.

### Frontend (Node / React)

1. Open a terminal and change directory:

   ```bash
   cd project-online-car-service-station-master-car-service-frontend/car-service-frontend
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Run the development server:

   ```bash
   npm start
   ```

4. Build for production:

   ```bash
   npm run build
   ```

## Contributing

- Please open issues for bugs or feature requests.
- Feel free to submit pull requests; follow standard GitHub flow (branch, PR, review).

## License

This project currently does not include a license file. Add a `LICENSE` if you want to define usage rights.

---

*Created and pushed by GitHub Copilot.*