📚 Student Attendance Management System (SAMS)

A modern, fully interactive frontend-based Attendance Management System built using HTML, CSS, and Vanilla JavaScript.
It allows teachers and admins to mark attendance, analyze reports, and monitor student performance in real-time.

🚀 Features
👩‍🏫 Teacher Module
Mark daily attendance (Present / Absent / Late)
Select class, subject, and date
Bulk actions (Mark All Present / Absent)
Save attendance with confirmation toast
Student-wise attendance percentage tracking
📊 Admin Dashboard
Overall attendance analytics
Class-wise performance comparison
Critical students (below 75%)
Warning alerts (75–85%)
Global student performance overview
📈 Reports Module
Class-wise attendance reports
Student-wise detailed analytics
Subject-wise performance tracking
Attendance calendar heatmap (last 30 days)
🚨 Alerts System
Critical absenteeism detection
Warning-level attendance tracking
Prioritized student list for intervention
🏫 Supported Classes & Subjects
Classes:
CSE-A (3rd year)
CSE-B (3rd year)
ECE-A (2nd year)
MECH-A (1st year)
Example Subjects:
Operating Systems
DBMS
Computer Networks
Machine Learning
Signals & Systems
Engineering Mathematics
🧑‍💻 Tech Stack
HTML5 – Structure
CSS3 – Styling (Modern UI with custom design system)
JavaScript (ES6) – Logic & State Management
Tabler Icons – UI icons
🧠 Core Concepts Used
Dynamic DOM rendering (no frameworks)
State management using JavaScript objects
Random attendance data generation (simulation)
Role-based UI switching (Teacher / Admin)
Data aggregation & analytics
Progress bars & visual reporting
Heatmap calendar visualization
📂 Project Structure
student-attendance-system/
│
├── index.html        # Main application (all-in-one file)
├── README.md         # Project documentation
▶️ How to Run the Project
Method 1 (Simple)
Download the project files
Open index.html in any modern browser (Chrome recommended)
Method 2 (VS Code Live Server)
Open folder in VS Code
Install Live Server extension
Right-click index.html
Click "Open with Live Server"
📊 How It Works
Attendance is stored in an in-memory JavaScript object (attendanceDB)
Random data is generated for the last 30 days for demo purposes
User interactions update a temporary state (todayMarked)
UI re-renders dynamically after every action
🎯 Key Highlights
No backend required (pure frontend project)
Fully interactive dashboard UI
Real-time updates without page refresh
Clean, modern Apple-like design
Suitable for college mini-project / portfolio
📌 Future Enhancements
Backend integration (Node.js / Firebase)
Login system (Student / Teacher / Admin roles)
Export reports (PDF / Excel)
Database storage (MongoDB / MySQL)
Mobile responsive optimization
Email/SMS attendance alerts
