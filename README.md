# Mini-Project-24-Software-Test
In this mini-project, you’ll create a test plan, test cases, and test cycles to ensure that an application is secure enough to be deployed for a large oil and gas field services firm. You’ll think "outside the box" to identify, assess, and remediate risks that are not always technical. Have the Corporate Information Security Risk Matrix, on hand below, to work on this project.




Create a test plan for testing this application


CIS7-9	 information security alteration privileges are limited to appropriate personnel. 
test cases
Attempt to alter inaccessible information from consoles without the proper privileges
test cycles
Monthly
Difference 
CIS7 for Unix (Solaris and AIX) environments
CIS8 for Oracle databases
CIS9 for SQL Servers
CIS18 	authenticated the identity of users through passwords or other authentication mechanisms (including policies, confidentiality, and passwords)
test cases
Run necessary scripts on each server to ensure all bellow data is verified:
PASSWORD_LIFE_TIME
PASSWORD_REUSE_TIME
PASSWORD_REUSE_MAX
PASSWORD_LOCK_TIME
FAILED_LOGIN_ATTEMPTS
test cycles
automated
CIS36 	limit privileged access  ("super user") to appropriate personnel
test cases
Obtain and document a list of users on each Oracle server
Run necessary script on all Oracle servers to better examine list of users and object privileges
Review with Risk Services Manager
test cycles
Quarterly

Risk Register Template.xlsx - Google Sheets
