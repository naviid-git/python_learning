Astronomy Observation Logger

A Python command-line application for recording, storing, searching, and analyzing astronomical observations.

Features

The application provides the following features:

1. Add Observation: Enter a target name, exposure time, observer name, and filter name. The observation is saved to an SQLite database.
2. Show Observations: Display all recorded observations.
3. View Data with Pandas: Load and display observations in a Pandas DataFrame.
4. Calculate Statistics: Calculate total, average, maximum, and minimum exposure times.
5. Search Observations: Search for observations by target name.
6. Plot Exposure Time: Create a bar chart showing exposure time for each target.
7. Export Data: Save observation records to a CSV file.
8. Exit: Close the application.

Technologies

- Python
- SQLite and SQL
- Pandas
- Matplotlib

Database Structure

The SQLite database stores the following fields:

- "ID": Unique observation ID
- "target": Name of the astronomical target
- "exposure": Exposure time in seconds
- "observer": Name of the observer
- "filter_name": Filter used for the observation

Installation

Install the required Python libraries:

pip install pandas matplotlib

How to Run

Run the main Python file:

python main.py

Follow the menu instructions to select an operation.

Project Workflow

1. Start the application.
2. Add an astronomical observation.
3. Save the observation to the SQLite database.
4. View, search, and analyze recorded observations.
5. Visualize exposure times using a bar chart.
6. Export the data to a CSV file.

Project Status

This project is a work in progress developed for learning Python, database management, data analysis, and visualization.

Future Improvements

- Add a graphical user interface (GUI).
- Improve input validation and error handling.
- Add date and time information to observations.
- Improve search and filtering capabilities.
