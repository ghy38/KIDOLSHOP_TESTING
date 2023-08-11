# Overall test automation framework design
```
root
|-- pom.xml
|-- testng.xml
|-- Screenshots				#Include bug's screenshots
|-- configuration			#Can config properties here
|-- src
|   |-- main/java/com/automation	
|   |   |-- base			#Include file to set up driver
|   |   |-- pom				#Include automation files are built according to the POM structure, can be reusable
|   |   |-- utils			#Include support files such as: get & set property, capture screenshot,... 
|   `-- test/java/com/aumation
|       |-- testcase			#Test cases are stored here
```
# Getting Started
Use the following commands to clone the project:
```
git clone https://github.com/ghy38/KIDOLSHOP_TESTING.git
```
# Run the Java Test
1. Set up Environment variables
    - [Maven](https://maven.apache.org/download.cgi)
    - [JDK17](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html)
2. Run the following command in KIDOLSHOP_TESTING dicrectory:
```
mvn clean test
```
