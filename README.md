# **Java Queue Application**
## Introduction
This project can be used to create a queue of tasks with accompanying ID numbers and descriptions, listing out those tasks, and removing the tasks once they are completed.
## Project Description
This project was started with the creation of the model package for the Task class, the service package for the TaskQueueService class, and the app package for the QueueApp 
class. \
The Task class includes the private integer data field id, which will contain the ID number for each created task. It also includes the private String data field description, 
which will contain a description of the task that corresponds with the ID number. The Task class is complete with getter and setter methods for each data field, a constructor
that will create the Task object to go in the queue, and a toString() method to print the Task ID number and description. \
The TaskQueueService class is created to manage the queue using LinkedList. It includes the enqueue() method, which adds the Task object to the queue; the listTasks() method, 
which lists the Task objects that are currently in the queue; and the dequeue() method, which removes the Task object from the front of the queue. \
The QueueApp class includes the main method, which prompts the user to select from a menu what they want the application to do, including adding tasks, listing the queue,
removing tasks, or exiting the application. This menu will loop until the user selects the Exit option. 
## Instructions to Compile
javac -d bin src/app/QueueApp.java
## Instructions to Run
java -cp bin app.QueueApp
## User Information
Upon running the application, the user will be given a menu of choices \
===Task Menu=== 
1. Add Tasks. 
2. List Tasks. 
3. Remove Task.
4. Exit 

Enter your choice: 
  
The user will choose what they want to do. If they want to add a task, they will be prompted to provide an ID number and description to assign to the task. If they choose to
list the tasks, a list of the tasks currently in the queue will print. If they choose to remove a task, the task at the front of the queue will be removed. If they exit,
the application will close. 
## Assumptions
Upon creation of the project, the execution environment JRE selected was JavaSE-22.
