# Project-for-sportvision
Application under test: https://www.sportvision.ro/

*Tools used*: JIRA, Zephyr for Jira, MySQl.

The final project is split into 2 sections: Testing section and SQL section.

SQL section can be found here: [SQL section](https://github.com/VasiliuIonela/SQL-project-for-sportvison#sql-project-for-sportvison)

# Functional specifications

The below *Stories* were created in Jira and describe the functional specifications of the *Registration* module, *Wishlist* module, *Reviews* module and *Forgot password* module, for which this project is performed upon: [Stories](https://github.com/VasiliuIonela/Project-for-sportvision/blob/main/Jira.pdf).

# 1 Testing Section
## 1.1 Test Planning
The *Test Plan* is designed to describe all details of testing for modules: *Registration of a new account*, *Wishlist*, *Reviews for products*, *Forget password* in the sportvision webpage online shop.

This plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan.
## 1.1.1 Roles asigned to the project and persons allocated
* Project manager: Madalin Gheorgidiu
* QA Lead: Cerasela Anton
* QA Tester: Ionela Vasiliu
### 1.1.2 Entry criteria defined
* All test hardware platform have been successfully installed, configured and functioning properly.
* All the necessary documentation, design and requirements information is available(that will allow testers to operate the system and judge the correct behaviour).
* Functional specifications are defined.
* Roles needed for the project are allocated.
* Initial project risks were detected and mitigated.
### 1.1.3 Exit criteria defined
* 80% of requirements coverage has been achieved.
* All tests have been executed.
* No high priority or severe bugs are left outstanding.
* All resolved bugs have been re-tested and approved by the QA team.
* All high-risk areas have been fully tested, with only minor residual risks left outstanding.
* The schedule has been achieved.
### 1.1.4 Test scope
 The scope of this project is limited to the testing of the features in the succeeding sections of this document. All the features of modules, as follow: Registration, Wishlist, Forget password, Reviews, which were defined in software requirements specifications, need to be tested.
### 1.1.5 Risks detected
* Project risks: tight deadline, failure to detect bugs on time, unclear requirements, exceeding budget and deadlines, dependency on external resources.
* Product risks: security risks, low performance, incompatibility with some browsers.
### 1.1.6 Evaluating entry criteria
The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.
## 1.2 Test monitoring and control
Periodic reports were generated to reflect the current status of the testing process, in case of major problems, control measures could be taken.
The following status report was generated, to view the actual progress: [test metrics](https://github.com/VasiliuIonela/Project-for-sportvision/blob/main/test%20metrics.jpeg)
## 1.3 Test Analysis
The testing process will be executed, based on the requirements sent by the client. 
The following test conditions were found: [test conditions](https://github.com/VasiliuIonela/Project-for-sportvision/blob/main/test%20cases%20sportvision.jpeg)

## 1.4 Test Design
Functional test cases were created in Zephyr Squad and  can be accessed here: [test cases](https://github.com/VasiliuIonela/Project-for-sportvision/blob/main/test.cases..pdf).

## 1.5 Test Implementation
* Testing environment is up and running: www.sportvision.ro
* Cycle summary was created.
* Test cases were added to the cycle summary: [cycle summary](https://github.com/VasiliuIonela/Project-for-sportvision/blob/main/cycle.summary.jpeg)
## 1.6 Test Execution
* Test cases are executed on the created test Cycle summary: [cycle summary execution](https://github.com/VasiliuIonela/Project-for-sportvision/blob/main/execution.list.jpeg)

* Bugs have been created based on the failed tests. The complete bug reports can be found here: [bug reports](https://github.com/VasiliuIonela/Project-for-sportvision/blob/main/bugs.pdf)
* Full regression testing is needed after the bugs are fixed.

## 1.7 Test Completion
* As the Exit Criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to 'Go live' by the Testing team.
* The traceability matrix was generated and can be found here: [Traceability matrix](https://github.com/VasiliuIonela/Project-for-sportvision/blob/main/Forward%20Traceability_15_5_2023%20(1).xlsx).
* Test execution chart was generated:
[test execution chart](https://github.com/VasiliuIonela/Project-for-sportvision/blob/main/execution.chart.jpeg)

After Testing of the functionalities for account registration, review submission, password recovery, and wishlist management, we have reached the following conclusions:

**Account registration functionality:** It was tested and performed efficient. Users were able to create new accounts without major issues. However, we have identified some minor aspects that require adjustments, such as inadequate marking of mandatory fields with asterisks (bug was reported).

**Review submission functionality:** The functionality for submitting reviews was generally efficient, and users were able to express their opinions easily. However, we noticed a few minor issues regarding reviews, such as the inability for users to rate products on a scale of 1 to 5 (bug was reported).

**Password recovery functionality:** The testing of the password recovery functionality demonstrated that users were able to recover their passwords adequately.

**Wishlist  functionality**  was tested and generally well-implemented. Users were able to add products to their wishlist and manage them appropriately. However, we observed that the system's responsiveness in terms of updating and displaying wishlist could be improved.

The tested functionalities generally performed well, with a few minor aspects that require adjustments to provide a better user experience. It is recommended to make these adjustments and further enhancements to ensure a seamless user experience when using these functionalities.

