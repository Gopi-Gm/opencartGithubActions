# OpenCart Automation Project

This project provides automated testing and integration for OpenCart using Java, Maven, and TestNG.

## Prerequisites

- Java 8 or higher
- Maven
- (Optional) Docker (if using Dockerfile in the project)

## Getting Started

1. **Clone the repository:**  
   ```
   git clone <your-github-repo-url>
   cd opencartGithubActions
   ```

2. **Install dependencies:**  
   ```
   mvn clean install
   ```

3. **Run Tests:**  
   ```
   mvn test
   ```

## Project Structure

- `src/` – Source code
- `testData/` – Test data files
- `reports/` – Test reports output
- `screenshots/` – Screenshots from test runs
- `.github/` – GitHub Actions/CI configuration
- `Dockerfile` – For Dockerized runs

## Continuous Integration

This project is set up with GitHub Actions in the `.github/` directory for CI/CD.

## License

Specify your license here (e.g., MIT, Apache 2.0).

