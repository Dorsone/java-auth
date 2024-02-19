# Java API Auth

## Information

The purpose of this project is the basic authentication using ```JWT``` technology and <br>
it can be used for any other project and can be customized. For api documentation we used <br>
the ```OpenApi``` automated documentation generator

## Installation
Follow these steps to install and run the Java Spring Maven project from the provided GitHub URL. Ensure you have Git, Java, and Maven installed on your machine before proceeding.

### 1. Clone the GitHub Repository

Open a terminal or command prompt and execute the following command to clone the repository to your local machine:

```bash
git clone https://github.com/Dorsone/java-auth.git
```

### 2. Navigate to the Project Directory
Change into the project directory with this command:

```bash
cd java-auth
```

### 3. Build the Project with Maven
Build the project using Maven to compile the project and download all necessary dependencies:

```bash
mvn clean install
```
To compile the project without running tests (to save time), use:

```bash
mvn clean install -DskipTests
```

### 4. Run the Application
If it's a Spring Boot application, start it using the following Maven command:

```bash
mvn spring-boot:run
```
This command launches the Spring Boot application, which includes running an embedded web server, making the application accessible through a web browser.

### 5. Access the Application
Once the application is up, open a web browser and navigate to http://localhost:8080 to access the application (unless the project specifies a different port).
