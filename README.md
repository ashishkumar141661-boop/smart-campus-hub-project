# Smart Campus Hub wireframes

This folder contains the public and student wireframes for the Smart Campus Hub. Admin sign-in and management pages are in the sibling `adminside` folder; links between both folders use relative paths.

## Start here

Open index.html in a browser to browse the page index, or open home.html for the public landing page.

## Included pages

### Public and student
- home.html
- student-login.html
- student-signup.html
- student-dashboard.html
- profile.html
- attendance.html
- timetable.html
- notes.html
- assignments.html
- events.html
- contact.html

### Admin
- In `../adminside/`: admin-login.html, admin-signup.html, admin-dashboard.html, admin-attendance.html, admin-timetable.html, admin-notes.html, admin-assignments.html, and admin-events.html
- In this folder: students.html and messages.html

The admin page index links to both folders, and the Students and Messages pages link back to the admin pages in `../adminside/`.

These are structural wireframes, so controls and data are intentionally represented as layout blocks rather than connected application behavior.
The admin sign-up form validates input in the browser only; account creation requires a server-side registration flow.
