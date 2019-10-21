# shonam-mulani
# Task 1 :
Task 1 folder contains the Test Suite for Monefy Android Application in Microsoft Excel Format.

I have created test plan with **Test Suite ID,Name,Description,Test Case ID,Test Case,Expected Results,Automation Required & Status(Pass/Run)** sections.
Test cases are divided into different pages of App and prioratized as per User Interface & Functional levels.
1. **User Interface** : It covers all test cases for navigation & valid/invalid value scenarios.
2. **Functional** : It covers all the test cases for the functionality of app like if all the details are correctly updated as per user input.

# Task 3:
I have automated "**Best Buy API**" app with all possible scenarios for all endpoints provided with Valid as well as Invalid scenarios.
All the assertions for each operation has been taken care.
- **IDE used** : Eclipse IDE for JAVA developers(4.13.0)
- **Libraries Used for automation** : Rest Assured - 4.1.1
- **Maven SureFile plugin** : 2.19.1
- **TestNG** : 7.0.0

## Setup Instructions For Task 3:

1. Download and install Eclipse IDE for Java Developers from here
2. Make sure Best Buy API is running on your machine.
3. Clone this repo : 
git clone https://github.com/SMK125/shonam-mulani.git
4. Import cloned repo in step 3 as Maven project in Eclipse
:
File->Import->Go to Maven -> Existing Maven Projects
Click on Next
Choose shonam-mulani\Task3 folder. And Click on Finish.
5. In import project ,right click on pom.xml & run as -> Maven build so that all the dependencies will be uploaded.
Now to run automation project ,right click on pom.xml & Run as -> Maven Test .All test suites will be executed.
Automation TestNG report can be seen from target -> surefire-reports->index.html
