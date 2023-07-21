# Simple-calculator
A basic calculator which provides common four types of operation based on the request
This repository contains a simple Java application called "Calculator" that performs basic arithmetic operations (addition, subtraction, multiplication, and division) on two numbers. The application is implemented using the Spring framework to manage the Calculator bean.

Features
Addition: Calculates the sum of two numbers.
Subtraction: Calculates the difference between two numbers.
Multiplication: Calculates the product of two numbers.
Division: Calculates the quotient of two numbers. Handles division by zero by throwing an exception with an appropriate error message.
prerequisites
Before running the application, ensure you have the following installed on your system:

Java Development Kit (JDK): To compile and run Java code.
Apache Maven (optional): If you prefer usi
ng Maven for managing dependencies and building the project.

How to Run
Clone the repository to your local machine
Navigate to the project directory
if you have a compiler use it to run the preferred jdk 11
if not above method 
you can compile and run the program if your system has jdk alone
Compile the Java files:

If you're using Maven
mvn compile
to run
mvn exec:java -Dexec.mainClass="MainApp"
