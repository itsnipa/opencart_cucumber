# Web Automation Using Cucumber & TestNG

This is a web automation project on ``Opencart`` using cucumber in java.

## About the project

This project explores Cucumber as a Web Automation tool. I have automated some feature. Such as- `Login`,`Registration`,`search`,`add to cart`. The projects showcase automation script development and utilize reporters in **HTML**. Additionally, it offers the ability to capture screenshots for tests and generate error shots for failed test cases.

`` PS:I am still working on this project.``

## Installation & Prerequisites

1. JDK 1.8+ (Ensure that the Java class path is properly set)
2. Maven (Ensure that the .m2 class path is properly set)
3. Eclipse IDE
4. Required Eclipse Plugins:
      * Maven
      * Cucumber
5. Browser driver (Ensure that you have the appropriate browser driver for your desired browser and that the class path is correctly configured) 


## Framework Setup

To set up the framework, you can either fork or clone the repository from [here](https://github.com/itsnipa/opencart_cucumber.git) , or download the ZIP file and set it up in your local workspace.


## Running Sample Tests

Access the CLI of your operating system (e.g., iTerm for macOS or PowerShell for Windows) and navigate to the project directory. Then, run the following command to execute the features:
`` mvn clean test`` . By default, this command will invoke default browser and execute the tests.

   * To run features on a specific browser, use the command: ``mvn test "-Dbrowser=browser_name"``. Replace ``browser_name`` with one of the following options: **Firefox**, **Chrome**, **Safari**, etc. Ensure that the browser's driver files are present and specified in the system variables. // Need to find out if Internet Explorer is supported or this should be updated to Edge, then update details around IE to Edge.

Please note that browser drivers are not included as part of this framework. The reason for this is that the version of Selenium browser drivers varies based on the browser version you are using, as well as the Selenium server version.

   * To run a specific feature file among multiple feature files, use the command: ``mvn test -Dcucumber.options="classpath:features/Registration.feature"``
### Test Report pictures


## Reporters

Once you have run your tests, you can generate various types of reports. This ``selenium-cucumber-java`` framework utilizes different test reporters to communicate pass/failure information.


## Reporting

Cucumber Report

![image](https://github.com/user-attachments/assets/2d38bcb4-534a-44b0-8040-a47af87ccdf2)


![image](https://github.com/user-attachments/assets/8a18c0be-3414-4e8e-b1c5-154d825d443c)


Test Output Report

![image](https://github.com/user-attachments/assets/6f0cca41-6b74-42ae-8737-f6dca12fe55e)
