# Ecommerce Selenium Automation

Automation testing project for ecommerce flow using Selenium WebDriver with Java.  
This project covers end-to-end user scenarios and demonstrates implementation of Page Object Model and data-driven testing.

## Tech Stack

- Java
- Selenium WebDriver
- TestNG
- Page Object Model (POM)
- Data Driven Testing (JSON / Excel)

## Features

- Login functionality (positive & negative scenarios)
- Add product to cart
- Checkout process
- Order validation
- End-to-end purchase flow

## Test Scenarios

- User can login with valid credentials
- User cannot login with invalid credentials
- User cannot login with empty fields
- User can add product to cart
- User can complete checkout process successfully


## How to Run

# install dependencies
mvn clean install

# run test
mvn test

## Notes
This project focuses on building a maintainable test automation framework using Selenium.
For comparison with Playwright implementation, check ecommerce-playwright-automation repository.

## Why Selenium vs Playwright?

This project is part of a comparison between Selenium and Playwright implementation for the same application flow, to understand differences in:

- Execution speed
- Stability (flaky test handling)
- Code simplicity
- Locator strategy
