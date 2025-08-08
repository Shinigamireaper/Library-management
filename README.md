# Online Library Management System  
An interactive system to automate library operations such as book search, issue/return, and membership management.

## Author  
**Likith G**
**Varun D S**

## Abstract  
The Online Library Management System is designed to eliminate the difficulties of manual library management.  
It streamlines processes like searching books by ISBN, title, or author, tracking availability, managing memberships, and handling fines.  
Admins can manage books, student records, staff, and schedules, while students can easily locate and borrow books using their accounts.

## Core Features  
- Search books by ISBN, title, or author  
- Issue and return books  
- Track fines and dues  
- Add/update/delete books and members  
- Admin dashboard for full control  
- Student registration and login  
- Staff account management  

## Technology Stack  
- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** PHP  
- **Database:** MySQL  
- **Server:** Apache  

## Requirements  
- WAMP / XAMPP / MAMP Server  
- PHP 7+  
- MySQL Database  

## Installation  
1. Clone or download the repository.  
2. Place the project folder into your server’s `www` (WAMP) or `htdocs` (XAMPP/MAMP) directory.  
3. Import the SQL database file from the `db` folder into MySQL.  
4. Update `dbcon.php` with your database credentials.  
5. Open your browser and visit `localhost/{your_project_folder}`.  

## Usage  
- **Admin:** Manage books, members, staff, schedules, and account details.  
- **Student:** Search for books, check location, issue/return books, and pay fines if applicable.  
- **Staff:** Scan barcodes, update accounts, and process book issues/returns.  