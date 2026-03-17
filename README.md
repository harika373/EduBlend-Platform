EduBlend Platform
Digital Learning Platform for Educational Opportunity Expansion Schools
Songkhla Province, Thailand

Based on the research paper: "Designing an Appropriate Learning Approach Utilizing Blended Learning to Improve Students' Achievement for Educational Opportunity Expansion Schools" — Apichaya Khwankaew, Rajamangala University of Technology Srivijaya, PlatCon 2023.


Overview
EduBlend is a browser-based blended learning dashboard that combines online and face-to-face learning environments for students in Educational Opportunity Expansion Schools. It provides role-based access for Teachers, Students, and School Administrators, supporting the digital learning goals outlined in the research.

Features
Authentication

Role-based login: Teacher, Student, Admin
Username and password validation
Session management with sign-out functionality
Enter key support for form submission

Teacher Dashboard

Daily schedule showing face-to-face and online sessions
Student progress tracking and engagement alerts
Assignment grading queue
Attendance statistics
Parent communication status

Student Dashboard

Enrolled course overview with completion status
Upcoming assignment deadlines
Attendance and score metrics
Direct access to blended learning materials

Admin Dashboard

School-wide platform health monitoring
Wi-Fi and infrastructure status
Teacher technology readiness tracking (aligned with the paper's finding that 80% of teachers want more training)
Thai-language UI rollout status


Getting Started
Requirements

Any modern web browser (Chrome, Firefox, Edge, Safari)
No server, no installation, no dependencies

Run the App

Download edublend_dashboard.html
Open it in your browser — double-click or drag into a browser window
Sign in using the demo credentials below

Demo Credentials
RoleUsernamePasswordTeacherteacher1234Studentstudent1234Adminadmin1234

File Structure
edublend_dashboard.html     # Complete single-file application
README.md                   # This file
The entire application is contained in a single HTML file with no external dependencies.

Research Background
This project is informed by the following key findings from the source paper:

80% of teachers in Expansion Schools want additional technology training
60% of teachers lack familiarity with integrating technology into teaching
Students face budget constraints limiting access to devices and internet
Most digital learning platforms lack Thai-language instruction manuals
Infrastructure gaps (Wi-Fi, device availability) remain a significant barrier
The blended learning model addresses four elements: online integration, data utilization, personalization, and virtual engagement

The platform design directly addresses these pain points through simplified login flows, role-appropriate dashboards, and clear visibility into infrastructure and training status.

Technology
LayerTechnologyStructureHTML5StylingCSS3 with custom propertiesLogicVanilla JavaScript (ES6)FontsSystem UI / Segoe UIDependenciesNone — fully self-contained

Blended Learning Model
The dashboard reflects the four-component blended learning framework described in the paper:
ComponentDashboard ImplementationOnline integrationSession cards showing face-to-face vs online modeData utilizationMetrics cards with attendance and score trackingPersonalizationRole-based views tailored to each user typeVirtual engagementLive session indicators and assignment workflows

Customisation
To adapt this platform for your school:

Update credentials — Replace the USERS object in the <script> section with real user data or connect to a backend API
Update school name — Change "Songkhla Province · Thailand" in the brand badge to your institution
Update metrics — Replace hardcoded values in the DASH object with live data from your LMS
Add Thai language support — Translate all UI strings; a language toggle can be added to the topbar
Connect to an LMS — Replace static dashboard data with API calls to platforms such as Moodle, Google Classroom, or a custom backend


Acknowledgement
This project was developed as part of the "Digital Learning Platforms Development for Enhancing the Professional Competencies in Innovative Education Areas, Songkhla Province" initiative, sponsored by the Program Management Unit on Area Based Development (PMU A), Thailand.

License
This project is provided for educational and research purposes in alignment with the goals of Educational Opportunity Expansion Schools in Thailand.ShareContentpdf
