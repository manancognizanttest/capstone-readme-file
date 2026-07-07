Component 2: Test Cases (Written Document)
Write a minimum of 15 formal test cases covering both the API layer and the UI layer. Your test cases must:

Use the standard template with ID, title, testing level, test type, preconditions, steps, expected result, actual result, and status
Cover at least five API test scenarios including GET, POST, and error handling
Cover at least five UI test scenarios including form interactions and validation
Cover at least two accessibility test scenarios using keyboard navigation or contrast checking
Cover at least two cross-device or cross-browser scenarios
Include at least one negative test case for each layer
Organize your test cases in a document called test_cases.txt or a spreadsheet.

Component 3: Automated API Test Suite (Java or Python)
Build an automated API test suite that covers the JSONPlaceholder /posts endpoint. Your suite must:

Contain a minimum of eight automated test cases
Cover GET, POST, PUT, and DELETE operations
Include at least one negative test case (404 scenario)
Include at least one chained request test
Use either REST Assured in Java with JUnit or the Python requests library with pytest
All tests must pass when run
Include a README.md in the project folder explaining how to run the tests
Component 4: Automated UI Test Suite (Java with Selenium)
Build an automated UI test suite for the Selenium practice web form. Your suite must:

Contain a minimum of five automated test cases
Use the Page Object Model design pattern with at least one page class
Use explicit waits and not Thread.sleep
Take at least one screenshot during the test run
Include at least one assertion that verifies element state
All tests must pass when run
Use the same Maven project as your API suite or a separate project
Component 5: BDD Feature File (Cucumber or Behave)
Write a BDD feature file that describes the behavior of at least one feature from either the API or UI layer. Your feature file must:

Contain at least one regular Scenario with Given When Then steps
Contain at least one Scenario Outline with an Examples table covering at least three data rows
Use at least one tag
Have matching step definitions that execute successfully
The scenarios must actually run and pass

Component 8: Load Test Results (JMeter)
Run a JMeter load test against the JSONPlaceholder GET /posts endpoint and include:

The saved JMX test plan file
The CLI run terminal screenshot
The HTML report dashboard screenshot
A three to five sentence summary of the load test findings in your execution summary
Component 9: Accessibility Testing Evidence
Perform accessibility testing on the Selenium practice web form and document:

Keyboard navigation test results covering at least five keyboard interactions
A colour contrast observation noting at least one element and its estimated contrast level
At least two WCAG 2.2 success criteria that apply to the form and whether the form passes or fails each one
Document this in your test execution summary or as a separate accessibility_findings.txt file.