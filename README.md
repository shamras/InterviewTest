# InterviewTest

1. This Framework was created with MAVEN and Selenium web driver I used dependencies such Testng, and maven surefire plug in for report Generating. I also used Log4j for a another HTML reporting but I have not added log listerners to the entire code base.
2. In Order to run these tests ensure you have a selenium webdriver for google or it can be added via the dependency in my case I had one on my local, once you have this you can change set system properties.
3. I also used Jenkings to Run the tests, I did not include the Jenkin.war as it is something I have on my local. Once I use Jenkins I would add my pom.xml File to the MVN test run link and run these tests.


4. The postman collection I was able to create a new user, and bring up one user. I could not bring up 10 users because the api did not have much to go on for searching or filtering infact never had these in the documenation. Dont forget to remove the postman collection once the project has been cloned.

Note I used Intelij as my IDE to create this maven tests, so when importing this ensure you have the above added to your project. Then run mvn clean, mvn compile, mvn test this can also be done on command line.


Also I was not able to finish test4 if I was to complete that I currently use a framework called cypress.io to write java script test data.
