# Gym Management System

A web based gym management system. Dashboard shows live activity, while members, trainers, attendance and payments are each managed from their own separate pages.

## Project Info

- University: DHA Suffa University
- Semester: 4th
- Course: DBMS Lab

## Idea

Most gyms especially small ones still keep track of members, attendance and payments on paper registers or in random Excel sheets. Finding a member's record or checking who paid this month becomes a hassle.

The idea behind this project was to move away from that. A dashboard showing live activity at a glance with separate pages to manage members, attendance, trainers and payments instead of digging through registers.

## Note

At the time I made this project and I didn't know how to properly use Git and GitHub. So whatever files I had at that time are got pushed. The database file itself just wasn't uploaded to GitHub, left out on purpose because of security.

After the semester ended I deleted the rest of the project files from my system, config file, database, setup stuff, all of it. I didn't think I would need them again. So right now I don't have those files anymore, which means I can't push them even if I wanted to. What's in this repo is all that's left of the project.

## Tech Stack

- HTML, CSS and JS for frontend
- PHP for backend
- MySQL for database
- XAMPP for local server
- ngrok for exposing the local server through a public URL
## Features

- Admin login
- Dashboard with live stats
- Member management
- Trainer management
- Activity management
- Attendance tracking
- Payment tracking
- Remote testing and demo through ngrok
## Files

```
Gym-Management-System/
api/                  php/api files
auth/                 login and auth logic
login.html            login page
dashboard.html        admin dashboard
members.html          member management page
trainers.html         trainer management page
attendance.html       attendance tracking page
payments.html         payment tracking page
activities.html       activity management page
activities.php        backend logic for activities
style.css             styling for all pages
README.md
```

## How to run it

1. Install XAMPP
2. Clone the repo into your htdocs folder
3. Start Apache and MySQL from XAMPP
4. Make a database in phpMyAdmin
5. Create tables for members, trainers, attendance, payments and activities. Schema is not included, **see note above**
6. Set your own DB username and password in the connection file
7. Open login.html from localhost in your browser

## License

No license.

## Status

Old university semester project. Not maintained.
