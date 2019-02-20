> # **TEST EXECUTION REPORT**

## *Project Info:*

**Project ID:** 0001

**Project name:** Mercury Tours

**System's version:** 011003-1.01-058

**Date of release:** 30/06/2019

**Author of Report:** Karolina Wardyla

**Date of Test Scenario (TS_MT_SignOn_001) execution:** 11/02/2019

**Test Scenario TS_MT_SignOn_001 inludes Test Cases:** TC_MT_SignOn_001 to TC_MT_SignOn_004

**Date of Report creation:** 12/02/2019

## *Testing Scope:*

Sign-On module

## *Test Environment & Tools:*

**Application URL:** http://newtours.demoaut.com/mercurywelcome.php

**Operating system:** Windows 7 Professional

**Browser:** Opera 58.0.3135.53

&nbsp;

## *Conclusions:*

**_Tab.2 Results of executed test cases_**

| Test Case ID | Actual Result | Status | Executed By | Executed Date | Comments (if any) |
| --- | --- | --- | --- | --- | --- |
| TC_MT_SignOn_001 | Successful sign-on. | Pass | Tester_K.W. | 11/02/2019 | No comments. |
| TC_MT_SignOn_002 | 1. User is not able to sign-on (correct). <br/> 2. No message is displayed (incorrect). | Fail | Tester_K.W. | 11/02/2019 | "Invalid user name/password" message should be implemented. See BUG REPORT (BR_0001) |
| TC_MT_SignOn_003 | 1. User is not able to sign-on (correct). <br/> 2. No message is displayed (incorrect). | Fail | Tester_K.W. | 11/02/2019 | "Invalid user name/password" message should be implemented. See BUG REPORT (BR_0001) |
| TC_MT_SignOn_004 | 1. User is not able to sign-on (correct). <br/> 2. No message is displayed (incorrect). | Fail | Tester_K.W. | 11/02/2019 | "Invalid user name/password" message should be implemented. See BUG REPORT (BR_0001) |

&nbsp;

**_Tab.3 Conclusion of test cases planned and executed_**

| Test Cases planned | Test Cases executed | TCs passed | TCs failed |
|:------------------:|:-------------------:|:----------:|:----------:|
|          4         |          4          |      1     |      3     |

&nbsp;

> *In my work I made an assumption that a displayed message is one of the business requirements and should be implemented in the system. After execution of 4 test cases which were written to check Sign-On functionality, 1 has passed and 3 have failed. The reason of that is a lack of message which should be implemented in this module in a case when User enters invalid name or/and password or leaves these two fields blank. The “Invalid user name/password” message would help to reduce a risk of bad user experience and minimalize a risk of credentials theft.*

