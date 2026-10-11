# CollegeConnect 🎓

**Smart College Resource Management Platform**

CollegeConnect is a web-based platform designed to simplify college resource management by bringing classroom availability, academic timetables, and campus complaint management together in one place. It helps students and faculty access important college information while supporting more efficient classroom utilization and infrastructure maintenance.

## ✨ Features

### 🏫 Classroom Availability
- Search for available classrooms based on the selected day and time slot.
- Filter classroom searches by branch and division.
- Identify classrooms that are not occupied according to the stored timetable.

### 📅 Timetable Management
- Access branch-wise and division-wise timetables.
- View scheduled subjects, professor codes, time slots, and classroom locations.
- Organize timetable information to support classroom availability checks.

### 🛠️ Complaint Management
- Register campus infrastructure complaints, such as AC issues, smart board failures, and Wi-Fi problems.
- Track complaints through their management workflow.
- Support complaint assignment and resolution workflows for authorized users.

### 👥 Role-Based Access
- Provide a centralized platform for students, class representatives (CRs), and professors.
- Support role-specific actions and interfaces.
- Use authentication to manage access to protected functionality.

### 📊 Dashboard
- View available classroom counts.
- Monitor occupied classrooms.
- Track active complaints.

## 🧰 Tech Stack

**Frontend**
- HTML5
- CSS3
- JavaScript

**Backend**
- Python
- Flask
- Flask-CORS

**Database**
- MySQL

**Development Tools**
- Visual Studio Code
- MySQL Workbench
- Git and GitHub

## 📁 Project Structure

```text
CollegeConnect/
├── assets/
├── backend/
│   ├── app.py
│   ├── db.py
│   └── requirements.txt
├── css/
├── database/
│   └── schema.sql
├── js/
├── index.html
├── dashboard.html
├── classrooms.html
├── timetable.html
├── complaints.html
├── login.html
├── .env.example
├── .gitignore
└── README.md
```

*Note: The structure above represents the main project files. Additional files may exist in individual folders.*

## ⚙️ Getting Started

### Prerequisites

Install the following before running the project:

- Python 3
- MySQL Server
- MySQL Workbench (recommended)
- Visual Studio Code
- Git

### 1. Clone the Repository

```bash
git clone <YOUR-GITHUB-REPOSITORY-URL>
cd CollegeConnect
```

### 2. Set Up the Python Environment

```bash
cd backend
python -m venv venv
```

Activate the virtual environment on Windows:

```powershell
.\venv\Scripts\Activate.ps1
```

Install the backend dependencies:

```bash
pip install -r requirements.txt
```

### 3. Configure the Database

1. Start your MySQL server.
2. Open MySQL Workbench.
3. Create the required database.
4. Execute the SQL statements in `database/schema.sql`, if it contains the project schema.
5. Configure your database connection settings using environment variables.

Create a `.env` file in the project root based on `.env.example`. Add your local database configuration and other required environment variables.

**Security:** Never commit your `.env` file, passwords, database credentials, or API keys to GitHub.

### 4. Start the Backend

From the `backend` directory, activate the virtual environment if it is not already active, then run:

```bash
python app.py
```

The backend is configured to run locally on:

```text
http://127.0.0.1:5000
```

### 5. Launch the Frontend

Open the project in Visual Studio Code and launch `index.html` using the Live Server extension, or use the frontend setup configured for your project.

Make sure the frontend API configuration points to the correct backend URL.

## 🔐 Security and Access

- Keep credentials in environment variables rather than source code.
- Use the application's login system for protected functionality.
- Configure role permissions appropriately before deploying the platform for real college-wide use.

## 🚀 Future Enhancements

- Expand timetable support across all branches and divisions.
- Improve classroom search with additional resource and capacity filters.
- Add complaint notifications and status updates.
- Enhance analytics for classroom utilization and complaint resolution.
- Deploy the application for college-wide access.

## 🎯 Project Objective

CollegeConnect aims to improve campus resource utilization, simplify access to academic schedules, and provide a centralized process for reporting infrastructure issues.

## 👨‍💻 Development

This project is being developed as a college resource management application, with a focus on usability, centralized information, and efficient campus operations.

---

**CollegeConnect — Connecting students, faculty, classrooms, and campus resources.**
