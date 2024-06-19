<h1>Testing Project for **TAROM**</h1>

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application

Application under test: **TAROM**

Tools used: Jira, Zephyr Squad.

<h2>Functional specifications:</h2>

The below stories was created in Jira and describes the functional specifications of the "check-in","passager information","reservation" module, for which the final project is performed upon.

[text](<d:/Tarom Jira/Filter+for+IZT+board+(Jira).doc>)    https://itfclasses.atlassian.net/jira/software/c/projects/IZT/boards/400/backlog?issueType=10001&selectedIssue=IZT-18

Here you can find the release that was created for this project:

 ![image](https://github.com/ZahariaI/Tarom-Jira/assets/166908547/e20e66a5-32d0-41d5-9f72-8d99e53392e2)
![image](https://github.com/ZahariaI/Tarom-Jira/assets/166908547/8bad31c5-2506-4ee9-b74b-3eb833bbb0af) 
![image](https://github.com/ZahariaI/Tarom-Jira/assets/166908547/3b0b499b-f55e-49e1-b206-14ac21277c65)
![image](https://github.com/ZahariaI/Tarom-Jira/assets/166908547/e5f5ca94-90af-4782-9346-4750cd7b6b42)

<h2>Testing process</h2>

The test process was performed based on the standard test process as described below.

<h3>1.1 Test planning</h3>

The Test Plan is designed to describe all details of testing for all the modules from the JPetStore Demo application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan. The test plan that was created for this project can be found here (https://onedrive.live.com/edit?id=EDAC4614722B6514!1448&resid=EDAC4614722B6514!1448&ithint=file%2cdocx&ct=1717437297526&wdOrigin=OFFICECOM-WEB.START.EDGEWORTH&wdPreviousSessionSrc=HarmonyWeb&wdPreviousSession=850a4a34-d094-424c-a623-f8b578586976&wdo=2&cid=edac4614722b6514)

<h4>1.1.1. Roles asigned to the project and persons allocated</h4>


<ul>
  <li>Ionescu Elena</li> 
  <li>Popescu Vasile</li>
  <li>Grigorescu Larisa</li>
  <li>Zaharia Ionica</li>
</ul>

<h4> 1.1.2 Entry criteria defined </h4>

1)Test environment up and running 

2)Smoke testing passed 

3)Permissions available 

4)Business requirements are available and agreed, completed by the analyst 

5)Roles and responsibilities established and agreed 

6)Projects risks identified and mitigated  

7)Deadlines established 

8)Objectives of testing established, communicated within the team 

<h4> 1.1.3 Exit criteria defined </h4>

1)Minimum 95% of all tests passed							2)No critical defects opened								3)The objectives have been accomplished						4)The deadline has been reached							5)The budget has been reached								6)Test report summary 										7)All defects have been documented and communicated to stakeholders		8)Test updates passed 100% 

<h4> 1.1.4 Test scope</h4>

<h5> Tests in scope: </h5>

positive testing, and negative testing. Additionally, we will conduct non-functional testing, such as usability testing, performance testing (stress, load, volume, and spike), retest and regression testing. 

<h5>Tests not in scope: </h5>

 Legal problems,Some features were not tested because they were not included in the software requirement specifications. These features include Trip Planning, My Booking, Information, Search button, and other information on the main page except for Passenger Information, Book, and Check-in. 

<h4>1.1.5 Risks detected</h4>

<h5>Project risks:</h5>
Reputation of the company, poor services, defamation of the company by the competition financial losses


<h5> Product risks: </h5>

tehnical failures, currency risk, climate

<h4>1.1.6 Evaluating entry criteria</h4>

The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

<h3>1.2 Test Monitoring and Control<h3>

The reason why the monitoring and control was done, was to verify the usefulness of the site and it's credibility.
We performed usability tests, positive tests, negative tests, interface tests,non-functional testing. 
https://itfclasses.atlassian.net/projects/IZT?selectedItem=com.thed.zephyr.je__traceability-project-level
https://itfclasses.atlassian.net/projects/IZT?selectedItem=com.thed.zephyr.je__search-test-executions-project-level

<h3> 1.3 Test Analysis </h3>
The testing process will be executed based on the application requirements. <b>(The requirements analysis has been done in order to implement the <i>early testing</i> test principle and the results can be found here - inserati linkul catre documentul de review. Parte asta specificata intre paranteze o puneti doar daca aveti cerinte si daca ati facut review)</b>. <br><br>

The following test conditions were found: <br>
![image](https://github.com/ZahariaI/Tarom-Jira/assets/166908547/8e848e0f-3ae2-4883-b682-b55058797399)





<h3> 1.4 Test Design</h3>

Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed here
https://itfclasses.atlassian.net/projects/IZT?selectedItem=com.thed.zephyr.je__test-cases

<h3>1.5 Test Implementation</h3>

The following elements are needed to be ready before the test execution phase begins:

To ensure successful testing, it's important that the environment is ready. This is achieved by validating it through smoke testing. Test Analysts organize and prioritize tests, creating test suites from the test procedures for efficient execution. It's crucial to verify that the test environment has been set up correctly. Actual results are then compared to expected results, with tests grouped based on objectives such as functional, regression, and acceptance testing. 

<h3>1.6. Test Execution </h3>

Test cases are executed on the created test Cycle summary: TAROM_VERSION_1

Bugs have been created based on the failed tests. The complete bug reports can be found here: ![image](https://github.com/ZahariaI/Tarom-Jira/assets/166908547/3887e7f2-cbd5-45bb-8349-2a1eed74a17c)
![image](https://github.com/ZahariaI/Tarom-Jira/assets/166908547/46a8a9fe-be59-4408-a606-b12134cd89fe)
![image](https://github.com/ZahariaI/Tarom-Jira/assets/166908547/bb55932b-55ed-4f52-a026-281dbc135872)


The following is a summary of the bugs that have been found
(image-11.png)

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

1.7 Test Completion
As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team

The traceability matrix was generated and can be found here:
https://itfclasses.atlassian.net/projects/IZT?selectedItem=com.thed.zephyr.je__traceability-project-level

Test execution chart was generated and can be found below. 
![image](https://github.com/ZahariaI/Tarom-Jira/assets/166908547/becd010a-5b69-4420-90ab-36bbfc8c6580)

The final report shows that a number 14 tests have failed of a total of 1

A number of 3 total bugs were found, from which the priority is:0 are high and 3 are medium.

Following the testing, 14 tests where performed whith a low impact on users and minimal severity that does not and danger the lives of users and the optimal functioning of the site. All the tests in scope were covered.  
