# Data_driven_testing : Excel Data Manipulation Script with OpenPyXL

## Description

This Python script demonstrates how to use the `openpyxl` library to manipulate an Excel file. It loads an existing Excel file, writes header values and sample data into it, and then saves the file. The script currently works on an Excel file named `testdata.xlsx` and updates data in the first sheet.

## Features

- Load an existing Excel file.
- Write headers and data to the first sheet of the Excel file.
- Save changes to the file.
- Outputs a success message upon completion.

## Prerequisites

Before running the script, ensure you have the following installed:

- Python 3.x
- `openpyxl` library

To install the `openpyxl` library, run the following command:

```bash
pip install openpyxl

Once after installing the dependecies, update the file variable in the script to point to the correct location of the testdata.xlsx file on your machine.
file = "C:/Users/LENOVO/Documents/Omkar/testdata.xlsx"

Execute the Python script using the below command:
python script_name.py

## Expected Output

The script will:

Open the Excel file located at the specified path.
Write the following headers into the first row of the Excel sheet:
SID
NAME
ROLE
Populate the second and third rows with the following sample data:
Row 2: 567, john, manager
Row 3: 567, david, developer
Save the changes back to the same Excel file.
Upon successful execution, the following message will be printed:

Successfully written data into excel
