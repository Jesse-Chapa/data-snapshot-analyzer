1. Project Overview

Data Snapshot Analyzer is a Python Tkinter GUI application that allows users to load and quickly analyze basic datasets in CSV format.
It provides easy-to-read summaries such as:

Row and column counts

Missing value checks

Descriptive statistics (mean, median, mode)

The goal is to support beginner data analysts, students, or anyone needing fast insights without writing code.



2. 🎯 Features
Load a dataset from a CSV file

Display number of rows, columns, and missing (null) values

Show descriptive statistics for numeric columns (mean, median, mode)

User-friendly, modular interface

Ability to load a new file or exit the application

Input validation to ensure proper file handling



3. 🖥️ GUI Structure

Window 1: Main Menu

Upload CSV file (file dialog)

Display file name, number of rows, and columns

Button to proceed to statistics view


Window 2: Statistics Display

Table/text area showing:

Null values per column

Mean, median, and mode

Button to load another file

Button to exit



4. 🛠️ Requirements

Python 3.8+

tkinter (standard with Python)

pandas library for data analysis

os module for file path handling



5. 🎯 Project Goals

✅ Create two distinct GUI windows

✅ Implement three or more labels

✅ Include three or more buttons with callback functions

✅ Integrate two images/icons (optional)

✅ Ensure input validation (check file types and data)

✅ Conduct validation testing with different CSV types

✅ Provide detailed user documentation

✅ Fully comment the source code



6. 👥 Target Audience

Age Range: 18–40 years old

Gender: All

Background: Students, entry-level professionals, and self-learners

Technical Skill: Basic spreadsheet skills, little to no coding experience


7. 📦 Installation Instructions

Clone or download this repository.

Make sure you have Python installed.

Install dependencies:
	pip install pandas
Run the program:
	python data_snapshot_analyzer.py


8. 🧪 Testing

Testing involved uploading:

Small datasets (under 500 rows)

Large datasets (over 10,000 rows)

Datasets with missing/null values

Empty or malformed CSV files (validation tested)