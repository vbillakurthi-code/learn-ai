Successfully added an "Available Courses" section to the dashboard. Here's what was implemented:
Dashboard Layout Changes:
- Converted the single "Next Session" section into a two-column grid layout
- Added "Available Courses" section alongside "Next Session"

Course Display on Dashboard:
- Added dashboardCourseList element reference
- Updated renderCourses() function to populate the dashboard with a compact course list
- Each course shows name, instructor, duration, and a "View" button in a clean, condensed format

Features:
- Courses are displayed in a compact format suitable for the dashboard
- Shows course name, instructor, and duration
- Responsive layout that works on both desktop and mobile
- Automatically updates when courses are added/removed through the admin panel

The dashboard now displays available courses in a user-friendly format, making it easy for users to see what courses are available right from the main dashboard view.
