# Attendance-Monitoring-System

This is a simple command-line program written in C++ that allows users to manage attendance data for a group of students. The program can perform the following tasks:

1. View attendance data
2. Search for a student
3. Edit attendance data for a student
4. View attendance history for a student
5. Export attendance data to a CSV file

## Getting Started
To use the program, simply download the main.cpp file and compile it using a C++ compiler such as g++ or Visual Studio. The program has been tested on Windows and Linux.

## Usage
Upon running the program, users will be presented with a menu of options. They can select an option by entering the corresponding number and pressing enter. Here are the available options:

1. View attendance data: Displays a list of all the students and their attendance status (present or absent) for the current date.
2. Search for a student: Allows users to search for a specific student by name or ID number, and view their attendance data.
3. Edit attendance data for a student: Allows users to edit the attendance data for a specific student.
4. View attendance history for a student: Allows users to view the attendance history for a specific student, including dates and whether they were present or absent.
5. Export attendance data to a CSV file: Allows users to export the attendance data to a CSV file, which can be useful for generating reports or analyzing the data in other programs.
6. Exit: Exits the program.

## Features
Here are some of the key features of the program:

- Data is stored in an array of structs that contain information about each student, including their name, ID number, and attendance status.
- The program can save and load data to/from a text file to preserve attendance data between sessions.
- The program implements input validation to ensure that only valid inputs (1 for present and 0 for absent) are accepted.
- The program can export attendance data to a CSV file, which can be opened in spreadsheet software such as Microsoft Excel or Google Sheets.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
