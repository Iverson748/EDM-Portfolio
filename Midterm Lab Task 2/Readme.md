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

Uncleaed Photo 3

![unc3](https://github.com/user-attachments/assets/15f3aa79-e7ab-4f60-81c3-40bb8d8cc0d5)

## After Cleaning

Cleaned Photo  1

![clean](https://github.com/user-attachments/assets/e8aff98e-d8ff-4ec7-93cc-ffc5c5913258)

Cleaned Photo 2

![clean 2](https://github.com/user-attachments/assets/7f7b4109-cc5f-4269-82cf-ea8be9fe307a)

## Step 2 - Reshaping and Grouping the Tables
Duplicate and reference Unclean DS Jobs to create new queries (Sal By Role Type dup, Sal By Role Size ref, Sal By State ref).

Select appropriate columns (Role Type, Size, Min Sal, Max Sal).

Change the columns to required data types (Currency).

Multiply Min Sal and Max Sal by 1000.

Group data by Role Type, Size, State Full Name to get averages.

Merge State Mapping with Unclean DS Jobs using State Abbreviation.

Rename merged column to State Full Name and remove nulls.

Check and review Query Dependencies.

## Grouped of Tables
Salary by Role Type Table
![1000018454](https://github.com/user-attachments/assets/4a9d54c0-1214-405e-9830-ddd551df36bc)

Salary by Size Role Type Table

![last](https://github.com/user-attachments/assets/1c17956d-8aab-4d35-9e91-51cfbac03b2b)

Salary by State Table

![1000018455](https://github.com/user-attachments/assets/b2e9b071-3c9e-492f-b4ba-7acfac4ccbb5)

States Mapping Table

![1000018456 (2)](https://github.com/user-attachments/assets/5a68f6ee-1dac-4c34-bed4-ae12736d6417)

## Step 3 - Query Dependencies
After all the previous steps, check the Query Dependencies in PowerQuery by going to view and selecting the Query Dependencies.
Double check whether they are properly linked appropriately.

Photo of Query Dependencies

![Depencies](https://github.com/user-attachments/assets/391710de-ce59-41f1-a75a-eb701b0c6d76)








