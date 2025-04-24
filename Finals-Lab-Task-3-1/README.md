## Finals-Lab-Task-3-1  Using MYSQL Clause
Instructions:
Create a database named online_courseDB
Use the online_courseDB
Copy and paste the initial query then perform the SELECT statements required for the problems in the figure below. (download onlineCourse.sql file)
Item Description
The following are already implemented:
A table named courses with the following fields:
Id: Unique integer, auto-increment, primary key.
course_name: String (VARCHAR), not null.
category: String (VARCHAR), not null.
enrollment_limit: Integer, not null.
students_enrolled: Integer, not null.
20 courses are already present.
The following are the tasks that need to be implemented using MySQL statements. Make sure to complete them in the order specified:
## Task 1: Retrieve all courses where students_enrolled is less than the enrollment_limit.
Query  Statements
 ![Screenshot 2025-04-24 2012071STATEMENT](https://github.com/user-attachments/assets/e8e7ab3c-cf24-4422-b1ae-462a3cdcad88)

Table Structure
![Screenshot 2025-04-24 2012451TABLE](https://github.com/user-attachments/assets/a7ae783a-0f86-42ec-a2b9-97cb8e8dd703)
##  Task 2: Group courses by category and calculate the total number of students enrolled for each category.
Query  Statements
![Screenshot 2025-04-24 2014152STATEMENT](https://github.com/user-attachments/assets/25d325de-dfba-4460-8fe0-00638c05f68b)

Table Structure
![Screenshot 2025-04-24 2014472TABLE](https://github.com/user-attachments/assets/47aed23b-3752-41f2-83fb-c7a1d8f0a9aa)
## Task 3: Retrieve the courses that are fully enrolled (i.e., students_enrolled equals enrollment_limit).
Query  Statements
![Screenshot 2025-04-24 2018253STATE](https://github.com/user-attachments/assets/5122b225-628b-43b4-9ccb-e160d07ea0d3)

Table Structure
![table3](https://github.com/user-attachments/assets/2bf1ebec-550d-44ee-ba63-a7a2e88246e2)

## Task 4: Calculate the total number of students enrolled across all courses.
Query  Statements
![4taskstate](https://github.com/user-attachments/assets/f1dde938-680c-4b1c-b2e2-ff36bb97d314)

Table Structure
![tabletask4](https://github.com/user-attachments/assets/394430d4-87a4-4efa-8c56-48c7ebe26012)

## Task 5: Sort courses by students_enrolled in ascending order.
Query  Statements
![task5fn](https://github.com/user-attachments/assets/69f33a26-a8ea-40d5-9bd6-6a9eb730b47a)


Table Structure
![task5table](https://github.com/user-attachments/assets/cb130062-311a-41ed-a76a-60bff9c8b276)

