# mvnProject
Maven project template with necessary dependencies.

## List of dependencies
1. [TestNG](https://testng.org/doc/documentation-main.html)
2. [Lombok](https://projectlombok.org/features/all)
3. [AssertJ](https://assertj.github.io/doc/)
4. [Apache Log4j 2](https://logging.apache.org/log4j/2.x/)

## Command to run tests
1. To run modern tests:
`mvn test -DtestNgSuite=resources/suites/UnitTestsSuite.xml`

## Pre-requisites:
1. Java is installed on your machine.
   * [Install JDK](https://www.oracle.com/java/technologies/javase-downloads.html)
2. Maven is installed on your machine, JAVA_HOME environment variable is created, path to Maven is added to environment variable PATH
   * [Download Maven](https://maven.apache.org/download.cgi)
   * [Install Maven, configure enviroment variables](https://maven.apache.org/install.html)
3. Git is installed on your machine.
   * [Install git](https://www.atlassian.com/git/tutorials/install-git)
4. IDE (IntelliJ IDEA for example) is installed on your machine.
   * [Install IntelliJ IDEA](https://www.jetbrains.com/idea/download/)
5. Set Project SDK to your JDK (installed in Step 1)  in Intellij - File > Project Structure > Project.
6. Restart your machine to implement updated  environment variables (need for some OS).