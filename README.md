# COMPS350F-Academic-Registry-Portal

## Overview
This Jupyter notebook contains the code for an IT Technician Version of an academic record system. It utilizes PySimpleGUI for the graphical user interface and pandas for data manipulation.

!THIS PROJECT CAN'T RUN ON COLAB!

YOU SHOULD RUN IT ON LOCAL JUPYTER NOTEBOOK. 

## Setup (Using in-browser Jupyter Notebook)
- 1. install the Python
- 2. use terminals to "pip install jupyter notebook" .
- 3. Extract the all the project file into same directory.
- 4. Run Academic-Registry-Portal.ipynb
- 5. At "Run" column, select run all cells.
- 6. The program should be exexuted, a window should be poped out.
  
## Setup: (VSCode) 
- 1. Download and install Python
- 2. Run file using the Run all button on top
- 3. Open Terminal input "pip install PySimpleGUI==4.60.5" to install PySimpleGUI
- 4. Open Terminal input "pip install pandas==1.4.4" to install Pandas
- 5. When prompted update pip using the "python.exe -m pip install --upgrade pip" command in terminal
- 6. Wait for dependencies to be installed
- 7. Run all when done

## Project Setup 
If you are running this code for the first time, please run the setup code at the beginning of the notebook. 

This includes installing required packages using pip. If you already installed you can choose to comment these line to improve setup time.

student-dataset.csv and Academic-Registry-Portal.ipynb should in the same file.

## Usage
To run the notebook, simply execute the cells in order. The notebook provides a graphical interface for managing academic records, including functionalities for updating, sorting, and searching records.
You need to RUN ALL of the code.
### Student Account
- account: student full id
- password: student id without 's'
  
For example: student id s1311002
- login account: s1311002
- login password: 1311002
### Teacher Account
- account: t123456
- password: t123
### IT Technician Account
- account: i123456
- password: itt123

## Dependencies
- PySimpleGUI==4.60.5
- pandas==1.4.4

## File Structure
- Academic-Registry-Portal.ipynb: The main Jupyter notebook file.
- student-dataset.csv: The dataset used by the notebook.

## Author
Hong Kong Metropolitan University (2023/24)
COMPS350F Group 29 - Lu Yuk Tong(13439007)
 
