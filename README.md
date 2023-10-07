# automation-selenium-java-cucumber-herokuapp.com
This project contains automation tests written in Java using Selenium WebDriver, TestNG, and Cucumber for the website [the-internet.herokuapp.com](url) that will allow us to build a test framework that can be used by businesses to understand the test scenarios and as well can test the web application.

The project is structured as follows:

```
│ .idea    
├── src
│   ├── main
│   │   ├── java   
│   │   │   ├── pom
│   │   │   └── utils
│   │   └── resources
│   └── test
│       ├── java
│       │   ├── runners
│       │   └── steps
│       │       
│       └── resources
│	          └── features
│
├── .gitignore
├── pom.xml
└── README.md 
```

- The src directory contains the main source code and test code and it has two folders **src/main/java** and **src/test/java**.
- The **src/main/java** directory contains the com.herokuapp package where you can place any utility classes framework or page object model classes.
- The **src/test/java** directory contains the test classes where you'll write your test cases.
- The **src/test/resources/features** directory contains the test scenarios in the Feature file written in Gherkins language the Feature file should be saved as an extension of .feature.
- The **src/test/resources/testng.xml** file is the TestNG configuration file where you can configure your test suites, test groups, and other settings.
- The **.gitignore** file specifies which files and directories should be ignored by Git version control.

## Prerequisites
To run the automation tests in this project, you'll need to have the following software installed on your machine:

- Java Development Kit (JDK) 10 or higher
- Apache Maven
- Selenium WebDriver
- TestNG
- Cucumber Java
- Cucumber TestNG
