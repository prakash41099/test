# test

# Detail requirements
## High Level Requirements:
| ID | Description |Steps to be executed|Expected O/P |Expected I/P|Actual Output|Type of Test|Pass/Fail|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|HLR_01| System shall be able to read the excel sheet. |User will have to enter the file name |System  will read the file and get the required data entered in the code|Datas should be entered in the excel  sheet|System prints the output|Requirement Based|Pass|
|HLR_02| The system shall able to store the output |The user should eneter the file path,where the output needs to be stored|The output is of the form of excel sheet|Enter the file name|The final output content will display|Requirement Based|Pass|
|HLR_03|The system shall able to identify whether the student(s) is present for the day.|User have to the enter the mark the attendence for the particular day|The system should able to read the data|The user should mark the attendence for the particular day |The systems reads the data given by  the user in the excel sheet|Scenario Based|Pass|||




##  Low level Requirements:
| ID | Description | Type|Expected O/P |Expected I/P|Actual Output|Type of Test|Pass/Fail|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|LLR_01| System shall be able to read the total number of students given in the excel sheet|HLR_01|The system should able to count the number of students|User will enter the data in the excel sheet|The system reads the data |Requirement Based|Pass|
|LLR_02| System shall be able to read the total number of Days given in the excel sheet|HLR_01|The system should able to count the number of days|User will enter the data in the excel sheet |The system reads the data|Requirement Based|Pass|
|LLR_03| User shall be able to view the output |HLR_02|The outout is stored in the excel sheet once the program is executed|The system reads the excel sheet |The system creates new entries int the excel sheet as programmedd by the programmer|Requirement Based|Pass|
|LLR_04|The system should able to mark TRUE if the student is Present |HLR_03|the system should return TRUE|The data given in the excel sheet is of "P(2/2)" which states that student is present  |The system returns TRUE|Scenario Based|Pass|
|LLR_05|The system should able to mark FALSE if the student is Present |HLR_03|the system should return FALSE|The data given in the excel sheet is of "?" which states that student is absent  |The system returns FALSE|Scenario Based|Pass|
