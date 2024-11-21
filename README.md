# Banking-application

A leading private bank looking for solution to track customers and their account details .As part of requirements,the below mentioned has been given to the partner.

Note: Find below recommended naming conventions to consider
1. groupld: < ADID>.<phase>.<project>
Example: avitepa.foundation.bank
2. artifactld: <ADID>_<casestudy>
Example: AVITEPA_bank
Steps to follow / Check point for self-review (indicative only)
A. Set up Dev environment
Note: You may refer the WASP portal https://wasp.wipro.com/esd to get the required software/tools
• During Phase 2 & 3
1. Git Version 2.9
2. OpenJDK Version 11
3. Maven Version 3.6.0
4. Spring Tool Suite (OR You may use any alternative IDE)
5. You may use H2 DB (or MySQL Workbench Version 8.0.CE)
• During Phase 4
1. Jenkins Version 284
B. Getting started with Creating Spring Boot Application
1. Configure pom.ml with all required dependencies
2. Configure application.properties (server port, DB details and any other)
3. Configure application-integrationtest. properties (for unit testing)
C. Build your solution with suitable design / sequence of steps with your plan /assumptions
1. Identify Model(s) and configure attributes with JPA

2. Create Repository interface and test sample CRUD operations for identified Model(s)
i. Test for Empty records ii. Test for saving ili. Test for findAll iv. Test for findByld vi: Test for dedeny fields
vii. Test for deleteAll
viii. Test for update < using serialized field> ix. Test for update < using non-serialized field>
Note: if required append/define customized method with Query
3. Create "@RestController" and test for all identified end points
i. Create methods for all identified end points ii. Test all end points with hard coded Response body
a) Test for GetMapping
a. for String
b. Object
c. List
d. ResponseEntity<HttpStatus>
b) Test for PostMapping
c) Test for PutMapping
d) Test for DeleteMapping
4. Create "@Service" and test for all identified business requirements
A leading private bank looking for solution to track customers and their account details .As part of requirements,the below mentioned has been given to the partner. Note: Find below recommended naming conventions to consider 1. groupld: < ADID>.<phase>.<project> Example: avitepa.foundation.bank 2. artifactld: <ADID>_<casestudy> Example: AVITEPA_bank Steps to follow / Check point for self-review (indicative only) A. Set up Dev environment Note: You may refer the WASP portal https://wasp.wipro.com/esd to get the required software/tools • During Phase 2 & 3 1. Git Version 2.9 2. OpenJDK Version 11 3. Maven Version 3.6.0 4. Spring Tool Suite (OR You may use any alternative IDE) 5. You may use H2 DB (or MySQL Workbench Version 8.0.CE) • During Phase 4 1. Jenkins Version 284 B. Getting started with Creating Spring Boot Application 1. Configure pom.ml with all required dependencies 2. Configure application.properties (server port, DB details and any other) 3. Configure application-integrationtest. properties (for unit testing) C. Build your solution with suitable design / sequence of steps with your plan /assumptions 1. Identify Model(s) and configure attributes with JPA 2. Create Repository interface and test sample CRUD operations for identified Model(s) i. Test for Empty records ii. Test for saving ili. Test for findAll iv. Test for findByld vi: Test for dedeny fields vii. Test for deleteAll viii. Test for update < using serialized field> ix. Test for update < using non-serialized field> Note: if required append/define customized method with Query 3. Create "@RestController" and test for all identified end points i. Create methods for all identified end points ii. Test all end points with hard coded Response body a) Test for GetMapping a. for String b. Object c. List d. ResponseEntity<HttpStatus> b) Test for PostMapping c) Test for PutMapping d) Test for DeleteMapping 4. Create "@Service" and test for all identified business requirements 
Skills: RESTful WebServices · Agile Project Management · REST APIs · Java · Springboot
