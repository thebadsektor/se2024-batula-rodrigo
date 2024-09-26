# SD-3101 [Class Scheduling System]

![Project Banner](https://github.com/oretnom23/php-class-scheduling-system/blob/master/scheduling.png)

## Table of Contents
- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
- [Usage Instructions](#usage-instructions)
- [Project Structure](#project-structure)
- [Contributors](#contributors)
- [Chagelog](#changelog)
- [Acknowledgments](#acknowledgments)
- [License](#license)

---

## Introduction
The Class Scheduling System is designed to help educational institutions manage class schedules efficiently, preventing conflicts such as overlapping room assignments or clashing time slots. This system automates the scheduling process, ensuring that classrooms and resources are allocated properly without manual errors.

By providing easy-to-use management tools, the system streamlines the organization of class and exam schedules, reducing administrative workload while maintaining accuracy.

## Project Overview
The Class Scheduling System is a web-based platform built with PHP and MySQLi, tailored for academic institutions like schools, colleges, and universities. Its primary purpose is to simplify the complex process of scheduling classes, exams, and room assignments. The system also includes features for managing teacher assignments, course sections, subjects, and academic years.

Target Audience:
- School administrators
- Academic schedulers
- Teachers

Real-World Applications:
- Automated scheduling prevents conflicts in room allocation and instructor availability.
- Helps schools manage academic schedules more effectively, improving operational efficiency.
## Objectives
The main objectives of this project are:

- Develop a conflict-free class scheduling system for academic institutions.
- Implement features that allow administrators to efficiently manage class schedules, exam schedules, teachers, and rooms.
- Ensure the system is user-friendly and easy to navigate for both administrators and other stakeholders.
- Test and validate the system to ensure accurate scheduling without conflicts.

## Features
Website Features:

- Exam Schedule Viewer: Displays upcoming exam schedules for students and teachers.
- Class Schedule Viewer: Shows detailed class schedules, including subjects, rooms, and instructors.
- News and Events: Allows the institution to post news and updates.
- About Page: Provides details about the school or institution.
- Site Map: Offers a structured overview of the website.
- Calendar of Events: Displays important academic events and holidays.

System Users Side:

- Login Page: Secure login for administrators to manage the system.
- Home Page: Central dashboard for administrators with key metrics and navigation.
- Class Schedule Management: Manage class schedules, ensuring no conflicts in time or room allocation.
- Exam Schedule Management: Organize and manage exam schedules.
- Teacher Management: Add, update, and manage teacher information.
- Course Year/Section Management: Manage course sections and year levels.
- Subject Management: Organize and manage the subjects offered by the institution.
- Room Management: Manage classroom availability and assignments.
- Department Management: Manage different departments within the school.
- Academic School Year Management: Organize the academic year and ensure accurate scheduling for each term.
- History Log: Keep track of system changes and user activity.
- User Account Management: Manage administrator and user accounts for accessing the system.

## Technologies Used

- Programming Language: PHP (server-side scripting)
- Database: MySQLi for database management
- Front-end Technologies: HTML, CSS, JavaScript
- Local Server: XAMPP for running the PHP scripts and managing the database locally
- Version Control: Git 

## Setup and Installation
Step-by-step instructions for setting up the project locally.

1. Download the Source Code:

   - Extract the zip file of the source code.

2. Set up a Local Web Server:

   - Download and install XAMPP or any other web server that supports PHP.

3. Create a Database:

   - Open your web-server’s database (e.g., using phpMyAdmin) and create a new database named "css".

4. Import the Database:

   - In phpMyAdmin, import the SQL file located in the db folder of the extracted source code.

5. Set Up the Project:

   - Copy the source code to your web server’s root directory. For example, if using XAMPP, paste the code in C:\xampp\htdocs\php-class-scheduling-system.

6. Access the Project:

   - Open a web browser and go to [http://localhost/php-class-scheduling-system] to view the website.
   - For admin access, visit [http://localhost/php-class-scheduling-system/admin].

Admin Default Access:
- Username: teph
- Password: teph

## Usage Instructions
Once the system is set up, follow these steps to begin using it:

1. Login:

   - Visit the admin panel at [http://localhost/online_class_scheduling_system/admin].
   - Log in using the default credentials or your own created admin account.

2. Class Scheduling:

   - Navigate to the "Class Schedule Management" section to begin scheduling classes.
   - Ensure that room availability and instructor assignments are conflict-free using the system’s automated conflict detection.

3. Exam Scheduling:

   - Use the "Exam Schedule Management" to schedule exams, and ensure that students, rooms, and times are properly assigned.

4. Manage Teachers, Rooms, and Courses:

   - Go to the relevant sections like "Teacher Management" or "Room Management" to update or manage teacher profiles and room availability.

## Project Structure
Explain the structure of the project directory. Example:
```bash
.
├── admin/
│   ├── contents/
│   ├── css/
│   ├── flash/
|   ├── img/
|   └── js/
├── db/
├── excel.php/
├── img/
└── README.md
```

## Contributors



- **Harold Batula**: Lead Developer, Backend Developer
- **John Benedict Rodrigo**: Frontend Developer, UI/UX Designer
- **Gerald Villaran**: Project Manager, Tester

## Project Timeline


- **Week 1-2**: Research and project planning.
- **Week 3-5**: Design and setup.
- **Week 6-10**: Implementation.
- **Week 11-12**: Testing and debugging.
- **Week 13-14**: Final presentation and documentation.

## Changelog

### [Version 1.0.0] - 2024-09-07
- Initial release of the project.
- Added basic functionality for [Feature 1], [Feature 2], and [Feature 3].

### [Version 1.1.0] - 2024-09-14
- Improved user interface for [Feature 1].
- Fixed bugs related to [Feature 2].
- Updated project documentation with setup instructions.

### [Version 1.2.0] - 2024-09-21
- Added new functionality for [Feature 4].
- Refactored codebase for better performance.
- Added unit tests for [Feature 3] and [Feature 4].


## Acknowledgments

Acknowledge any resources, mentors, or external tools that helped in completing the project.

This project was built from [php-class-scheduling-system](https://github.com/oretnom23/php-class-scheduling-system), created by oretnom23. You can view the original repository [here](https://github.com/oretnom23/php-class-scheduling-system).

## License

Specify the project's license. For starters, adapt the license of the original repository.
"# se2024-batula-rodrigo" 
"# se2024-batula-rodrigo" 
"# se2024-batula-rodrigo" 
"# se2024-batula-rodrigo" 
