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
|-- test-output				#Test report is stored here
```
#Getting Started
Use the following commands to clone the project
```
```
