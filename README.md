# Employee-Review-System
The Employee Review System is a web-based application that provides both Admin and Employee views. The system allows authorized users to manage employees, performance reviews, and feedback in a seamless manner.

![image](https://github.com/pk1114585/EmployeeReviewSystem/assets/45114125/e1ed32a2-2cc4-4071-b447-74cfeb5e082c)


### Description

The Employee Review System is a web application built using a modern tech stack, including Node.js, Express.js, MongoDB, EJS (Embedded JavaScript), JavaScript, HTML, and CSS. This comprehensive system is designed to streamline and enhance the employee performance review process within an organization.

## Key Features:

User Authentication:
The system employs secure user authentication, allowing employees and admin users to log in using their unique credentials. This ensures that only authorized personnel can access specific features and data.

Employee Management:
Admin users have complete control over employee data. They can add new employees to the system, remove them, and update their information as needed. This feature facilitates efficient employee data management.

Performance Review Creation and Management:
Admin users can create performance reviews for employees, defining review criteria, timelines, and objectives. The system allows for easy management and tracking of ongoing and past reviews.

Feedback Mechanism:
Employees are assigned to participate in their peers' performance reviews, contributing valuable feedback to evaluate their colleagues' performance. This 360-degree feedback mechanism fosters a collaborative and developmental work environment.

EJS Templating:
The system utilizes EJS templating for dynamic content generation, allowing the server to render HTML pages with dynamic data. This ensures a smooth and interactive user experience.

Responsive Design:
The application's user interface is designed with HTML and CSS, following modern web design principles, ensuring responsiveness across various devices and screen sizes.

Data Persistence with MongoDB:
The system uses MongoDB as the database to store employee data, performance reviews, and feedback. This ensures robust data storage and retrieval capabilities.

CRUD Operations:
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
  
  
  # HomePage 
  ![image](https://github.com/pk1114585/EmployeeReviewSystem/assets/45114125/a5bdb27a-3c65-4ce3-ba2d-bfbf33522f9a)

  # Sign-In
  ![image](https://github.com/pk1114585/EmployeeReviewSystem/assets/45114125/d7aab87c-5289-4973-a738-173c83d13e21)

  # Sign-Up
  ![image](https://github.com/pk1114585/EmployeeReviewSystem/assets/45114125/17f278aa-aa13-443d-8a2c-808e27670da4)

  # Forget Password
  ![image](https://github.com/pk1114585/EmployeeReviewSystem/assets/45114125/92fd5d96-14c3-45a7-beb9-62e353c90db8)

  # Admin home screen
  ![image](https://github.com/pk1114585/EmployeeReviewSystem/assets/45114125/bcf8b022-71f0-4c83-9a93-bd050aa1fd7b)

  # Assign Task
  ![image](https://github.com/pk1114585/EmployeeReviewSystem/assets/45114125/d4f0d145-0cc8-4223-8a3e-1ee1a4700bfc)

  # Employee List
  ![image](https://github.com/pk1114585/EmployeeReviewSystem/assets/45114125/51fde2fc-a742-429a-aad5-adbdce7fa5e5)

  # User After login
  ![image](https://github.com/pk1114585/EmployeeReviewSystem/assets/45114125/e4e9ee09-33f8-4a16-8852-fc2b069b7f2f)

  ![image](https://github.com/pk1114585/EmployeeReviewSystem/assets/45114125/d38c411e-52f1-4323-b93f-32f3d1d4e099)

  
  ### MongoDB 
  # User DB
  ![image](https://github.com/pk1114585/EmployeeReviewSystem/assets/45114125/52126581-e982-4d0e-88c9-537a906aa75d)

  # User review
  ![image](https://github.com/pk1114585/EmployeeReviewSystem/assets/45114125/6fc6abad-6fc4-4bac-9fad-e1ad79dc8b66)


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
