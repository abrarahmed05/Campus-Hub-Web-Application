# Campus-Hub-Web-Application
A centralized web portal designed to streamline campus activities and student resource management.

# About the Project
This project was built to solve the fragmentation of student resources. Instead of checking multiple sites, students can find everything in one place—from event updates to tracking their own coursework.

# Features
User Authentication: Secure login system for students.

Events Board: Real-time updates on campus activities and registrations.

Task Management: A personal dashboard to manage study tasks and deadlines.

Lost & Found: A community-driven system with full CRUD functionality to report and find items.

# Tech Stack
Frontend: HTML5, CSS3, JavaScript, jQuery

Backend: Node.js

Database: MySQL

## Installation & Setup

Follow these steps to run Campus Hub locally:

### 1. Prerequisites

Make sure you have installed:
- Node.js (v14 or higher)
- MySQL

---

### 2. Database Setup

1. Open MySQL (terminal or Workbench)

2. Create a database:
```sql
CREATE DATABASE studenthub;

Import the schema:
    *   Locate the `studenthub.sql` file in the project directory.
    *   Run the following command in your terminal:
    ```bash
    mysql -u your_username -p studenthub < studenthub.sql
    ```

### 3. Project Configuration
1.  Clone the repository:
    ```bash
    git clone https://github.com/abrarahmed05/Campus-Hub-Web-Application.git
    cd Campus-Hub-Web-Application
    ```
2.  Install the required dependencies:
    
```bash
    npm install
    ```
3.  **Environment Variables:** 
    Create a file named `.env` in the root directory and add your MySQL credentials:
    ```text
    DB_HOST=localhost
    DB_USER=your_mysql_username
    DB_PASS=your_mysql_password
    DB_NAME=studenthub
    PORT=3000
    ```

### 4. Running the App
Start the backend server:
```bash
node server.js

# Author
Abrar Ahmed

GitHub: abrarahmed05

# License
This project is licensed under the MIT License.
