# Automated testing example project setup using: Gradle, TestNG & Selenium

Requirements: 
- apt install default-jre
- apt install gradle

To build the project:
- gradle build

Run all tests:
- gradle clean test

Run example tests with task definitions:
- gradle clean smokeTests
- gradle regressionsTests
- gradle suiteTest

Reports are generated and placed in:
- /build/reports/tests/
