# TestNG
## Assignment Task: Selenium TestNG
### Module: Test Scenarios
#### PROBLEM STATEMENT :Test the Lambdatest portal.
##### Member:Sripriya-R99
##### URL USED:
* The website used in this project is "https://www.lambdatest.com/selenium-playground".
#### DETAILED DESCRIPTION:
##### Pre-Conditions
* Use suitable Before*** annotation to launch a browser and the given URL: https://www.lambdatest.com/selenium-playground/.
* Pass Browser Name and URL from Test Suite XML.
* For all three given Test Scenarios, use the same URL.
* Use suitable After*** annotation to close the browser after each test scenario.
##### Test Scenario 1:
* Perform an explicit wait till the time all the elements in the DOM are available.
* Use the SoftAssert to validate Page Title. Validate Against “LambdaTest” (expecting a failure and proceeding to the following statement).
##### Test Scenario 2:
* Click “Checkbox Demo” under “Input Forms”.
* Click the checkbox under the “Single Checkbox Demo” section.
* Validate whether this checkbox is “selected”.
* Now click the checkbox again and validate whether the checkbox is “unselected”.
##### Test Scenario 3:
* Launch the same browser and URL given in the Pre-Condition.
* Click “Javascript Alerts” under “Alerts & Modals”.
* Now click the “Click Me” button in the “Java Script Alert Box” section.
* Validate the alert message “I am an alert box!” and click ok.
##### Tools and Plugins
* POM.xml
* Testng.xml
* LambdaTest platform
##### OUTPUTS:
#### Detailed console output
* We can see the testscenario status in lambdatest page under Automation->Builds
#### Output in Console of Eclipse
============Parallel Test Suite Total tests run: 12, Passes: 12, Failures: 0, Skips: 0============
