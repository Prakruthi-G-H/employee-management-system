# Employee Management System

A web-based Employee Management System built using Java, JSP, Servlets, JDBC, and MySQL. This project allows users to manage employee records through basic CRUD (Create, Read, Update, Delete) operations.

## 📌 Project Overview

The Employee Management System simplifies employee record management by providing functionality to add, view, update, and delete employee details. It follows a layered structure with separate components for controllers, data access, models, and business logic.

## 🧰 Tech Stack Used

- **Frontend**: HTML, CSS, JSP
- **Backend**: Java, Servlets, JDBC
- **Database**: MySQL
- **Build Tool**: Maven
- **Server**: Apache Tomcat 
- **IDE**: Eclipse

## 📌 Features

- Add new employee records  
- View employee details
- Update existing employee information 
- Delete employee records
- Store and retrieve employee data using MySQL
- Organize application code into separate layers

## 🗂️ Project Structure

```bash
employee-management-system/
├── src/
│   └── main/
│       ├── java/
│       │   └── com/example/ems/
│       │       ├── controller/       
│       │       ├── dao/              
│       │       ├── model/            
│       │       └── service/         
│       └── webapp/
│           ├── WEB-INF/
│           │   └── web.xml           
│           ├── addemployee.html
│           ├── delete.html
│           ├── employee.html
│           ├── manage.html
│           ├── success.jsp
│           ├── update.html
│           ├── updateemployee.jsp
│           └── viewemployee.jsp    
├── pom.xml
└── README.md
```

## ⚙️ Prerequisites

Make sure you have the following installed:
- JDK compatible with your project
- Eclipse IDE
- MySQL Workbench
- Apache Tomcat compatible with your project
- Maven

## 🚀 How to Run the Project

1. Clone the repository  
   ```bash
   git clone https://github.com/Prakruthi-G-H/Employee-Management-System.git
   ```
2. Import into Eclipse
    - Open Eclipse IDE.
    - Import the project as an existing Maven project.
3. Set up the MySQL database
   - Create a database: ems_db
   - Create employee table manually 

4. Configure DB connection in your Java code 

5. Add and configure Apache Tomcat Server
   - Right-click project → Run on Server
   - Choose Apache Tomcat v9 or v10

6. Open the browser and go to: http://localhost:8080/Employee-Management-System/


## 🔮 Future Enhancements

- Implement login and authentication (Admin/User roles)
- Integrate with Spring Boot for scalability

  
## 👩‍💻 Developed By

**Prakruthi G H**  
📍 Bangalore, India  
📧 prakruthigh28@gmail.com  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/prakruthi-g-h)
