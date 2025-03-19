# Simple Web Project

This is a simple web project that demonstrates the use of JSP and Servlets in a Java web application.

## Project Structure

```
simple-web-project
├── src
│   ├── main
│   │   ├── webapp
│   │   │   └── index.jsp
│   │   └── java
│   │       └── com
│   │           └── example
│   │               └── HelloWorldServlet.java
├── pom.xml
└── README.md
```

## Requirements

- Java Development Kit (JDK)
- Apache Maven

## Building the Project

To build the project, navigate to the root directory of the project and run the following command:

```
mvn clean install
```

## Running the Application

After building the project, you can run the application on a servlet container like Apache Tomcat. 

1. Deploy the generated `.war` file located in the `target` directory to your servlet container.
2. Access the application in your web browser at `http://localhost:8080/simple-web-project`.

## Features

- A simple JSP page (`index.jsp`) that serves as the main entry point of the application.
- A servlet (`HelloWorldServlet.java`) that handles GET requests and returns a simple message.

## License

This project is licensed under the MIT License.