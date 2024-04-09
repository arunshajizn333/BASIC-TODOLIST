Basic Todo List
This is a simple Todo List web application built using Node.js, Express.js, PostgreSQL, and EJS template engine.

Table of Contents
Description
Features
Installation
Usage
Database Setup
License
Description
The Basic Todo List is a web application that allows users to manage their daily tasks. Users can add, edit, and delete tasks from the list.

Features
Add new tasks to the list.
Edit existing tasks.
Delete tasks from the list.
View tasks in a sorted manner.
Responsive design for various screen sizes.
Installation
To run this project locally, follow these steps:

Clone the repository:
bash
Copy code
git clone https://github.com/arunshajizn333/BASIC-TODOLIST.git
Install dependencies:
bash
Copy code
cd BASIC-TODOLIST
npm install
Usage
After installing the dependencies, you can start the application by running:

bash
Copy code
npm start
The application will be accessible at http://localhost:3000 by default.

Database Setup
This application uses PostgreSQL as the database. Make sure you have PostgreSQL installed and running on your system. Create a database named TODOLIST and execute the following SQL commands to set up the required table and initial data:

sql
Copy code
CREATE TABLE items (
  id SERIAL PRIMARY KEY,
  title VARCHAR(100) NOT NULL
);


Make sure to update the database configuration in index.js file if your PostgreSQL setup requires different credentials.

License
This project is licensed under the MIT License - see the LICENSE file for details.
