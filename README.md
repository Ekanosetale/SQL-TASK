# SQL-TASKS
# TASK1 
•	Create a Database named “Students Record”
•	Create the following tables in the database create
- Students Info  (Student ID, Gender, Name, Age, Subject)
- Health records (Student ID, Blood Group, Height, Weight)
-	Performance (Student ID, Score, Grade)
•	The ID has to be unique
•	Where a student has no score, it should be ‘0’ by default
•	Add a constraint that prevents the ID and Subject from taking null values
•	Apply the following modifications to the table
1.	Change column name ‘’Subject” to ‘’Course” 
2.	Drop the “Age” column from the ‘Students Info’ table
  # SKILL Demonstrated
•	Creating Databases
•	Creating Tables
•	Inserting values into tables
•	Adding constraints to columns in a table
•	Retrieving information using SELECT
•	Altering table structure
 # Brief Discussion
I create the **Database** and **Tables** using the **CREATE FUNCTIONS**. I made the ID unique using the **PRIMARY KEY CONSTRAINT**. On the student’s score column, those without scores were set to indicate ‘0’ with the **DEFAULT CONSTRAINT**. Using the **NOT NULL CONSTRAINT**, student ID, and subject columns were set not to allow null values.  To rename the **‘subject’** column to **‘course’** I use the **rename** option from the column name drop-down. Lastly, to drop the age column from the table, the **ALTER FUNCTION**. These are shown in the  shots below:
![](Point3.PNP)
