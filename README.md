# Readme

## This is a simple task management program written in Python. It allows users to register, login, add tasks, remove tasks, display tasks, update tasks, mark tasks as done, save tasks, and exit the program.

## Getting Started

#### * To use this program, follow the instructions below:

##### 1. Make sure you have Python installed on your computer.
##### 2. Download the code file to your local machine or copy the code into a new Python file.
##### 3. Open a terminal or command prompt and navigate to the directory where the code file is located.

## Usage

### Register

#### * To register a new user, run the program and enter the following information when prompted:

##### • Username: Enter your desired username.
##### • Create Password: Enter a password for your account.
##### • Confirm Password: Re-enter the password to confirm.

#### If the password and confirmation match, your registration will be successful, and the data will be saved in a file named "Data.txt".

### Login

##### * To log in as a registered user, run the program and enter your username and password when prompted. The program will check the provided credentials against the registered users' data in the "Data.txt" file. If the credentials match, you will be logged in successfully.

### Add Task

#### * To add a new task, choose option 1 from the menu. Enter the task description and the deadline in the format "Year-Month-Day Hour:Minute:Second" when prompted. The task will be added to the task list.

### Delete Task

#### * To remove a task, choose option 2 from the menu. Enter the task you want to remove when prompted. If a matching task is found in the task list, it will be removed.

### Display Tasks

#### * To display all the tasks, choose option 3 from the menu. The program will show the task index, description, and deadline for each task in the task list.

### Change Task

#### * To update a task, choose option 4 from the menu. Enter the task you want to update when prompted. If a matching task is found, enter the new task description. The program will update the task with the new description.

### Mark as Done

#### * Option 5 is currently not implemented in the code. You can modify the code and add the functionality to mark tasks as done.

### Save and Exit

#### * To save the tasks and exit the program, choose option 6 from the menu. The program will save the task list in a file named "tasks.pickle" using Python's pickle module. This allows you to load the tasks the next time you run the program.

### Data Persistence

#### * The program uses two files for data persistence:

##### • "Data.txt": This file stores the registered users' data in the format "username:password". Each registered user is stored on a separate line.
##### • "tasks.pickle": This file stores the task list using Python's pickle module. It allows the program to load and save the tasks between program runs.



###  ➦ Feel free to modify and improve the code according to your needs and requirements.


















