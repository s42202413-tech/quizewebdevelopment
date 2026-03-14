Skip to content
Navigation Menu
Platform
Solutions
Resources
Open Source
Enterprise
Pricing

Sign in
Sign up
webproject2025
/
QuizWhiz-web-app
Public
Code
Issues
Pull requests
Actions
Projects
Security
Insights
webproject2025/QuizWhiz-web-app
Go to file
Name		
Eba1623
Eba1623
Merge pull request #22 from webproject2025/ebisa
a3efd8e
 · 
10 months ago
Public
some project folder structure and adjustments on the explore page.
10 months ago
api
fixed leader board fetch data
10 months ago
assets/images
Initial commit: Core features implemented
11 months ago
backend
Merge pull request #18 from webproject2025/kakidan
10 months ago
components
Create header.html
10 months ago
config
some project folder structure and adjustments on the explore page.
10 months ago
database
added sidebar components and restructured project folder
10 months ago
src
High score Tracking and Functionality of Leaderboard and some others …
10 months ago
utils
added sidebar components and restructured project folder
10 months ago
.gitignore
Initial commit: Core features implemented
11 months ago
README.md
README Modification.
10 months ago
database.sql
explore page added.
10 months ago
setup_database.php
added sidebar components and restructured project folder
10 months ago
Repository files navigation
README
QuizWhiz+ – Web-Based Quiz App
QuizWhiz+ is an interactive quiz web application built using HTML, CSS, JavaScript, and PHP, with MySQL as the backend database. It supports multiple quiz categories, live scoring, answer review, a leaderboard, theming options, and a fully responsive design.

🔧 Built as part of a Web Development course project. No external libraries or frameworks were used.

🚀 Features
🧠 Quiz Categories (Science, HTML, Logic, etc.)
🎚️ Difficulty Levels (Easy, Medium, Hard)
📝 Answer Review with Explanations
💡 Instant Feedback (Correct/Incorrect)
🌗 Dark/Light Theme Toggle
🏆 Leaderboard System with Score Persistence
📱 Responsive Design (Mobile/Desktop)
🛠️ Installation & Setup
To run the project locally, follow these steps:

1. Clone the Repository
git clone https://github.com/your-username/QuizWhiz-web-app.git

Copy or move the folder into your htdocs directory if you're using XAMPP:
C:\xampp\htdocs\QuizWhiz-web-app

###2. Start XAMPP
Launch XAMPP Control Panel

Start Apache and MySQL

###3. Import the Database
Open your browser and go to phpMyAdmin.

Create a new database named: quiz

Import the SQL file:

Go to the Import tab

Choose the file: database/quiz_tables.sql

Click Go

###4. Open the App
Navigate to the app in your browser:
http://localhost/QuizWhiz-web-app/public/pages/index.html

🔐 Test Credentials
Use the following test accounts to log in:

Email	Password
john@example.com	password
jane@example.com	password

📁 Project Structure

QuizWhiz-web-app/
│
├── database/
│   ├── quiz_tables.sql          # Database schema
│   └── setup_database.php       # Optional setup script
│
├── public/
│   ├── pages/                   # HTML pages
│   ├── js/                      # JavaScript files
│   └── styles/                  # CSS styles
│
├── api/                         # PHP APIs (e.g., get_quizzes.php)
├── README.md                    # This file
└── .gitignore

❓ FAQ
Q: I don't know where to start!
A: Visit the Project Board and pick a task from the "To Do" column.

Q: Who do I ask for help?
A: Ask @Abdataa via GitHub, or check the issue discussions.
📱 Telegram: @abdataa123

📘 License
This project is intended for educational use only.
No commercial or production deployment is permitted.

Thanks for being part of the QuizWhiz+ team! 🎉
About
No description, website, or topics provided.
Resources
 Readme
 Activity
 Custom properties
Stars
 0 stars
Watchers
 1 watching
Forks
 0 forks
Report repository
Releases
No releases published
Packages
No packages published
Contributors
5
@Eba1623
@Abdataa
@ezexkedir19
@amir935
@kamlakineh
Languages
HTML
49.0%
 
PHP
22.3%
 
CSS
19.3%
 
JavaScript
9.4%
