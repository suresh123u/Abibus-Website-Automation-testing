# Abibus-Website-Automation-testing

## Project Description: Bus Ticket Booking Automation Using Selenium and Cucumber

This project automates the process of booking bus tickets on the Abhibus website using Selenium WebDriver with the Edge browser. The testing framework is implemented using Cucumber, which allows for behavior-driven development (BDD) with Gherkin syntax.

## Key Functionalities Automated
### Website Navigation:

1. Opens the Abhibus website.
Maximizes the browser window to enhance user experience.
Journey Details Input:

2. Allows the user to input the origin and destination cities dynamically.
Selects a specific travel date, such as "Tomorrow."
Filters and Bus Selection:

3. Filters buses based on a "Price Drop" checkbox.
Dynamically selects three bus partners from the list of available options.
Seat Selection:

4. Automates the "Show Seats" button click and dynamically selects a seat by its identifier (e.g., "5U").
Pickup and Drop Points:

5. Automates the selection of boarding and dropping points.
### Payment Process:

Proceeds to the payment page, ensuring all prerequisites are completed.
## Technical Details
Programming Language: Java
## Frameworks and Tools:
Cucumber: For BDD implementation.
Selenium WebDriver: For browser automation.
WebDriverManager: For managing browser drivers dynamically.
Browser: Microsoft Edge
Key Selenium Features Used:
WebElement interactions (click, sendKeys, etc.)
Locators like XPath and ID.
Handling dynamic elements (lists and loops).
Cucumber Annotations
@Given: To set up the initial state (e.g., opening the website).
@When: To define the user's actions (e.g., selecting cities, date, and seat).
@Then: To validate the final outcome (e.g., proceeding to payment).
Improvements/Extensions
Error Handling: Add exception handling for possible errors like ElementClickInterceptedException or stale element references.
Dynamic Inputs: Enhance input handling for real-time data or parameterization through a configuration file.
Reporting: Integrate Cucumber reporting tools like Extent Reports for detailed test results.
Cross-Browser Testing: Extend compatibility to other browsers like Chrome and Firefox.
Data-Driven Testing: Use external data sources like Excel or JSON for dynamic test inputs.
This project ensures an end-to-end automation of the bus ticket booking process, making it efficient, reliable, and user-friendly.
