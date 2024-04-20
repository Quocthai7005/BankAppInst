This project demonstrates how Java Instrumentation API works.
To demonstrate the feature follow below steps:
1. run [mvn clean install] to create an agent jar file or this project.
2. run [mvn clean install] to create an agent jar file or project: BankApplication
3. With this step, we have 2 options:
   a. Run static instrumentation: run this command: java -javaagent:<agent.jar> -jar <application.jar> <parameters: (String Int Int Int)>
   b. Run Dynamic instrumentation: run this command: java -jar <application.jar> <parameters: ("LoadAgent" Int Int Int)
