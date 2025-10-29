# Student Management System

## 📄 Description
A simple ASP.NET Web Forms project that allows adding, viewing, and deleting student records using XML storage.

## 👨‍💻 Author Information
- **Name:** Krins Dobariya
- **Branch:** CE
- **Division:** 5E
- **Enrollment No:** 202403103520078

## ⚙️ Technologies Used
- ASP.NET Web Forms
- C#
- XML for data storage
- HTML, CSS

## ▶️ How to Run
1. Open the solution file `StudentManagementSystem.sln` in Visual Studio.
2. Press **Ctrl + F5** to run the project.
3. Use the web interface to add, view, and delete student data.

**Note:** This project writes to the `App_Data/students.xml` file. It is designed to run locally from Visual Studio. If deploying to a live server (IIS), the web server's user account (like 'IIS_IUSRS') must be given 'Write' and 'Modify' permissions on the `App_Data` folder.

## 🗂️ Files Included
- `Default.aspx` – Add new student form
- `Students.aspx` – View all student records
- `students.xml` – XML data file (used for storing student info)
