# Internship Backend

Spring Boot (Java 21, Maven) + PostgreSQL REST backend.

## Requirements
- Java 21
- Maven (or use the included `mvnw`)
- PostgreSQL

## Setup
1. Clone the repo:
   ```bash
   git clone https://github.com/Suman748/internship-backend.git
   cd internship-backend
   ```
2. Create the database:
   ```bash
   createdb -U postgres internship_db
   ```
3. Run the app (replace the value with your own PostgreSQL password):
   ```bash
   DB_PASSWORD=yourpostgrespassword ./mvnw spring-boot:run
   ```
4. Open http://localhost:8080. A "Whitelabel Error Page" (404) means the server is running, because no endpoints exist yet.

## Configuration
Database settings are in `src/main/resources/application.properties`. The password is read from the `DB_PASSWORD` environment variable.

## Stop
Press `Ctrl+C` in the terminal.
