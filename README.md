# Habit_tracking_app_iU_project

**Intro**

The following is a project, that I’ve done in context of the course “Object Oriented and Functional Programming I with Python” at the “iU Internationale Hochschule”-University. The task was to create a solid habit-tracker app using Python as a programming language. Further we should build the tracker module of the app using the OOP (object oriented programming) paradigm and the analytics module with the FP (functional programming) paradigm. Here’s my gameplan:

1.	Create the Habit, User, and Tracker Classes for the habit tracking module.
2.	Implement the Analytics Module using functional programming principles.
3.	Create Sample Data as required in the task + to test the application.
4.	Provide Functions for users to add and track their own habits, and for analytics.
5.	Implement Analytics functions
6.	Create a User Interface (here: simple CLI)

Before you can start, you need to make sure you have access to programming tools that use the Python programming language. I highly recommend environments, such as Spyder or Jupyterlab. Here's how to install the Anaconda Distribution, where you can access both, Spyder and Jupyterlab.

**Installing Anaconda**

1. Download Anaconda:
Visit the Anaconda website and download the Anaconda Installer for your operating system (Windows, macOS, or Linux).

2. Run the Installer:
Windows: Open the downloaded .exe file and follow the installation instructions. Choose whether to add Anaconda to your PATH (not recommended by the installer but may be convenient for some users).
macOS: Open the downloaded .pkg file and follow the on-screen instructions.
Linux: Open a terminal, navigate to the directory containing the downloaded .sh file, and run bash Anaconda3-2020.02-Linux-x86_64.sh (adjust the file name as per the version you downloaded). Follow the on-screen instructions.

3. Verify Installation:
Open a terminal (or Anaconda Prompt on Windows) and type conda list. If Anaconda is correctly installed, you should see a list of installed packages.

**Working with Spyder**
Spyder is an IDE (integrated developement environment) designed for scientific Python development, featuring a powerful interactive console, advanced editing, debugging, visualization, and data exploration capabilities.

1. Launching Spyder:
You can launch Spyder from the Anaconda Navigator GUI, or by typing spyder in your terminal (or Anaconda Prompt on Windows).

2. Using Spyder:
Editor: Write your Python scripts or modules here. Spyder supports syntax highlighting, code completion, and more.
IPython Console: Execute Python commands interactively, view results, or run scripts from the Editor.
Variable Explorer: Inspect and interact with the variables created during your session.
Help: Access documentation for Python functions and modules.

**Working with JupyterLab**
JupyterLab allows you to create and share documents (notebooks) that contain live code, equations, visualizations, and narrative text.

1. Launching JupyterLab:
Open a terminal (or Anaconda Prompt) and run jupyter lab. Your default web browser will open with the JupyterLab interface.
2. Using JupyterLab:
Creating a Notebook: Click on the "New" button and select a Python 3 notebook to start coding.
Writing and Running Code: Type Python code into a cell, and press Shift + Enter to execute it. The output will appear beneath the cell.
Markdown Cells: Besides code, notebooks can contain Markdown cells for formatted text, equations, and images to create a rich, interactive document.
Saving and Sharing: Save your notebook with the .ipynb extension. Notebooks can be shared via email, GitHub, or other platforms.

Anaconda simplifies Python development, especially for data science and machine learning projects, by bundling a comprehensive suite of tools and libraries. Spyder and JupyterLab, included with Anaconda, cater to different aspects of the development process, from writing scripts to interactive exploration and presenting results.

But now let's see how my habit-tracker app solution looks like:

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
