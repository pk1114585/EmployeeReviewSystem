# Employee-Review-System
The Employee Review System is a web-based application that provides both Admin and Employee views. The system allows authorized users to manage employees, performance reviews, and feedback in a seamless manner.



### Description

The Employee Review System is a web application built using a modern tech stack, including Node.js, Express.js, MongoDB, EJS (Embedded JavaScript), JavaScript, HTML, and CSS. This comprehensive system is designed to streamline and enhance the employee performance review process within an organization.

## Key Features:

# User Authentication:
The system employs secure user authentication, allowing employees and admin users to log in using their unique credentials. This ensures that only authorized personnel can access specific features and data.

# Employee Management:
Admin users have complete control over employee data. They can add new employees to the system, remove them, and update their information as needed. This feature facilitates efficient employee data management.

# Performance Review Creation and Management:
Admin users can create performance reviews for employees, defining review criteria, timelines, and objectives. The system allows for easy management and tracking of ongoing and past reviews.

# Feedback Mechanism:
Employees are assigned to participate in their peers' performance reviews, contributing valuable feedback to evaluate their colleagues' performance. This 360-degree feedback mechanism fosters a collaborative and developmental work environment.

# EJS Templating:
The system utilizes EJS templating for dynamic content generation, allowing the server to render HTML pages with dynamic data. This ensures a smooth and interactive user experience.

# Responsive Design:
The application's user interface is designed with HTML and CSS, following modern web design principles, ensuring responsiveness across various devices and screen sizes.

# Data Persistence with MongoDB:
The system uses MongoDB as the database to store employee data, performance reviews, and feedback. This ensures robust data storage and retrieval capabilities.

# CRUD Operations:
The system implements CRUD (Create, Read, Update, Delete) operations for managing employee data, performance reviews, and feedback. This provides full data management functionality.

Overall, the Employee Review System offers a secure, user-friendly, and efficient solution for managing the performance review process within the organization. It promotes transparency, fosters a culture of feedback, and empowers employees to contribute actively to the evaluation and development of their peers. With its modern tech stack and well-designed features, the system enhances productivity and facilitates continuous improvement in the workplace.

### Tech Stack

Node , Express, Mongodb , EJS , javaScript , html, css

### How to setup the project on local system

  1. Clone this project
  2. Start by installing npm if you don't have it already.
  3. Navigate to Project Directory.

After reaching the project directory you have to run the following the command.
   ```` 
        npm install 
        npm start || nodemon index.js
   ````

#### If you want to make an employee as admin then use the secret key : pradeep.

### Features

  You can review the employees. The admin has the special power to assing, the task to employee, remove the employee, add new admin, and also employee;
  
  
  # HomePage / Admin View
  
  
  # Home page / Employee view
  
  
  # Sign-Up
  

  # Sign-In
  

  # Forget Password
  
  
  # Assign Task
  

  # Employee List
  

  

### Folder Structure

```
Employee Review System
    |
    |               |--->css
    |--->assets---->|--->images
    |             
    |
    |               |--->flashMiddleware.js
    |--->config---->|--->mongoose.js
    |               |--->passport-local-Stradegy.js
    |
    |                  |-->admin_controller.js
    |--->controllers-->|-->home_controller.js
    |                  |-->review_controller.js
    |                  |-->user_controller.js
    |
    |               |-->review.js
    |--->models---->|
    |               |-->user.js
    |
    |              
    |               |-->admin.js
    |--->routes---->|-->index.js
    |               |-->review.js
    |               |-->user.js
    |
    |              |--->_header.ejs
    |              |---> addEmployee.ejs
    |              |---> admin.ejs
    |              |---> employe.ejs
    |--->views---->|--->forget_password.ejs
    |              |--->home.ejs
    |              |--->layout.ejs
    |              |--->sign_in.ejs
    |              |--->sign_up.ejs
    |
    |-->node_modules
    |-->.gitignore
    |--> index.js
    |--> package-lock.json
    |-->package.json
    
    ````
