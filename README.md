# Habit_tracking_app_iU_project

**Intro**

The following is a project, that I’ve done in context of the course “Object Oriented and Functional Programming I with Python” at the “iU Internationale Hochschule”-University. The task was to create a solid habit-tracker app using Python as a programming language. Further we should build the tracker module of the app using the OOP (object oriented programming) paradigm and the analytics module with the FP (functional programming) paradigm. Here’s my gameplan:

1.	Create the Habit, User, and Tracker Classes for the habit tracking module.
2.	Implement the Analytics Module using functional programming principles.
3.	Create Sample Data as required in the task + to test the application.
4.	Provide Functions for users to add and track their own habits, and for analytics.
5.	Implement Analytics functions
6.	Create a User Interface (here: simple CLI)

**Step 1: Create the Habit, User, and Tracker Classes**

This should be done with OOP and contain following objects:

Habit Class

User Class

Tracker Class

**Step 2: Implement the Analytics Module**

Use functional programming to implement the analytics part. This includes functions to analyze streaks, habit periodicities and the habit with the longest streak.

**Step 3: Create Sample Data and Test the Application**

Create a user and some predefined habits with sample data to demonstrate the functionality.

**Step 4: Provide Functions for User Interaction**

These functions will allow users to add new habits, track existing ones, and view analytics.

**Step 5: Implementing the Analytics Functions**

1. Function to find the habit with the longest overall streak.
2. Function to list habits by periodicity.
3. Function to list all current habits.

These functions allow us to analyze habits based on their streaks and periodicity. You can use these functions to add new habits, mark habits as complete, and perform analytics on the habit data.

**Step 6: Creating a CLI for user interaction**

To implement a Command Line Interface (CLI) for the habit-tracking app was designed in a Jupyter Notebook. So it’s possible to use can use Python's built-in input function for user interaction. 

Create a simple menu-driven interface, where the user can choose different options like adding a habit, marking a habit as complete, and viewing analytics.
Here's what was implement:

1.	Main Menu Function: This will display the main menu and handle user input for different options.
2.	Supporting Functions: Functions to add a habit, mark a habit as complete, and show analytics.
3.	Looping Mechanism: To continuously run the CLI until the user decides to exit.

**Outlook for further development**

This solution is just one of many and reduced to the backend of such a habit-tracking-app. An app would of course profit from a more sophisticated, well designed graphical user interface on the frontend. 
Even if the aforementioned step is not considered, a more user-friendly way of displaying data could also be implemented with modules and libraries that do it graphically,, such as matplotlib.  
To make the app fully functional, it would be important to implement a proper data storage function, using json files or the DataFrame structure from the Pandas library for instance. 
Even if that app can easily be tested by simply running the code in Spyder or Jupyterlab etc., this step could also be automated by using a framework, such as pytest.
