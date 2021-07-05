1. Create a API TestPlan:
	First we need to analyse the requirements to create a test plan which includes
		-The purpose of API testing and target application
		-The workflow of the application
		-The Features and functions of API
		-The functionalities covered by API testing
		-The functionalities covered by UI testing
		-Out of scope functionalities
		-Dependency from other teams or environment
		-Test Schedule
		-Test Enviornment set up
		-The areas that are priortized for this testing
		-Expected output
		-Expected codes for pass and fail tests
2. Make sure all the necessary enviornment is set up. 
3. Make sure you have enough postman license for the testing team
4. Make sure you have the right Docker configuration and its up and running
5. Verify you have the correct url
6. Confirm you have the right JSON body and correct field names, types and values
7. Check if you have the necessary header and permissions for the url
8. Write any pre requisite scripts needed for the tests
9. Make sure you have enough coverage for both positive and negative tests eg:  date within weekdays and date for weekend
10. Verify to have tests for the authorisation. Make sure to test with different user permissions
11. Make sure to set the vaules as an enviornment variables and use them in the tests
12. Make sure to cover the status code for 200, 201, 400, 404, 409  - depending the requirement.
13. Verify if the test returns the same status on multiple runs
14. Arrange the tests in an order to make sure there is no conflict or overriding results
15. Have a detailed tests to check the response body messages for both pass and fail
16. Raise neccesary defects and track the defects, make sure you have enough coverage for all the sceanrios
17. Verify the pipeline to make sure there is no failures, if so verify to confirm if its a test issue or code issue.
18. Once the necessary API testing is done, carry on with the UI testing for the functionalities. 
19. Make sure to cover both happy path and negative sceanrios for the Web testing . For eg: check the buttons to add the date and returns the right message
20. On finding defects, make sure to log the defects, track and once fixed, run a regression test to make sure nothing is broken
21. Make sure the most critical area are tested, for UI make sure to check the all the buttons, dialogs and alert messages
22. Perform Security testing to make sure the app is secured
23. Perform load testing to make sure it can handle heavy data load without crashing
24. Also cover Performance testing to make sure app behaves the same way even in N number of users lof in
25. Make sure all the hight priority bugs are fixed and closed
26. Check the pipeline and jenkin jobs to make sure there is no major failures

None of the product can be 100% tested but we can be confident in the product when we are sure that we have 95% of the coverage.

			
	