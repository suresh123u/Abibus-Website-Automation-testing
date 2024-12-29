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
1. Cucumber: For BDD implementation.
2. Selenium WebDriver: For browser automation.
3. WebDriverManager: For managing browser drivers dynamically.
4. Browser: Microsoft Edge
5. Key Selenium Features Used:
6. WebElement interactions (click, sendKeys, etc.)
7. Locators like XPath and ID.
8. Handling dynamic elements (lists and loops).
## Cucumber Annotations
1. @Given: To set up the initial state (e.g., opening the website).
2. @When: To define the user's actions (e.g., selecting cities, date, and seat).
3. @Then: To validate the final outcome (e.g., proceeding to payment).
## Improvements/Extensions
1. Error Handling: Add exception handling for possible errors like ElementClickInterceptedException or stale element references.
2. Dynamic Inputs: Enhance input handling for real-time data or parameterization through a configuration file.
3. Reporting: Integrate Cucumber reporting tools like Extent Reports for detailed test results.
4. Cross-Browser Testing: Extend compatibility to other browsers like Chrome and Firefox.
5. Data-Driven Testing: Use external data sources like Excel or JSON for dynamic test inputs.

##This project ensures an end-to-end automation of the bus ticket booking process, making it efficient, reliable, and user-friendly.
