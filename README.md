# AutoTests for Аптека для Бережливых website

---

* This project is aimed at providing automated tests for the website [Аптека для Бережливых](https://aptekaeconom.com/)

## Stack: Java | Selenium | TestNG

---

## Project Overview
* The project is developed following the principles of Page Object Model (POM).
  The main advantage of this pattern is its ease of test maintenance in case of UI changes.
####
* To run the project locally, install 
  [Maven](https://maven.apache.org/download.cgi) and 
  [Java](https://www.java.com/download/ie_manual.jsp) on your local machine.

To run tests use the command:

- `mvn test`

For download allure report use the command:

- `mvn allureReport`

For generate allure report use the command:

- `mvn allureServe`

To get a clear report use the following command before running test

- `mvn clean`

####
## Tools Used:
* [TestNG](https://mvnrepository.com/artifact/org.testng/testng)
* [Selenium](https://mvnrepository.com/artifact/org.seleniumhq.selenium/selenium-java)
* [AssertJ](https://mvnrepository.com/artifact/org.assertj/assertj-core)
* [Allure](https://mvnrepository.com/artifact/io.qameta.allure/allure-testng)
* [Owner::Core](https://mvnrepository.com/artifact/org.aeonbits.owner/owner)
* [Maven_Surefire_Plugin](https://mvnrepository.com/artifact/org.apache.maven.plugins/maven-surefire-plugin)
* [ASHot](https://mvnrepository.com/artifact/ru.yandex.qatools.ashot/ashot)

### "Аптека для Бережливых" Project Tests Allure Screenshots
![Allure_Overview](https://github.com/AnnaAbg/QAA_Java_Practicum/assets/106620445/60225a4a-64da-4d5d-a4d1-86de5e868b5b)


