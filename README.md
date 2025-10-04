# AI-CAMPUS-GTP-CALLED-CAMPUS-GPT-
Core Concept
CampusConnect is a dynamic, role-based web portal designed to centralize and streamline all essential campus information for both students and teachers. It acts as a single source of truth, replacing scattered notices and manual communication with an efficient, interactive, and modern digital platform.

Target Audience & User Roles
The entire system is built around two distinct user roles with tailored experiences:

Students:

Goal: To easily access critical academic information without confusion.

Experience: The student dashboard is a personalized hub that shows them only what they need: their class timetable, upcoming exam schedules for their specific course, campus-wide events, and a list of their subjects. They also have access to an innovative AI Help Bot for study assistance.

Teachers (Administrators):

Goal: To manage, update, and distribute information to students efficiently.

Experience: The teacher dashboard is a powerful control panel. Teachers can manage the entire application's content, including scheduling exams for specific courses, updating the general timetable, managing the faculty directory, and updating their own profile details like their sitting location.

Key Features & Functionality
The application is made up of several interconnected modules:

Secure User Management:

A robust Login/Signup system that handles different roles.

Users are identified by a unique Registration ID and email.

Passwords are securely hashed.

The system differentiates between 'student' and 'teacher' accounts, granting different levels of access.

Role-Based Dashboards:

The main hub of the application, which dynamically changes its layout and features based on whether a student or a teacher is logged in.

Information Management Tools (for Teachers):

Faculty Management: A directory of all teachers, which is automatically populated when a teacher signs up. Admins can view the list and remove members.

Exam Scheduling: A dedicated tool for teachers to create, edit, and delete exam schedules specifically for the courses and subjects they teach.

Timetable Management: A tool for updating the master class schedule for all students.

AI-Powered Help Center:

An integrated "Help Bot" where any user can upload a PDF document (like a syllabus, textbook chapter, or research paper).

The system uses JavaScript to extract the text from the PDF.

The user can then ask questions (e.g., "Summarize this document," "What is the main point of section 2?").

The Gemini AI answers these questions based only on the content of the uploaded PDF, providing accurate, context-aware study help.

Technical Stack
Backend: PHP

Database: MySQL (managed via XAMPP)

Frontend: HTML, Tailwind CSS for styling, and JavaScript for interactive features like the AI chat.

AI Integration: Google Gemini API for natural language processing and question-answering.

Overall Goal
The ultimate goal of CampusConnect is to create a more organized, efficient, and technologically advanced campus environment. It reduces the administrative
