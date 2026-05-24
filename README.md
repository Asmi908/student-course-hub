# Student Course Hub

A web-based university course and staff management system where 
students can search for academic programmes and view staff profiles.

## Built With
- PHP (MVC Architecture)
- MySQL
- HTML
- CSS

## Features
- View and search all staff members by name and job title
- View detailed staff profiles with photo, bio, contact info
- Search for academic programmes
- Staff dashboard for managing content

## Project Structure
/student_course_hub
├── /staff
│   ├── staff.php          # Staff list with search and filters
│   ├── staff_details.php  # Full staff profile page
│   └── /staff_photos      # Staff profile pictures
├── student_course_hub.sql # Database schema and data
└── README.md              # Project guide

## Setting Up

### 1. Install the Database
- Open phpMyAdmin
- Create a new database: `student_course_hub`
- Import `student_course_hub.sql`

### 2. Upload Staff Photos
- Create a folder named `staff_photos/` in your project
- Upload staff images (must match Photo column in database)

### 3. Run the Website
- Move project folder into XAMPP's `htdocs/` directory
- Start Apache and MySQL in XAMPP
- Open: `http://localhost/staff/staff.php`

## How to Use
1. Open `staff.php` to see all staff members
2. Search by name or filter by job title
3. Click **"View Profile"** to see full details

## Author
Ashmita Thapa — github.com/Asmi908
