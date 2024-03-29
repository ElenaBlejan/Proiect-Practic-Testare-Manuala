#  <h1 align="center"> Final Project for ITF Manual Testing Course <h1>
# OrangeHRM Project

# 1.*Introduction* 
This test plan describes the strategies, process, workflows and methodologies used to plan, organize, execute and manage testing process for OrangeHRM browser application, **PIM** module, Submenu Add Employee -Personal details. 

## 1.1 Project Objective

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application. 

Application under test: [OrangeHRM](https://opensource-demo.orangehrmlive.com/web/index.php/auth/login)

Original documentation: [OrangeHRM](https://www.orangehrm.com/assets/Files/Complete-Administrative-User-Guide.pdf?url=/Files/Complete-Administrative-User-Guide.pdf)


Tools used: Jira and Zephyr Squad

## 1.2 Functionalities in scope

> - All features of PIM ( Submenu: Add Employee ) module which were defined in software requirement specification need to be: Functional testing, GUI testing

The below Story was created in JIRA and describes the functional specifications of the "Add Employee" section. 


![](https://github.com/ElenaBlejan/Proiect-Practic-Testare-Manuala/blob/main/User%20story.PNG)


## 1.3 Functionalities and tests out of scope
> - All OrangeHRM features except PIM - Add employee and Employee list modules.
> - Non-functional testing like stress, performance is beyond scope of this project.
> - No QA support for mobile application developed. Only web application will be tested.
> - Automation testing is beyond scope.

# 2. *Test Process*
## 2.1 Test planning
**Roles and responsabilities:**


| ROLE  | NAME    |
| :-----: | :---: | 
| Software Developer | Loredana Alexe   | 
| Product Owner | Iulia Oprescu  | 
| Project Manager | Madalina Vladu | 
| QA Engineer | Elena Blejan | 
| Senior QA Engineer | Diana Dumitru |

**Entry criteria :**
> - Functional specification defined
> - Roles needed for the project are allocated
> - Initial project risks were detected and mitigated

**Exit criteria :**
> - All test cases have been executed
> - The number of unresolved bugs is insignificant or have low priority
> - All resolved bugs have been re-tested and closed by the QA team
> - Deadline was reached
> - No detected major risks remained un-mitigated

**Risks:**

***Project risks:***
> - lack of experience of the QA team
> - only one QA in the QA team
> - unavailability of the test environment
> - short deadline of Zephyr Squad and Jira tools

***Product risks:***
> - the inability of the product to fulfill the requirements
> - the inability of the product to meet the customer's expectations 

## 2.2 Test Analysis

 The testing process will be executed based on the Business Requirements for the PIM module – Add Employee. The following **test conditions** were found:
 
1. Verify that user cannot add an employee when no field was fill in
2. Verify that user can add an employee when the mandatory  fields are filled
3. Verify how many employees can be added
4. Verify that user cannot add an employee when required fields "First Name" and "Last Name" are filled with numbers
5. Verify that user cannot add an employee when required fields "First Name" and "Last Name" are filled with special characters
6. Check if all the expected fields are available in employee "Personal Details" section
7. Check the "First name" as required field by not filling any data in "Personal details" section
8. Check the "Last name" as required field by not filling any data in "Personal details" section
9. Verify that user can add a picture in "Add Employee" section
10. Check the functionality of  "Save" button at "Personal details" section
11. Verify that "Driver's License Number" from "Personal Details" section accepts any type of letters and special characters 
12. Verify that "License Expiry Date" accepts the format yyyy-mm-dd in "Personal details" section 
13. Verify that "Nationality" dropdown contains all the expected values
14. Verify that "Marital status" dropdown contains all the expected values
15. Verify if the user can select an option  from the dropdown list for "Marital status"  in "Personal details" section
16. Verify if the user can select an option  from the dropdown list for "Nationality"  in "Personal details" section
17. Verify that "Date of  Birth" accepts the format yyyy-mm-dd in "Personal details" section
18. Verify if "Date of Birth"  can't be set to future date in "Personal details" section
19. Verify that only one value from "Gender" radio buttons can be selected in "Personal details" section
20. Verify that "First Name" field does not accept over 30 characters in employee "Personal details" section
21. Check that user cannot insert numbers in "Military service" field
22. Check the functionality of  "Smoker" field in "Personal details" section
23. Verify that "Blood Type" dropdown contains all the expected values
24. Verify if the user can select one option  from the dropdown list for "Blood Type"  in "Personal details - Custom fields" section
25. Check the functionality of  "Save" button at "Personal details - Custom Fields" section
26. Check that user can add one attachment in "Personal Details - Add Attachment" section
27. Check that user cannot add one attachment larger than 1 MB in "Personal Details - Add Attachment" section
28. Check if multiple uploads are allowed in "Personal Details - Add attachment" section
29. Check that user can delete an attachment from attachment list from "Personal Details - Add attachment" section
30. Check the functionality of  "Edit" button in "Personal Details - Add attachment" section
31. Check that "Comment" field allows maxim 200 characters from "Personal Details - Add attachment" section
32. Check that "Add attachment" module in employee "Personal details" can be saved without filling in mandatory fields
33. Check that the field "Other ID" from "Personal Details " section accepts numbers
34. Check that the field "Other ID" from "Personal Details " section does not accept letters

 





## 2.3 Test Design

> - Functional test cases will be created in Zephyr Squad
> - GUI test cases will be created in Zephyr Squad
> - The test design techniques used for generating test cases are: equivalence partitioning, boundary value analysis.
 
**Test cases:**
 
 
 ![Screen jira](https://github.com/ElenaBlejan/Proiect-Practic-Testare-Manuala/blob/main/Test%20cases%202.JPG)


 
## 2.4 Test Implementation

The following elements are needed to be ready before the test execution phase begins:
> - Test environment is up and running: (https://opensource-demo.orangehrmlive.com/web/index.php/auth/login)
> - Access to the test environment is given: username Admin, pass: admin123
> - Cycle summary was created 
> - The test cases were added to the cycle summary

## 2.5  Test Execution

> - Test cases are executed on the created Cycle summary
> - Bug reports were created based on the failed test cases
> - Full regression testing is needed after the bugs are fixed

## 2.6 Test Completion

As the exit criteria were met and satisfied as mentioned in the 2.1 section, this feature is suggested to "Go Live" by the QA team.

## 2.7 Test Monitoring and Control

Periodic reports were done to reflect the current status of the testing process.

![Screen jira](https://github.com/ElenaBlejan/Proiect-Practic-Testare-Manuala/blob/main/Test%20Executions%20by%20Test%20Cycle.PNG)

![Screen jira](https://github.com/ElenaBlejan/Proiect-Practic-Testare-Manuala/blob/main/Test%20execution.PNG)
 
![Screen jira](https://github.com/ElenaBlejan/Proiect-Practic-Testare-Manuala/blob/main/Daily%20Test%20Execution%20Progress.PNG)

# 3. *Test Deliverables*

## 3.1 Test conditions
 
  Here you can find the list of test conditions that were created for this project:
[Test conditions ](https://github.com/ElenaBlejan/Proiect-Practic-Testare-Manuala/blob/main/Test%20condition.pdf) 

## 3.2 Test cases 
 
  Here you can find the list of test cases that were created and executed for this project: 
  [Test cases ](https://github.com/ElenaBlejan/Proiect-Practic-Testare-Manuala/blob/main/Test%20cases.pdf) 



## 3.3 Traceability matrix

I created two stories which, according to the traceability matrix were covered in the following way: 6 tests for OP-3 and 28 tests
for OP-2. Also the rate of defects of OP-2 was bigger (6 defects) than for OP-3 (2 defects) taking into account both the larger number of test cases that were created and executed and the process of defect clustering.
 
The Traceability Matrix was generated and can be found here: [Traceability Matrix ](https://github.com/ElenaBlejan/Proiect-Practic-Testare-Manuala/blob/main/Forward%20Traceability.xlsx) 
 
The Traceability Matrix short by story was generated and can be found here: [Traceability Matrix short by story](https://github.com/ElenaBlejan/Proiect-Practic-Testare-Manuala/blob/main/Forward%20Traceability%20by%20story.xlsx)
 
 
![Screen jira](https://github.com/ElenaBlejan/Proiect-Practic-Testare-Manuala/blob/main/Traceability%20Matrix%20screen.JPG)  

## 3.4 Test case results 
 Test cases are executed on the created Cycle summary and the test cases results can be found here: 
[Test cases results ](https://github.com/ElenaBlejan/Proiect-Practic-Testare-Manuala/blob/main/Test%20cases%20results.pdf) 

## 3.5 Bugs report 
Bugs have been created based on the failed tests. A number of 8 defects were found, from which the priority is: 2 high and 6 medium. They were reported to the development team and were prioritised according to their importance in the following way: first the bugs with high priority and second the bugs with medium priority.  
The list with bugs can be found here:
[Bugs report ](https://github.com/ElenaBlejan/Proiect-Practic-Testare-Manuala/blob/main/Bugs%20report.pdf) 

## 3.6 Test completion report 
 A number of 34 test cases were planned for execution and all of them were executed. After execution there were found 8 bugs. The bugs found do not impact the launch of the product and they can be fixed later. All the functionalities in scope were coverd.

![Test Completion Report ](https://github.com/ElenaBlejan/Proiect-Practic-Testare-Manuala/blob/main/Test%20Completion%20Report%201.png)


# SQL Section

For SQL section I created the database "Employee_OrangeHRM" with 5 (tabelas) tabels:

•	PersonalDetails 

•	Nationality 

•	MaritalStatus

•	BloodType

•	Department

In this SQL project I use the following queries:

•	create, use, select * from, insert;

•	update, alter table;

•	where, limit, max, sum, group by, count, cross join;

The SQL project can be found here: 

[SQL database](https://github.com/ElenaBlejan/Proiect-Practic-Testare-Manuala/blob/main/Database_Employee_OrangeHRM.sql) 

![Database Employee OrangeHRM ](https://github.com/ElenaBlejan/Proiect-Practic-Testare-Manuala/blob/main/diagram%20Employee_OrangeHRM.JPG)

