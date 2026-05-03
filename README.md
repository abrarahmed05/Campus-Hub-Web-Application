# Campus Hub

Campus Hub is a full-stack web application designed to centralize student activities, including events, task management, lost & found, and resource sharing, into a single platform.


##  About the Project
This project was built to solve the fragmentation of student resources. Instead of checking multiple sites, students can find everything in one place—from event updates to tracking their own coursework.

---

##  Features

- Academic calendar and task management  
-  Events board with RSVP functionality  
-  Lost & found system  
-  Resource sharing platform  
-  Admin announcements system  
-  Role-based access (Student & Admin)

---

## Tech Stack
*   **Frontend:** HTML5, CSS3, JavaScript, jQuery
*   **Backend:** Node.js
*   **Database:** MySQL

---

## Installation & Setup

Follow these steps to run **Campus Hub** locally:

### 1. Prerequisites
Ensure you have the following installed:
*   **Node.js** (v14 or higher)
*   **MySQL**

### 2. Database Setup
1. Open your MySQL terminal or workbench.
2. Create a new database:
   ```sql
   CREATE DATABASE studenthub;
Import the schema:

Locate the studenthub.sql file in the project directory.

Run the following command in your terminal:

Bash
mysql -u your_username -p studenthub < studenthub.sql
3. Project Configuration
Clone the repository:

Bash
git clone https://github.com/abrarahmed05/Campus-Hub-Web-Application.git
Navigate into the project folder and install dependencies:

Bash
cd Campus-Hub-Web-Application
npm install
Environment Variables:
Create a file named .env in the root directory and add your MySQL credentials:

Plaintext
DB_HOST=localhost
DB_USER=your_mysql_username
DB_PASS=your_mysql_password
DB_NAME=studenthub
PORT=3000
4. Running the App
Start the backend server:

Bash
node server.js
The server will start on http://localhost:3000. 

## Author
Abrar Ahmed

GitHub: abrarahmed05

## License
This project is licensed under the MIT License.
