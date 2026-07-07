# phpassignment1
phpbasic
A simple web application built using PHP and MySQL, demonstrating core CRUD operations, form validation, and basic database connectivity.

📌 Overview
This project is a beginner‑friendly PHP web application designed to show how a typical dynamic website interacts with a MySQL database. It includes:

Adding records

Viewing records

Validating form inputs

Connecting to a database

Basic UI using HTML & CSS

It’s ideal for students, junior developers, or anyone learning backend fundamentals with PHP.

🧱 Features
Create new entries using add.php

Read/View entries using view.php

Validate user input with validate.php

Database connection handled through db.php

Homepage served via index.php

Reusable components inside the includes/ folder

Database schema stored in the sql/ folder

Basic styling using CSS

📂 Project Structure
Code
phpbasic/
│
├── add.php          # Add new data
├── db.php           # Database connection
├── index.php        # Homepage
├── validate.php     # Input validation
├── view.php         # Display records
│
├── includes/        # Reusable components
├── css/             # Stylesheets
├── img/             # Images
├── sql/             # Database schema
│
└── README.md        # Project documentation
🗄️ Database
The sql directory contains the SQL file needed to create the required tables.
Import it into your MySQL server before running the project.

🚀 Getting Started
1. Clone the repository
bash
git clone https://github.com/mdanwarulkabir/phpbasic.git
2. Configure the database
Create a MySQL database

Import the SQL file from /sql

Update db.php with your database credentials

3. Run the project
Place the project folder inside your local server directory (e.g., htdocs for XAMPP) and open:

Code
http://localhost/phpbasic/
🛠️ Technologies Used
PHP

MySQL

HTML

CSS

👤 Author
Md Anwarul Kabir  
GitHub: https://github.com/mdanwarulkabir
