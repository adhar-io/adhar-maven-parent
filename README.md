# adhar-maven-parent
> Maven parent for Adhar Platform applications and services

## Basic Details
This project serves as the Maven parent for all Adhar Platform applications and services. It provides common configurations and dependencies to streamline the development process.

## Prerequisites
- Java 17 or higher
- Maven 3.9.0 or higher

## Getting Started
To get started with this project, follow these steps:

1. **Clone the repository:**
   ```sh
   git clone <repository-url>
   cd adhar-maven-parent
   ```
2. Build the project:
   ```sh
   mvn clean install
   ```
3. Add the following to your project's `pom.xml` file:
   ```xml
    <parent>
         <groupId>com.adhar</groupId>
         <artifactId>adhar-maven-parent</artifactId>
         <version>1.0.0</version>
    </parent>
    ```
4. Run your Maven project:
   ```sh
   mvn clean package
   ```

## Contributing
Please read CONTRIBUTING.md for details on our code of conduct, and the process for submitting pull requests.  

## License
This project is licensed under the MIT License - see the LICENSE file for details. 