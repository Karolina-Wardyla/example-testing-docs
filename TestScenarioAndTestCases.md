> # **TEST SCENARIO AND TEST CASES**

&nbsp;

**Demo site URL:** [Mercury Tours](http://newtours.demoaut.com/mercurywelcome.php)

**Project Name:** Mercury Tours

**Module Name:** Sign-On

**Created By:** Karolina Wardyla

**Creation Date:** 10/02/2019

**Reviewed By:** P.Z.

**Review Date:** 11/02/2019

&nbsp;

**_Tab.1 Test Scenario TS_MT_SignOn_001 to verify the sign-on functionality of the Mercury Tours page_**

| Test Case ID | Test Case Description | Test Steps | Preconditions | Test Data | Expected Result |
| --- | --- | --- | --- | --- | --- |
| TC_MT_SignOn_001 | Enter a valid user name & password | 1. Enter valid user name <br/> 2. Enter valid password <br/> 3. Click on Submit button | Valid URL <br/> Test Data | User Name: Kalusia Password: P@ssw0rd | Successful sign-on. |
| TC_MT_SignOn_002 | Enter a valid user name & invalid password | 1. Enter valid user name <br/> 2. Enter invalid password <br/> 3. Click on Submit button | Valid URL <br/> Test Data | User Name: Kalusia Password: password | 1. User is not signed-on. <br/> 2. Message "Invalid user name/password" is displayed. |
| TC_MT_SignOn_003 | Enter an invalid user name & valid password | 1. Enter invalid user name <br/> 2. Enter valid password <br/> 3. Click on Submit button | Valid URL <br/> Test Data | User Name: Andrez10a Password: P@ssw0rd | 1. User is not signed-on. <br/> 2. Message "Invalid user name/password" is displayed. |
| TC_MT_SignOn_004 | Enter an invalid user name & invalid password | 1. Enter invalid user name <br/> 2. Enter invalid password <br/> 3. Click on Submit button | Valid URL <br/> Test Data | User Name: Andrez10a Password: password | 1. User is not signed-on. <br/> 2. Message "Invalid user name/password" is displayed. |                                             