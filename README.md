# User Authentication System in PHP and MySQL: Login System

###### Version 1.0.0

User authentication is an essential component of web development that allows for authorization and restriction of user access to specific pages within a web application.

## Registration System

### Database Table in MySQL

To create the necessary users table, make sure you have a MySQL database. Execute the `sql.sql` file in your MySQL database to create the table.

### Configuration File

The PHP script responsible for connecting to the database can be found in the `config/config.php` directory. Update the credentials in `config.php` to match your server credentials.

### Registration Form and Script

The `register.php` file contains a web form that enables users to register themselves. The script will generate an error if the form input is empty or if the chosen username has already been taken by another user.

## Login System

### Login Form and Script

The login process is handled by `login.php`. When a user submits the username and password, these inputs are verified against the stored credentials in the database. If there is a match, the user will be authorized and granted access to the site or page.

### Welcome Page

After a successful login, the user is redirected to `welcome.php`.

### Password Reset

Logged-in users have the option to reset their password for their registered account. The script for this functionality can be found in `password_reset.php`.

<hr />
<small>If you found this project useful, please give it a ⭐ and follow me for more interesting projects in the future.</small>
