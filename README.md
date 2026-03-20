# backendVideoclub

A small Java backend application for movie rental/store management with a clean MVC-style package structure.

## 🚀 Overview

- Java (JDK 11+ recommended)
- Maven build system
- Manual repository implementation (no Spring)
- Organized in packages: `model`, `repository`, `controller`, `view`, `config`

## 📁 Project Structure

- `src/main/java/org/factoria/`
  - `Main.java`
  - `config/DBManager.java`
  - `controller/MovieController.java`
  - `model/Movie.java`
  - `repository/MovieRepository.java`, `MovieRepositoryImpl.java`
  - `view/MovieView.java`
- `src/main/resources/` for app resources
- `src/test/java/` for tests

## 🛠️ Getting Started

1. Clone the repository:
   ```bash
   git clone <your-repo-url>
   cd backendVideoclub
   ```
2. Build project:
   ```bash
   mvn clean install
   ```
3. Run the app:
   ```bash
   mvn exec:java -Dexec.mainClass="org.factoria.Main"
   ```
4. Run tests:
   ```bash
   mvn test
   ```

## ✅ Features

- Movie entity with title, genre, year and other fields
- Repository interface + implementation for data operations
- Controller for business logic and flow
- View layer for output
- DB connection config via `DBManager`

## 🧩 Customize

- Update `DBManager` with your JDBC connection settings
- Add more operations in controllers and repository
- Add unit/integration tests

## 📄 License

 CC BY 
