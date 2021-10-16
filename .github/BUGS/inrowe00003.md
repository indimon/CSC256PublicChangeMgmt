---
name: Bug report
about: Create a report to help us improve
title: 'Bug 3'
labels: 'bug'
assignees: 'India Rowe'

---

**Describe the bug**
When running full_retirement_age_calculator_app.py and are asked to “Enter the year of birth”, integers are entered, however, a special character is added to the input.
Ex. Instead of “1992”, you enter “$1992”.


**Program**
https://github.com/wtccjava/CSC256PublicChangeDoc
Date: September 29, 2021
Time: 2:28:24 PM


**Component**
full_retirement_age_calculator_app.py


**Error Type**
Coding error, since the code doesn’t accommodate for inputs that aren’t correct numbers


**Severity**
Minor Nuisance


**Priority**
TBD


**State**
Open


**To Reproduce**
Steps to reproduce the behavior:
1.	Run full_retirement_age_calculator_app.py
2.	After being asked “Enter the year of birth or <enter> to exit” input a year (with integers), but add special characters into the integer.
3.	FYI - Integers don’t even have to be added to get this error, the special characters being added by themselves also gives the same error.
4.	Click enter and see the errors


**Expected behavior**
For this test I expect that if I enter in special characters when being asked a question that wouldn’t expect special characters in the answer, that I would be given some sort of error message. However, it would be better if the code read those and noticed they weren’t numbers, and asked you to enter your input again instead of going straight to an error message.


**Screenshots**
If applicable, add screenshots to help explain your problem.


**Desktop (please complete the following information):**
Please complete the following information:
-	OS: Windows 10
-	Browser: Firefox
-	Version: 92.0.1 (64 bit)


**Additional context**
Add any other context about the problem here.


**Assigned**
Unassigned


**Defect Type**
For ODC later.  
One of
* Interface
* Function
* Build/Package/Merge
* Assignment
* Documentation
* Checking
* Algorithm
* Timing/Serialization


**Defect Trigger**
For ODC later.
One of
* Review and Inspection Triggers
* Unit and Function Test Triggers
* System and Field Test Triggers


**Defect Impact**
For ODC later.
One of
* Capability
* Usability
* Performance
* Reliability
* Installability
* Maintainability
* Documentation
* Migration
* Standards
* Integrity/Security
