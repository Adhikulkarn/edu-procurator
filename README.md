# edu-procurator
edu-procurator is a web-based educational management system designed to help teachers and educators manage attendance, tasks, communications, and student collaboration efficiently. The application features a responsive design and offline capability to ensure uninterrupted functionality.
Features
1. Attendance Management

Select class and subject for attendance marking
Bulk attendance marking capability
Automatic notification system for absent students
Offline support with data syncing

2. Task Management

Create and assign tasks with titles, descriptions, and due dates
Track task completion rates
Automated task reminder system
Task progress visualization

3. Communication Center

Pre-built message templates
Custom message creation
Automated notifications for absences
Bulk notification capabilities

4. Insights Dashboard

Real-time attendance rate tracking
Task completion statistics
Active student monitoring
Performance metrics visualization

5. Collaboration Forum

Create discussion topics
Thread-based conversations
Real-time updates
User participation tracking

6. Additional Features

Voice Assistant Integration
Dark Mode Support
Offline Functionality
Responsive Design
Real-time Data Synchronization

Technical Details
Prerequisites

Modern web browser with JavaScript enabled
Internet connection (offline functionality available)
Access to MongoDB backend

Dependencies

Tailwind CSS (via CDN)
Bootstrap Icons
Inter Font Family
Web Speech API (for voice assistant)

API Integration
The application uses a MongoDB backend with the following endpoint:
Copyhttps://r0c8kgwocscg8gsokogwwsw4.zetaverse.one/mongodb
Authentication

Bearer token authentication required for API calls
Token format: Bearer TCOiLaQdqIgknEmPVRYyMCqzcT32

Installation & Setup

Clone the repository
Open the index.html file in a web browser
No additional installation required as dependencies are loaded via CDN

Offline Functionality
The application includes robust offline support:

Automatic detection of connection status
Data storage during offline mode
Automatic synchronization when connection is restored
Visual indicator for offline status

Data Collections
The application uses the following MongoDB collections:

attendance: Stores attendance records
tasks: Manages assigned tasks
notifications: Tracks all communications
forum: Stores discussion threads

Security Features

Secure API authentication
User session management
Data persistence with localStorage
Encrypted communications

Browser Compatibility
The application is compatible with modern web browsers that support:

Web Speech API
localStorage
Fetch API
CSS Grid and Flexbox

Contributing

Fork the repository
Create a feature branch
Commit your changes
Push to the branch
Create a Pull Request

License
This project is licensed under the MIT License - see the LICENSE file for details.
Support
For support queries, please create an issue in the repository or contact the development team.
