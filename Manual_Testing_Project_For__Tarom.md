<h1>Testing Project for **TAROM**</h1>

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application

Application under test: **TAROM**

Tools used: Jira, Zephyr Squad.

<h2>Functional specifications:</h2>

This story has been done  in Jira and describes the functional specifications of the "check-in","passengers information","reservation" module, for which the final project is performed upon.
![image](https://github.com/user-attachments/assets/7329909a-d391-4c57-8d2f-8bc38becd794)

Here you can find the release that was created for this project:
![image](https://github.com/user-attachments/assets/fead660f-ffc7-4702-abd9-15b46bdd9650)

<h2>Testing process</h2>

The test process was performed based on the standard test process as described below.

<h3>1.1 Test planning</h3>

The Test Plan is designed to describe all details of testing for all the modules from the JPetStore Demo application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan. 
The test plan that was created for this project can be found here

 https://onedrive.live.com/edit?id=EDAC4614722B6514!1448&resid=EDAC4614722B6514!1448&ithint=file%2Cdocx&ct=1717437297526&wdOrigin=OFFICECOM-WEB.START.EDGEWORTH&wdPreviousSessionSrc=HarmonyWeb&wdPreviousSession=850a4a34-d094-424c-a623-f8b578586976&wdo=2&cid=edac4614722b6514



<h4>1.1.1. Roles asigned to the project and persons allocated</h4>
<ul>
  <li>Ionescu Elena - Team lead</li> 
  <li>Popescu Vasile - QA</li>
  <li>Grigorescu Larisa - QA</li>
  <li>Zaharia Ionica - QA</li>
</ul>

<h4> 1.1.2 Entry criteria defined </h4>

  <li> Business requirements are available and agreed, completed by the analyst </li> 

  <li> Roles and responsibilities established and agreed </li>

  <li> Projects risks identified and mitigated </li> 

  <li> Deadlines established </li>

  <li> Objectives of testing established, communicated within the team </li>

<h4> 1.1.3 Exit criteria defined </h4>

  <li> Minimum 95% of all tests passed	</li>					
 
  <li>  No critical defects opened</li>								
  
  <li> The objectives have been accomplished	</li>					
 
  <li> The deadline has been reached</li>							
 
  <li> The budget has been reached	</li>							
  
  <li>Test report summary</li> 										
  
  <li> All defects have been documented and communicated to stakeholders	</li>
  
  <li> Test updates passed 100%</li> 

<h4> 1.1.4 Test scope</h4>

<h5> Tests in scope: </h5>

positive testing, and negative testing. Additionally, we will conduct non-functional testing, such as usability testing, performance testing (stress, load, volume, and spike), retest and regression testing. 

<h5>Tests not in scope: </h5>

 Legal problems,Some features will not be tested because they were not included in the software requirement specifications. These features include Trip Planning, My Booking, Information, Search button, and other information on the main page except for Passenger Information, Book, and Check-in. 

<h4>1.1.5 Risks detected</h4>

<h5>Project risks:</h5>
 <li>Reputation of the company   - Due to the strikes and non-compliance with flight times faced by the Tarom company, passenger confidence 
                              has dropped considerably and is affecting the sale of tickets;

 <li>Currency risk               - The increase and change in the exchange rate. In all developed countries, promotional rates are used for 
                              overflight services provided to national companies, for this reason the involvement of the Ministry of 
                              Transport is required         

 <li>Optimizing SkyTeam benefits - Associating or expanding the cooperation network with partners can bring more financial benefits

<h5> Product risks: </h5>

 <li>  Common IT platform  - Using an old technology, not using new programs that can reduce expenses and simplify things

<h4>1.1.6 Evaluating entry criteria</h4>

The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

<h3>1.2 Test Monitoring and Control<h3>

 In this phase, the project is on schedule, the resources were sufficient, the deadline was met
 
https://itfclasses.atlassian.net/projects/IZT?selectedItem=com.thed.zephyr.je__traceability-project-level
https://itfclasses.atlassian.net/projects/IZT?selectedItem=com.thed.zephyr.je__search-test-executions-project-level



<h3> 1.3 Test Design</h3>

Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed here

https://itfclasses.atlassian.net/projects/IZT?selectedItem=com.thed.zephyr.je__test-cases

<h3>1.5 Test Implementation</h3>

The following elements are needed to be ready before the test execution phase begins:

To ensure successful testing, it's important that the environment is ready. This is achieved by validating it through smoke testing. Test Analysts organize and prioritize tests, creating test suites from the test procedures for efficient execution. It's crucial to verify that the test environment has been set up correctly. Actual results are then compared to expected results, with tests grouped based on objectives such as functional, regression, and acceptance testing. 

<h3>1.6. Test Execution </h3>

Test cases are executed on the created test Cycle summary: TAROM_VERSION_1

Bugs have been created based on the failed tests. The complete bug reports can be found here: 

https://itfclasses.atlassian.net/jira/software/c/projects/IZT/issues/IZT-47?jql=project%20%3D%20%22IZT%22%20AND%20type%20%3D%20Bug%20ORDER%20BY%20created%20DESC


The following is a summary of the bugs that have been found

![image](https://github.com/user-attachments/assets/5663a884-9250-4e6e-8635-ee1b87e5f1a9)


Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

1.7 Test Completion


As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team

The traceability matrix was generated and can be found here:

Following the generation of the traceability matrix, it can be seen that out of the total of 8 stories and 14 tests, in the IZT-41 story, in the IZT-42 test, we discovered 3 bugs.

https://itfclasses.atlassian.net/projects/IZT?selectedItem=com.thed.zephyr.je__traceability-project-level

Test execution chart was generated and can be found below. 


![image](https://github.com/ZahariaI/Tarom-Jira/assets/166908547/8fdce5ae-1311-4d4e-9963-c2c016e02598)


The final report shows that a number 14 tests have failed of a total of 1.

A number of 3 total bugs were found, from which the priority is:0 are high and 3 are medium.

Following the testing, 14 tests where performed whith a low impact on users and minimal severity that does not and danger the lives of users and the optimal functioning of the site. All the tests in scope were covered.  
