# Campus Hub

A centralized web portal designed to streamline campus activities and student resource management.

---

##  About the Project
This project was built to solve the fragmentation of student resources. Instead of checking multiple sites, students can find everything in one place—from event updates to tracking their own coursework.

---

##  Features
*   **User Authentication:** Secure login system for students.
*   **Events Board:** Real-time updates on campus activities and registrations.
*   **Task Management:** A personal dashboard to manage study tasks and deadlines.
*   **Lost & Found:** A community-driven system with full **CRUD** functionality to report and find items.
*   **Responsive Design:** Fully functional on both desktop and mobile browsers.

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
