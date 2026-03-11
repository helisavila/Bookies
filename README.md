# Book Forum – Bookies
Bookies is an intuitive forum platform where book enthusiasts can discuss literature, share insights and engage in meaningful conversations with fellow readers.

## 1. Summary
### Current situation:

The "Literary Lions" book club was drowning in paper-based discussions that created chaos and confusion. Sticky notes overflowed pages, comments got lost in scribbles and finding past insights felt like navigating a literary labyrinth. New members felt intimidated by the chaotic paper trails, hindering their engagement and knowledge sharing.
The challenge was to design a digital forum that tames the paper pandemonium and fosters a thriving online book club community.

### Solution:
Literary Lions Forum addresses these needs by providing a comprehensive digital platform that transforms chaotic paper discussions into organized, accessible conversations. The solution includes:

- User authentication system with secure registration and login
- Comprehensive post and comment system for rich discussions
- Category-based organization for different books, genres, and topics
- Like/dislike functionality to highlight valuable contributions
- Advanced filtering capabilities for easy content discovery
- Responsive design optimized for all devices
- SQLite database for reliable data management
- Dockerized deployment for easy setup and scalability

## 2. Features

User Authentication
Post Management
Comment System
Like/Dislike System
Category Organization and filtering posts
Error Handling

## 3. Bonus features (for review)

User Profiles: personal dashboards showing user activity
Daily rotating quotes
Search tab
Sorting feature: sort posts by recent, most liked, most disliked
Dark/Light Mode: Complete theme switching with persistent user preferences (cookie-based storage)
Responsive Design: optimized for desktop and mobile devices
Log out option
Seperate home and forum pages

## 4. Technical Stack

Backend: Go (Golang) with net/http
Database: SQLite with go-sqlite3 driver
Frontend: HTML templates with CSS styling
Containerization: Docker for deployment
Session Management: Cookie-based with UUID tokens
Security: bcrypt password hashing

## 5. Authors

Heli Savila Frontend Development, UI/UX Design
Ibrahim Sen Backend Development, Architecture, Docker Implementation
