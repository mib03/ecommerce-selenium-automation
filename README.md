# Ecommerce Selenium Automation

End-to-end automation testing project for an ecommerce application using Selenium WebDriver and Java.  
This project demonstrates a scalable automation framework with Page Object Model and reusable components.

## Tech Stack

- Java
- Selenium WebDriver
- TestNG
- Maven
- Page Object Model (POM)
- Extent Reports

## Features

- Login validation (positive & negative scenarios)
- Product catalog interaction
- Add to cart
- Checkout process
- Order confirmation
- HTML test reporting

## Test Coverage

- User can login with valid credentials
- User cannot login with invalid credentials
- User cannot login with empty fields
- User can add product to cart
- User can complete checkout process
- User can verify order in order history

## Project Structure

src/
├── main/java/rahulshettyacademy
│   ├── AbstractComponents
│   ├── PageObjects
│   └── Resources
│
├── test/java
│   └── cucumber
│
reports/
test-output/
target/

## How to Run

mvn clean install  
mvn test  

## Reporting

Extent Report is generated after test execution.

Default location:
reports/

## Notes

- Uses Page Object Model for better maintainability
- Common reusable methods are placed in AbstractComponents
- Designed for scalable automation framework

## Related Project

This project has a Playwright version with the same test flow:

ecommerce-playwright-automation
