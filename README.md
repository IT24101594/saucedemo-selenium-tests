# Sauce Demo – Selenium Test Automation

Automated UI tests for the login page of [saucedemo.com](https://www.saucedemo.com), built with **Selenium WebDriver**, **Java** and **TestNG** using the **Page Object Model (POM)**.

## Tools & Technologies
- Java 21
- Selenium WebDriver 4
- TestNG
- Maven
- IntelliJ IDEA

## Project Structure
| File | Purpose |
|------|---------|
| `src/test/java/LoginPage.java` | Page object: login page locators and actions |
| `src/test/java/LoginTest.java` | Test cases |
| `pom.xml` | Maven dependencies (Selenium, TestNG) |

## Test Cases
| ID | Test | Type | Result |
|----|------|------|--------|
| TC_LOGIN_001 | Valid login opens the Products page | Positive | ✅ Pass |
| TC_LOGIN_002 | Wrong password shows an error message | Negative | ✅ Pass |
| TC_LOGIN_004 | Empty username shows "Username is required" | Negative | ✅ Pass |

## How to Run
1. Clone this repository
2. Open it in IntelliJ IDEA as a Maven project
3. Wait for Maven to download the dependencies
4. Right-click `LoginTest.java` → **Run 'LoginTest'**

Chrome opens automatically and runs the tests. Selenium Manager downloads the correct ChromeDriver.

## Result
All 3 tests passed.

## What I Learned
- Designing positive and negative test cases
- Using locators (id, cssSelector, className) and explicit waits
- Writing assertions with TestNG
- Structuring tests with the Page Object Model so locators are kept in one place

## Author
**Hasali Perera**, IT undergraduate at SLIIT  
[LinkedIn](https://linkedin.com/in/hasali-perera) · [GitHub](https://github.com/IT24101594)
