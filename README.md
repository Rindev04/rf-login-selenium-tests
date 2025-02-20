rf-login-selenium-tests
Robot Framework Login Tests

Automated testing suite for the login functionality of [Melivecode](https://melivecode.com) using Robot Framework and Selenium.


Features
- Automated testing for login functionality
- Utilizes Robot Framework with Selenium WebDriver
- Checks for both valid and invalid login scenarios
- Generates detailed reports and logs


Technology Stack
- Robot Framework - Test automation framework
- SeleniumLibrary - Web testing library for Robot Framework
- Python - Scripting language
- ChromeDriver - For browser automation


Prerequisites
Ensure you have the following installed:
- Python
- Robot Framework
- SeleniumLibrary
- ChromeDriver 

Project Structure
login_tests
valid_login.robot            # Test case for valid login
invalid_login.robot          # Test case for invalid login
resources keywords.robot     # Reusable keywords
output.xml                   # Test outputreport.html           
report.html                  # Test summary report
log.html                     # Detailed execution log
README.md                    # Project documentation


Test Cases Overview
1. Valid Login
Navigate to the login page
Enter valid credentials
Verify successful login and redirect to the profile page
2. Invalid Login
Navigate to the login page
Enter invalid credentials
Verify error message is displayed
