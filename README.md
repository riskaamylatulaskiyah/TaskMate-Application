# TaskMate Project

## Introduction
This TaskMate (To-Do List) application is developed to help users manage their daily task lists. The application features the ability to add, delete, and mark tasks as completed.

## Business Objectives
- **Efficiency:** Enhance the efficiency of daily task management.
- **Organization:** Help users stay organized.
- **Productivity:** Increase productivity by prioritizing tasks.

## Solution
A user-friendly web-based To-Do List application that allows users to manage their tasks quickly and efficiently.

## Urgency
Using task management applications has become increasingly important in everyday life to organize work and other activities.

## Technologies Used
- **HTML:** Web page structure.
- **CSS:** Web page styling.
- **JavaScript:** Interaction and dynamic functionality.
- **PHP:** Backend and database management.
- **MySQL:** Data storage.

## Installation and Usage
1. **Install XAMPP:**
   - Download and install XAMPP from [https://www.apachefriends.org/index.html](https://www.apachefriends.org/index.html).
   - Run Apache and MySQL through the XAMPP Control Panel.

2. **Project Setup:**
   - Create a `todo-list` folder inside the XAMPP `htdocs` folder.
   - Create the folder structure as follows:
     ```
     TaskMate/
     ├── css/
     │   └── style.css
     ├── js/
     │   └── script.js
     ├── includes/
     │   └── db.php
     ├── add_task.php
     ├── complete_task.php
     ├── delete_task.php
     └── index.php
     ```

3. **Database Connection:**
   - Open `phpMyAdmin` and create a database `taskmate_db`.
   - Create the `tasks` table with the following SQL query:
     ```sql
     CREATE TABLE `tasks` (
       `id` int(11) NOT NULL AUTO_INCREMENT,
       `task` varchar(255) NOT NULL,
       `status` enum('pending','completed') NOT NULL DEFAULT 'pending',
       PRIMARY KEY (`id`)
     ) ENGINE=InnoDB DEFAULT CHARSET=utf8;
     ```

4. **Running the Application:**
   - Open a browser and navigate to `http://localhost/taskmate`.
   - Add new tasks, mark them as completed, and delete tasks as needed.

## Application Demo
A demo of the TaskMate application can be seen in the following image:
![Application Demo](./demo-screenshot.png)

## Marketing and Application
This application can be applied in various fields such as education, business, and personal life to improve time management and productivity.

## Results
This TaskMate application has helped many users manage their daily tasks more effectively.

## How to Use the Application
- **Add Task:** Fill out the form and click "Add Task".
- **Mark Task:** Click the "Complete" button to mark a task as completed.
- **Delete Task:** Click the "Delete" button to delete a task.

## Contact
For more information, contact: riskaamylatulaskiyah@gmail.com

