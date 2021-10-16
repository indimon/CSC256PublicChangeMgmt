---
name: Bug report
about: Create a report to help us improve
title: 'Bug 2'
labels: 'n/a'
assignees: 'India Rowe'

---

**Describe the bug**
When running full_retirement_age_calculator_app.py and are asked to “Enter the year of birth”, the year is entered incorrectly with a space somewhere within the numbers.
Ex. Instead of “1992”, you enter “19 92”.


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
2.	After being asked “Enter the year of birth or <enter> to exit” input a year (with integers), but add a space somewhere within the integers
3.	Click enter and see the errors


**Expected behavior**
For this test I would expect that if I entered in any incorrect spaces within years, the code would read this and tell me that I entered the number incorrectly and ask me to enter it again. Ideally, the code would even read the space within the integers and erase the empty space and read the code normally, however, the earlier suggestion would be easier to code in, I believe.


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


**Comment**
Fix completed