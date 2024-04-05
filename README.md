# PHP-Learning
# What is PHP?
- PHP is an acronym for "PHP: Hypertext Preprocessor"
- PHP is a widely-used, open source scripting language
- PHP scripts are executed on the server
- PHP is free to download and use

PHP is an amazing and popular language!

- It is powerful enough to be at the core of the biggest blogging system on the web (WordPress)!
- It is deep enough to run large social networks!
- It is also easy enough to be a beginner's first server side language!

# What is a PHP File?
- PHP files can contain text, HTML, CSS, JavaScript, and PHP code
- PHP code is executed on the server, and the result is returned to the browser as plain HTML
- PHP files have extension ".php"
# What Can PHP Do?
- PHP can generate dynamic page content
- PHP can create, open, read, write, delete, and close files on the server
- PHP can collect form data
- PHP can send and receive cookies
- PHP can add, delete, modify data in your database
- PHP can be used to control user-access
- PHP can encrypt data
- With PHP you are not limited to output HTML. You can output images or PDF files. You can also output any text, such as XHTML and XML.

# Why PHP?
- PHP runs on various platforms (Windows, Linux, Unix, Mac OS X, etc.)
- PHP is compatible with almost all servers used today (Apache, IIS, etc.)
- PHP supports a wide range of databases
- PHP is free. Download it from the official PHP resource: www.php.net
- PHP is easy to learn and runs efficiently on the server side

# Applications of PHP
- Server-side web development: It is a development where the program runs on a server dealing with the generation of content of web pages.
- Content management systems (CMS): It is a framework already designed by other programmers and coders on which you can either contribute your knowledge and skills or just use those coders’ skills to design your own website or blog
- E-commerce websites: E-commerce, or electronic commerce, refers to the buying and selling of goods and services over the Internet.
- Database-driven applications: It is a software application that relies on a database to store, manage, and retrieve data. It utilizes a database management system (DBMS) to organize and manipulate data, enabling efficient data storage, retrieval, and management.
- Web APIs: It is an API as the name suggests, it can be accessed over the web using the HTTP protocol. It is a framework that helps you to create and develop HTTP-based RESTFUL services.

# Basic PHP Syntax
- A PHP script can be placed anywhere in the document.
- A PHP script starts with <?php and ends with ?>:

```php
<?php
// This is a simple PHP script that echoes "Hello, World!"
echo "Hello, World!";
?>
```
# PHP Case Sensitivity
In PHP, keywords (e.g. if, else, while, echo, etc.), classes, functions, and user-defined functions are not case-sensitive.
```php
<?php
ECHO "Hello World!<br>";
echo "Hello World!<br>";
EcHo "Hello World!<be>";
?>
```
# Note: However; all variable names are case-sensitive!
Look at the example below; only the first statement will display the value of the $color variable! This is because $color, $COLOR, and $coLOR are treated as three different variables:

Example
$COLOR is not same as $color:
```php
<?php
$color = "red";
echo "My car is " . $color . "<br>";
echo "My house is " . $COLOR . "<br>";
echo "My boat is " . $coLOR . "<br>";
?>
```
