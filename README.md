# my-test-repo

A Kotlin Spring Boot application.

## Technologies

- **Kotlin** 1.9.22
- **Spring Boot** 3.2.2
- **Java** 17
- **Gradle** (Kotlin DSL)

## Project Structure

```
my-test-repo/
├── src/
│   ├── main/
│   │   ├── kotlin/
│   │   │   └── com/example/mytestrepository/
│   │   │       ├── MyTestRepoApplication.kt
│   │   │       └── HelloController.kt
│   │   └── resources/
│   │       └── application.properties
│   └── test/
│       └── kotlin/
│           └── com/example/mytestrepository/
│               ├── MyTestRepoApplicationTests.kt
│               └── HelloControllerTest.kt
├── build.gradle.kts
└── settings.gradle.kts
```

## Getting Started

### Prerequisites

- Java 17 or higher
- Gradle (or use the included Gradle wrapper)

### Build the Project

```bash
./gradlew build
```

### Run the Application

```bash
./gradlew bootRun
```

The application will start on `http://localhost:8080`

### Run Tests

```bash
./gradlew test
```

## API Endpoints

- `GET /` - Returns a hello message