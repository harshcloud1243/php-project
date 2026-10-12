# PHP Signup Form Project

## 1. Introduction

This project is a simple signup form application developed using HTML, PHP, and MySQL. It collects user details and stores them in a database.

## 2. Project Architecture

The project follows a client-server architecture. The HTML form collects user information, PHP processes the submitted data, and MySQL stores the information.

**Workflow:**
User → HTML Form → PHP Script → MySQL Database → Result Displayed in Browser

![Architectural Diagram](PHP%20Signup%20Form%20Architecture.png)


## 3. Input

The application accepts the following details from the user:

* Name
* Email
* Website
* Comment
* Gender

The input form is created in `signup.html` and sends the data to `submit.php` using the POST met!

<img width="1005" height="824" alt="Screenshot 2026-10-08 181102" src="https://github.com/user-attachments/assets/c24471a2-c32f-44d4-89fb-53c8f66d8768" />


## 4. Output

After submission, the PHP script connects to the database and attempts to insert the information into the `users` table.

The browser displays a success message with the submitted details or an error message if the insertion fails.

<img width="1197" height="818" alt="Screenshot 2026-10-08 181115" src="https://github.com/user-attachments/assets/abe3821e-5bab-4034-ada9-fa9366863a83" />
<img width="1400" height="392" alt="Screenshot 2026-10-08 181838" src="https://github.com/user-attachments/assets/ae5332bf-8537-470b-b73c-00ddb5b3d1b0" />

## 5. PHP Project Setup

The project requires the following components:

* **Operating System:** Linux or Windows
* **Web Server:** Apache or Nginx with PHP support
* **Backend:** PHP
* **Database:** MySQL or MariaDB
* **Database Name:** `FCT`
* **Table Name:** `users`

**Project Files:**

* `signup.html` – User signup form
* `submit.php` – Form processing and database connectivity
* `README.md` – Project documentation

## 6. Conclusion

This project demonstrates HTML form creation, PHP form handling, and MySQL database connectivity. It provides basic practical knowledge of web application development and server-side programming.
