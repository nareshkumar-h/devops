#### DevOps
* Combination of the development of our code paired with the operation of our code.
* Code -> build -> Test -> Deploy -> maintenance -> evaluation

#### Continuous integration  
* All developers push and pull code to a central repository accompanied with automatic builds and testing. 
* Helps us fail fast to see what code works and what does not

#### Continuous Delivery 
* Successful builds which pass automated tests are stored in a staging area where they can be marked for deployment into the market. You might have a human assurance testing team at work before deployment.

#### Continuous deployment
* If all tests are passed then the application can go immediately live and available to end users without any human approval

#### Static code analysis (Sonar Cloud)
-	Analyzes your code for bad programming practices
-	Improvements or possible vulnerabilities
-	Does NOT execute or run my code


#### Jenkins- Build and deployment automation tool 

1.	Source code in a repository
2.	Create an ec2 with Maven (building our application), Tomcat (hosting our application)
3.	Installed Jenkins to read from that repository and automatically call Maven to build our application and deploy it on Tomcat




