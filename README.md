Project structure
framwork - project related part with PageObjects, models and utilities
configuration/: classes that used to fetch project config from src/main/resources/environment folder
forms/: Page Objects
models/: classes that represent data models of the application 
src/main/resources/: resource files such as configurations and test data
Project supported for for latest chrome browser . Version 105.0.5195.127. 

Tests execution with TestNG plugin for IDE (Intellij Idea, Eclipse) or with Maven command mvn clean test where you can specify all necessary arguments.

