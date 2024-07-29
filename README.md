# FeedsApp


This project is a Post Feeds Management application built using the Laravel PHP framework. It allows users to manage their posts efficiently by providing features such as create, read, comment, and like the posts.

Table of Contents

Features 

Modules Used 
Getting Started 
Prerequisites 
Installation 
Usage 
Features

CRUD operations for Post feeds (Create, Read, Update, Delete) Database persistence using MySQL User-friendly interface with Blade templates 

Modules Used

The following modules/packages were used in this project:

Laravel Framework: Provides the foundation for the application, including routing, ORM, and authentication. 
Blade Templating Engine: Allows for the creation of dynamic views using Laravel's Blade syntax. 
MySQL Database: Used for storing post items and their details. 
Logging: Used for log the datas like checking incoming requests and actions and passed parameters. 
Model: Interact with our database and tables. 
Migrations: Used for maintaining versions. 
Carbon: Access the date and time. 
Validator: Validates the input requests. 
Blade Directives: Used for including the same blade file to many files by extending the layouts. 
Components: We can render the specific component blade files to all. 
FrontEnd: Html,Css,Bootstrap,Javascript,Jquery,Ajax, Scss, Blade. 

Getting Started Prerequisites

PHP - 8.1 > MySQL Apache server (Any server to run the application) (LAMPP) Composer

Downloading LAMPP will be easy for the Application deploy, since it includes Php,mysql,apache.

Installation

Clone the repository - git clone https://github.com/gludhayasurya/FeedsApp.git

Setup

Place the application in htdocs folder for local environment. Change the .env file as per your database config, like username,password,database,host. Then, open the application using like, localhost/FeedsApp/public

Usage

We can create posts. From the posts list, can create, read ,comment and like it.
