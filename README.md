🎓 Student Management System (Java + MySQL)

A simple Java Swing and MySQL based application to manage student records — including features for searching, deleting, and displaying student data.
Built as a mini PBLJ project to demonstrate JDBC connectivity and GUI integration in Java.

🧩 Features

🔍 Search Student: Find details by roll number

🗑️ Delete Student: Remove records from database

🔁 Reload Data: View all students from the database

🧭 Admin Panel: Navigate between modules

🎨 User Interface: Built using Java Swing (NetBeans GUI)


⚙️ Technologies Used

| Category             | Technology                      |
| -------------------- | ------------------------------- |
| Programming Language | Java (JDK 17+)                  |
| GUI Framework        | Java Swing                      |
| Database             | MySQL                           |
| Database Connector   | JDBC (com.mysql.cj.jdbc.Driver) |
| IDE Used             | NetBeans / IntelliJ IDEA        |




🗄️ Database Details
| Column      | Type         | Description              |
| ----------- | ------------ | ------------------------ |
| Rollnumber  | INT          | Unique ID of the student |
| StudentName | VARCHAR(100) | Full name of the student |
| Class       | VARCHAR(50)  | Class or course name     |




SQL Table Creation Example:

<img width="1443" height="599" alt="image" src="https://github.com/user-attachments/assets/35716128-4183-4624-8ae9-6e48803e1935" />





🚀 How to Run the Project


1.Clone this repository:

2.git clone https://github.com/your-username/Student-Management-System.git


3.Open it in NetBeans or IntelliJ IDEA.

4.Update your MySQL username and password inside the code:

5.Connection con = DriverManager.getConnection("jdbc:mysql://localhost:3306/college", "root", "your_password");


6.Run the project — enjoy! 🎉


📸 Screenshots:

<img width="2551" height="1504" alt="Screenshot 2025-11-09 155803" src="https://github.com/user-attachments/assets/12c599c9-ceb8-47de-a66f-2644134446fd" />
<img width="2550" height="1442" alt="Screenshot 2025-11-09 155844" src="https://github.com/user-attachments/assets/f790620e-8ff1-4320-a003-1767c30fcecc" />
<img width="2547" height="1431" alt="Screenshot 2025-11-09 155936" src="https://github.com/user-attachments/assets/852bf32e-f9a4-413f-a434-d5ee1de145fc" />
<img width="2549" height="1433" alt="Screenshot 2025-11-09 160010" src="https://github.com/user-attachments/assets/cab76d1b-8d79-434d-a0bd-d068a6180547" />
<img width="2544" height="1433" alt="Screenshot 2025-11-09 160034" src="https://github.com/user-attachments/assets/e9343d89-cbe8-435e-9fde-629ffcc40943" />
<img width="2544" height="1428" alt="Screenshot 2025-11-09 160057" src="https://github.com/user-attachments/assets/86a47829-5741-4ebe-9b16-528df4582359" />
<img width="2554" height="1433" alt="Screenshot 2025-11-09 160120" src="https://github.com/user-attachments/assets/12402033-3250-481e-ab10-0823272993eb" />



🧑‍💻Author

Developed by Shree Kumar Bauri
📧 Contact: 7677381627

📍 Made as part of a Mini Project for PBLJ.
