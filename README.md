
# XEBuisness
Selenium Documentation References:-

1) https://www.selenium.dev/documentation/en/



# Test Automation Project

Acceptance test for ClickTime URL feature.



## Table of Contents

1. Development requirements
2. Configuring test project
3. Creating tests
4. Creating Logging Handler
5. Running tests 
6. Project structure

## 1. Development requirements

**Required:** Chrome browser, Chrome Driver(91.0.4472.19), Java Development Kit 15 (JDK11) and maven (3.6.3) should be present on environment in order to develop and/or run the tests.

## 2. Configuring test project

Run this command to ensure the code has no errors:


$ mvn clean install


## 3. Creating tests

The test cases will be written in java lanuage using TestNg annotation language present under  under \src\test\java\TitanHq\ClickNew\TestCases. The 
Page Object Model is used for writing test cases and all te pae object class are present under folder src\main\java\TitanHq\ClickNew\PageObjects.

## 4. Running tests

$ mvn clean install 
 

## 5. Project structure
src/main/java/TitanHq/ClickNew -: contains three packages.
 
    BaseResources -: contain a java class named Base.java which is a Base class and  data.properties file and log4j file
    CommonClasses -: contains an Abstract java class named AbstractComponent.
    Page Object -: It will contain Page Component class for the application
    
 
 src/test/java/TitanHq/ClickNew -: contains one packages.
    
    TestCases -: It will contain the Test Scripts for Application.
    TestRunner -: Contains the TestRunner java class.
    


