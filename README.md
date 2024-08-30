
# CashCard Project

This project is part of this course https://spring.academy/courses/building-a-rest-api-with-spring-boot

These are all accomplishments I achieved doing this project:
- I’ve delved into REST and the lore of HTTP verbs: not just GET, but also PUT, PATCH, and POST.
- I've used HTTP response status codes as designed: not just 200 OK, but 204 NO CONTENT and 201 CREATED as well.
- By using Spring Boot, I’ve now got a solid understanding of Spring. I learned about its Inversion of Control container, how to use annotations, and how to employ auto-configuration to free me from configuration tasks.
- I built the API using a layered architecture. I understand how Spring Security sits at the “front” of the API, Spring Web enables HTTP communications between the API and its clients, and Spring Data handles reading and writing to/from the relational data store.
- I used a test-first approach to provide confidence that my application works as designed while driving out my app's functionality.
- I drove my implementation using a Steel Thread - exercising all the integration points and validating my architecture early on to de-risk my functionality.
- I used the Red, Green, Refactor process to improve my code (and tests!) throughout the application development.


## Prerequisites

Before you begin, ensure you have met the following requirements:

- **Java Development Kit (JDK) 17 or later**  
  Ensure that you have JDK 17 installed on your machine. You can check your version by running:
  ```bash
  java -version
  ```

- **Gradle**  
  The project uses the Gradle Wrapper, so you do not need to install Gradle globally. You can build and run the project using the provided wrapper scripts (`./gradlew` for Linux/Mac, `gradlew.bat` for Windows).

- **Git**  
  Git is required to clone the repository. Ensure you have it installed and configured.

## Installation

1. **Clone the Repository**

   Clone the project from GitHub to your local machine using the following command:

   ```bash
   git clone https://github.com/henriMacedoGoncalves/cashcard.git
   cd cashcard
   ```

2. **Build the Project**

   Use the Gradle Wrapper to build the project and download all dependencies:

   ```bash
   ./gradlew build
   ```

3. **Run the tests**

   Start testing with the following command:

   ```bash
   ./gradlew test
   ```
   
  Test results will be displayed in the console. The configuration for test logging can be adjusted in the `build.gradle` file under the `test` block.

## Project Structure

- **Java Toolchain**  
  The project uses Java 17, configured in the `build.gradle` file.

- **Dependencies**
  - `spring-boot-starter-web`: Starter for building web, including RESTful, applications using Spring MVC.
  - `spring-boot-starter-security`: Provides security features such as authentication and authorization.
  - `spring-data-jdbc`: Simplified database interaction using Spring Data JDBC.
  - `h2`: In-memory database for development and testing.
  - `spring-boot-starter-test`: Testing support including JUnit and Mockito.
  - `junit-platform-launcher`: JUnit platform launcher for running tests.

## Contributing

If you want to contribute to this project:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

This `README.md` provides a clear overview of the project, including setup instructions, a brief description of the project's structure, and additional helpful details. You can adjust this template based on any specific features or details unique to your project.
