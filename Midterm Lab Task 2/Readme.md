# Midterm Lab Task 2 - Data Cleaning and Transformation Using Power Query Editor
## Step 1 - Cleaning the data using PowerQuery Editor
Download and open the raw data given by your instructor.

Add the required columns (Min Sal, Max Sal, Role Type).

Split the columns (Salary Estimate, Location, Size).

Change the columns to appropriate data types (Currency, Text).

Filter columns (Competitors, Revenue, Industry to remove negative values).

Remove unnecessary columns to avoid redundancy (Company Name ratings, extra descriptions).

Save the M Language to a notepad.

Before Cleaning
Uncleaned Photo 1

![Image](https://github.com/user-attachments/assets/5efe1018-2ce7-4e40-8c9a-0dde85dddc59)
 Uncleaned Photo 2
 
![Image](https://github.com/user-attachments/assets/e1ebc394-b25a-46be-bf46-ccad1cd37afa)

Uncleaned Photo 3

![unc3](https://github.com/user-attachments/assets/15f3aa79-e7ab-4f60-81c3-40bb8d8cc0d5)

## After Cleaning

Cleaned Photo  1

![clean1 1](https://github.com/user-attachments/assets/0e306f12-0318-437f-833a-998a537d3680)



Cleaned Photo 2

![clean2 2](https://github.com/user-attachments/assets/18cfbbc2-6cad-4577-b21b-5b4f679c0492)


Cleaned Photo 3

![cleaned2 3lst](https://github.com/user-attachments/assets/30a6d45b-df44-480a-a0d8-dc1c3ef78b56)

## Step 2 - Reshaping and Grouping the Tables
Duplicate and reference Unclean DS Jobs to create new queries (Sal By Role Type dup, Sal By Role Size ref, Sal By State ref).

Select appropriate columns 

Change the columns to required data types (Currency).

Multiply Min Sal and Max Sal by 1000.

Group data by Role Type, Size, State Full Name to get averages.

Merge State Mapping with Unclean DS Jobs using State Abbreviation.

Rename merged column to State Full Name and remove nulls.

Check and review Query Dependencies.

## Grouped of Tables
Salary by Size Role Type Table

![sal by role size](https://github.com/user-attachments/assets/7e5813d2-40ec-4d18-affb-e955141ed0cb)


Salary by Role Type Table

![sal by role type](https://github.com/user-attachments/assets/2402dc02-5543-49e0-a3b3-d202962debeb)


Salary by State Table

![Sal by size](https://github.com/user-attachments/assets/c6f65fd4-569b-4ae8-b039-1bae34dc3976)


States Mapping Table

![state 1 1](https://github.com/user-attachments/assets/0399668f-702b-4c20-b211-8c2061f7fe20)

## Step 3 - Query Dependencies
 View and selecting the Query Dependencies.
Double check if they are properly linked appropriately.

Photo of Query Dependencies

![last](https://github.com/user-attachments/assets/7a256abd-8ebe-4dda-8012-650acd1d353f)









