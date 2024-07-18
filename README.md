This project focuses on the management of employee salary data. Follow these steps to import, process, and export employee details using Python and R.

Prerequisites
Python: Ensure Python is installed on your computer.
R: Ensure R is installed on your computer.
Steps to Use the Code
1. Import Salary Data
First, import the salary data into your Jupyter Notebook. Ensure the file salary_data.csv is in the same folder as your notebook. You'll use Python to read this file.

2. Create a Function to Get Employee Details
Next, create a function in Python that takes an employee's name and returns their details such as name, salary, and department. This function will search through the salary data and find the relevant information.

3. Process Data Using a Dictionary
The function will store and return employee details using a dictionary, a simple data structure in Python that holds key-value pairs.

4. Handle Errors
The function will include error handling to show a message if the employee name isn't found in the data. This ensures the program doesn't crash and provides useful feedback.

5. Export Employee Details
Create another function in Python to export an employee's details to a CSV file. Save this file in a folder named "Employee Profile," and then zip this folder. This makes it easy to share or store the employee details securely.

6. Unzip and Display Data with R
Finally, use R to unzip the folder and display the data. This step involves reading the CSV file back into R and showing the employee details.

Example Usage
Get Employee Details: Use the function to get details of an employee by their name.
Export Employee Profile: Use the function to save the employee's details to a CSV file and zip the folder.
Unzip and Display Data in R: Use R to unzip the folder and read the CSV file to display the employee details.
