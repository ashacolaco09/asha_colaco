scenario 1 : verify if the application is launching if yes test is passed.
verify if application itself is not launching log a defect for the same in jira
verify if application has launched sucessfully and user is able to see - login screen with user name and password entries and login button is displayed. if yes test is passed
verify if either of the fields are not available log a defect for the same


Scenario 2: verify user is able to fill details in user name and password and then click on login( this field should be editable and user should be able to fill the information as per the pre-requiste).if yes pass the test case.
verify only after filling the right details user is able to click on the login button.
verify after filling the wrong details an error to rectify the details is poupulated. Eg: Invalid user name
verify user should not be landed to news screen till the point all validation are successfull

Scenario 3 - user login succeed with correct credentails
verify user should be landed to the news screen
verify if user is not landed to the news screen page or else if the news screen page appears blank log a bug for the same.

Scenario 4 - user opens app next time (when previously logged in)
verify application is launching correctly and user is taken directly to the news screen. if yes test is passed.
verify if login details are asked again. log a defect for the same.
verify while lauching session time out issue doesnot appear if it appears log a bug for the same.


Scenario 1 - news images are loaded
verify the user successfully logged in to the app and there is internet connection
verify images are displayed in the rows on the list if not raise a defect for the same.


Scenario 2 - failed to load images
verify the user successfully logged in to the app and there is no internet connection image will not load
verify if “failed to load news” error message should be displayed and Retry button should be provided.
verify when clicked on retry and internet is available news should load.


Scenario 3 - news image is clicked
verify when the news images are successfully loaded on the screen
verify the user is able to clicks one of the image
verify if user is navigated to the external browser with clicked image loaded.

Note: If neither of test fails a defect should be raised for the same.


Example of raising a Bug:
Bug ID:123
Description:user is asked to into creadentials even when previously logged in.
Test data: user name and password
Assigned to:name of the person
filed against:Team
creation date:1/11/201
arefacts:attach the artifacts.
priority:high
severity:high

