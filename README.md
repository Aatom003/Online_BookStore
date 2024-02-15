# [OnlineBookStore](https://youtu.be/mLFPodZO8Iw)

- A Java Web Development Project

<!-- Check out the Live website demo: [https://theonlinebookstore.herokuapp.com](https://theonlinebookstore.herokuapp.com) -->

- User Login Credentials: (shashi/shashi)
- Admin Login Credentials: (Admin/Admin)

---

### About

The OnlineBookStore is a user-friendly e-commerce platform where users can log in or register, browse available books, select desired items with quantities, and make purchases. Users receive payment receipts upon successful transactions. The platform also provides administrative functionalities, allowing administrators to manage inventory, update book details, and monitor sales history.

![onlinebookstore](https://user-images.githubusercontent.com/34605595/137615096-8447d32d-bddc-4f13-a8ed-3c0f4dd5e04e.png)

**This Website is built for the following purposes:**
- Online book sales
- Sales history management
- Inventory management
- User-friendly interface
- Implementation of Http Servlets in Java
- This project is developed using Java, JDBC, and Servlets.

**Admin Access:**
- Add new books
- View available books
- Remove books
- Update book quantities

**User Access:**
- Create a new account or register
- Log in
- Browse available books
- Select books for purchase
- Choose quantities
- Make purchases
- Receive payment receipts

### Technologies used:

1. Front-End Development:
   - HTML
   - CSS
   - JavaScript
   - Bootstrap

2. Back-End Development:
   - Java (JDK 8+)
   - JDBC
   - Servlets

3. Database:
   - MySQL

### Required Software and Tools:

- Git
- Java JDK 8+
- Eclipse EE (Enterprise Edition)
- Apache Maven
- Tomcat v8.0+
- MySQL Server
- MySQL Workbench (optional)

### Dummy Database Initialization:

1. Open MySQL Command Prompt or MySQL Workbench
2. Log in to the administrator user: `mysql -u <username> -p` (Enter Password if asked)
3. Execute the following MySQL Commands:

```MySQL
create database if not exists onlinebookstore;

use onlinebookstore;

-- Create tables and insert data (see provided commands in the original text)

commit;
```

### Importing and Running The Project Through Eclipse EE:

1. Open Eclipse Enterprise Edition.
2. Click on File > Import > Git > Projects From Git > Clone Uri > Paste The Repository Url: `https://github.com/shashirajraja/onlinebookstore.git` > Select master Branch > Next > Next > Finish.
3. Configure database details in `src/main/resources/application.properties`.
4. Right Click on Project > Run as > Maven Build > In the goals field enter "clean install" > apply > run
5. Right Click On Project > Build Path > Configure Build Path > Libraries > Remove and Update Any Libraries if Red Mark Exists > Finish.
6. Run the project on Tomcat Server.
7. Access the website at [http://localhost:8083/onlinebookstore/](http://localhost:8083/onlinebookstore/)
8. Default credentials: Admin (Admin/Admin), User (shashi/shashi)

### FAQ

**Question: Unable to Connect to Database?**

**Answer:** Please ensure MySQL is installed correctly and update the database details in `application.properties`. Additionally, try Maven clean install, force update the project, and restart if needed.

---

Note: This project is a sample and may not fully consider web security aspects.

#### Screenshots:

<img width="941" alt="image" src="https://user-images.githubusercontent.com/34605595/224769637-37c34d4b-26e7-4d49-b990-4c09b260ec31.png">
<img width="954" alt="image" src="https://user-images.githubusercontent.com/34605595/224769990-f440f74d-41b2-4629-ba1c-a87267f225d9.png">
<img width="930" alt="image" src="https://user-images.githubusercontent.com/34605595/224770145-5902054f-5943-44ac-b02f-92097c8a6972.png">
<img width="934" alt="image" src="https://user-images.githubusercontent.com/34605595/224770257-e18a3810-0457-4b78-bf46-cf82746708ee.png">
<img width="946" alt="image" src="https://user-images.githubusercontent.com/34605595/224770392-5a5478d2-98cc-44ee-8689-132b6b16af80.png">

#### Suggestions and project improvement ideas are welcomed!

Thanks a lot,
<br>
Anind Kumar Jha
