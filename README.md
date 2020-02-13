# Jenkins CI Test


Jenkins CI automatically detects when a commit has been made and pushed to a GitHub repository that is using Jenkins CI, and each time this happens, it will try to build the project and run tests

 This project is build on Mocha and Chai JS 
 
 Where test cases are written in mocha.
 
 #Test Case:
A Test case basically a line of code where we write the condition to test the another line of code. Here we ensure that this particular system is working according the expectation or satisfy the requirements.
By writing the test cases can also help to determine the problem, bugs in existing system. We write the test cases to get the surety that system is working fine.

#Mocha:
Mocha is used for testing, It is a javascript framework for nodejs. Mocha is asynchronous. Mocha is used to build an environment where we can write and run our test cases.We can also use our assertion libraries under the mocha environment, here we will use “Chai”.

#Chai:
“Chai” is a BDD / TDD assertion library for node and the browser that can be delightfully paired with any javaScript testing framework. “Chai” provide a better way to write the test cases under mocha environment.
Why Chai ?
Actually Mocha provide the environment for making our test, But we need to test our API and our API using http calls like GET, PUT, DELETE, POST etc. So we need a assertion library to fix this challenge. Chai helps us to determine the output of this test case.


TDD (Test-Driven Development) mainly uses automated unit tests to give developers direction on how to design the software. This approach follows a set process.


behavior-driven-development: (BDD) is a software development approach that has evolved from TDD (Test Driven Development). It differs by being written in a shared language, which improves communication between tech and non-tech teams and stakeholders. In both development approaches, tests are written ahead of the code, but in BDD, tests are more user-focused and based on the system’s behavior.


command to achieve CI.

npm install

