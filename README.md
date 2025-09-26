Campus Course & Records Manager (CCRM)
A console-based student and course management system built with modern Java SE.

CCRM is a comprehensive, console-based application designed to help an educational institute manage students, courses, enrollments, and academic records. Built entirely in Java, this project serves as a practical demonstration of core Java principles, Object-Oriented Programming, and modern Java APIs like Streams and NIO.2.

✨ Key Features
👨‍🎓 Student Management: Add, update, view, and list student profiles.

📚 Course Administration: Create, update, and search for courses. Assign instructors and manage course details.

📝 Enrollment & Grading: Enroll students in courses, record marks, and generate academic transcripts with GPA calculations.

💾 Data Operations: Import and export data from/to text files, and create timestamped backups of all application data.

📊 Simple Reporting: Generate basic reports, like GPA distribution or course listings by department.

Export to Sheets
Data Export	Backup Folder
Your data export screenshot here	Your backup folder screenshot here

Export to Sheets
💻 Technology Stack
Language: Java SE 17

Build Tool: Maven

Core APIs:

java.nio (NIO.2) for modern file operations

java.util.stream (Streams API) for efficient data processing

java.time (Date/Time API) for reliable date and time handling

🚀 Getting Started
Follow these instructions to get a copy of the project up and running on your local machine.

Prerequisites
Make sure you have the following software installed:

Git

Java Development Kit (JDK) - Version 17 or higher

Apache Maven

An IDE like Eclipse or IntelliJ IDEA is recommended.

Installation & Running
Clone the repository:
git clone https://github.com/Prattscse/Vityarthi-CCRM-Assignment
cd Vityarthi-CCRM-Assignment
Open in your IDE:

Open your preferred IDE (e.g., Eclipse or IntelliJ).

Import the cloned folder as an "Existing Maven Project".

Your IDE will automatically detect the pom.xml file and download all necessary dependencies.

Run the application:

Navigate to the main class located at src/main/java/edu/ccrm/cli/Main.java.

Right-click on the Main.java file and select "Run". The application menu will appear in your console.

📋 How to Use
The application is fully operated through a simple, menu-driven command-line interface.

On startup, you will be presented with the main menu.

Enter the number corresponding to your desired action (e.g., 1 for Student Management) and press Enter.

Follow the on-screen prompts to perform various operations like adding students, creating courses, or enrolling students.

To test the data import feature, sample data files are provided in the /test-data directory. You can import them using the "Data Utilities" option in the main menu.
