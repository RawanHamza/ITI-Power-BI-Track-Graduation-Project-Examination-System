# Examination System

## INTRODUCTION
  
 Welcome to the Examination System of ITI .. 

 Due our journey as being itian’s students in power BI Track,
 we have been inspired actually to develop this examination system in 
a helpful manner,That covers different aspects of this huge educational institution so that any supervisor or manger can use it to analysis 
the data of the students instructors, departments, courses and exam performance and KPIs and job offers and progress through different dashboards for each of them which will help to give a useful insights to be used.

Once exams are administered, the evaluation phase becomes crucial. Professors will find detailed instructions on how to assess student answers, assign grades, and provide valuable feedback. 

As after taking the data of the students and their grades of the courses this gonna help to know their progress in the study process and will help in the end to know the performance of them and try to improve it so they can achieve the kpis in an excellent way and get a good job 

So we in our system explore methods for tracking and analyzing performance trends, identifying areas of improvement, and generating comprehensive reports. These insights empower educators to make data-driven decisions and implement targeted interventions to enhance learning outcomes.


## ERD & Mapping: 

at this phase we decided our entities and the tables which are :
{ Student ,Department ,Instructor,Course,Topic,Question,Exam ,Choice ,
Exam_Question ,student course student answer, student exam grade,
Course evaluation,KPI ,Job offer }
we made the mapping for it after creating it as the below :
ERD:
![ERD](https://github.com/RawanHamza/ITI-Power-BI-Track-Graduation-Project-Examination-System/assets/62294577/a88228ec-db10-4b03-8149-009d00abb89d)

Mapping:
![image](https://github.com/RawanHamza/ITI-Power-BI-Track-Graduation-Project-Examination-System/assets/62294577/8182b8a3-c68c-4bc0-a6e4-4e6cf3508e8a)



## Creating Database & Implementation :
Creating a database for an examination system typically involves defining tables :
{Student ,Department ,Instructor,Course,Topic,Question,Exam ,Choice ,
Exam_Question ,student course student answer, student exam grade,
Course evaluation,KPI ,Job offer }
Import data directly from Excel files by using the SQL Server Import and Export Wizard.
Create Stored procedures
- Select, Insert update, and delete in any table
- Exam generation
- Exam Answers 
- Exam Correction & Grades


After finishing the stored procedures and testing them we moved to the phase : 

## Data extraction: 
At this phase we have extracted data from a database for generating reports in Power BI Desktop, SQL Server Report Service, and Power BI Report Builder that need querying database, saving the data as a CSV file, then importing it into the reporting tool




## SSRS:
 SQL Server report server to present the data from stored procedures to SSRS 
as the upcoming :
-1-Report that returns the students' information according to the Department No parameter

-2-Report that takes the student ID and returns the grades of the student in all courses. 

-3-Report that takes the instructor ID and returns the name of the courses that he teaches and the number of students per course.

-4-Report that takes course ID and returns its topics
  
-5-Report that takes exam number and returns the Questions in it and choices [free-form report]

-6-Report that takes the exam number and the student ID then returns the Questions in this exam with the student's answers.



## Power BI Report builder:  
paginated  report designed for creating a report has the information of students, instructor,exams.


## Power BI  Dashboard: 

### [Click Here to open the dashboard and try it out!](https://www.novypro.com/project/iti-power-bi-track-graduation-project-%7C-examination-system)

After the above phases, we came to the time of making the Dashboards that 
supervisor the manager or any stakeholder will use it to analyze the needed data from any table we mentioned in our system to get the important insights that will be so useful in tracking the performance of the system overall 
we have made 20 dashboards but we will focus now on the main 6 overviews in the upcoming screens :


1- overview when you log into the system dashboard.

2- Student overview :
The total number of students and number due to the gender distribution and the average age, also you can find students by age and student graduation year, and we should mention that we made a filter so that you can enter any name for the student and get the needed insight due to the student you wrote his name  and there is important navigation buttons in the left side to choose from it thing you need to know from distribution or the KPIs or the job offers or graduated students to get the insights you want

3- Instructor overview :

There are 2 main filters one by the instructor city and the other by the instructor name to filter the data to these two mentioned then 
when you choose the instructor's name you can have its mail, also we made a card with the total number of instructors we have, and the number of instructors in each department in the system, and also we got a map to get the number of the instructors in each city and the distribution of the instructors by its gender
also, you can find in the left related navigation button for the instructors to choose from and they are: feedback or the instructor's performance 

4-Department overview :

 There is  a main filter on the dashboard and it is the department name, and when you choose the name the manager of it will show immediately, we made a card to show the total number of departments we have, and distribution and the total number for the instructor in each department and numbers of the departments by its location 
and as usual on the left, you can find 2 navigation buttons to choose from department or department performance.

4- Course  overview :

There is main filter on the dashboard here and it is the course name, and when you choose the name it will show immediately the insights due to it, we made a card to show the total number of the courses and average courses duration, also we have  the course duration due to the topic name and the number of courses by department name, also we have a table to show information like the course name and its duration and topic name and number of students, and as usual there in the left, you can find navigation  buttons to choose from the course, course grade course feedback and student course

 
5- Exam overview :

 Here we can see there is one main filter on the dashboard and it is the course name, when you choose the name it will show immediately the insights due to the total Exam number, number of questions, and exam duration,  and also we have the number of exams by the month and number of questions by the question type and a table show information about the exam date and its day and number of exams and its id.



With all of those dashboards, you can navigate through the system and get the main insight you want and do the analysis in an easy way to help you improve your progress in the educational institution and the progress of the student we can sum this up in the 
journey map of the user in the upcoming visual : 

![image](https://github.com/RawanHamza/ITI-Power-BI-Track-Graduation-Project-Examination-System/assets/62294577/4b89dc9a-a047-4a46-a741-f6677302b490)


### Team members:
- Rawan Elghali
- Mennatullah Mohamed Bahaa Eldein
- Yomna Hamed Shehabeldien
- Eslam Ibrahim Badr
- Abdelmonem Ali Elmongy



