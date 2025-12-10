🛡️ SafeZone: Disaster Preparedness Portal
Empowering schools and communities with the knowledge to stay safe during emergencies.

SafeZone is a comprehensive, full-stack web application designed to bridge the gap between disaster management authorities, schools, and students. By combining AI, Virtual Reality (VR), and Gamification, SafeZone makes disaster preparedness engaging, accessible, and effective.

Whether you are a student learning safety protocols, a school admin monitoring preparedness, or a government official issuing critical alerts, SafeZone has a dedicated dashboard for you.

🌟 Key Features
🎓 For Students (Gamified Learning)
Interactive Courses: Access structured lessons on various disaster types (Earthquakes, Floods, etc.) and mark them as complete to earn XP.

VR Mock Drills: Experience realistic 360° scenarios (like fire evacuations) directly in the browser using A-Frame. Make split-second decisions to survive and score points.

AI Kit Checker: Upload a photo of your emergency bag, and our Google Gemini-powered AI will analyze it, identifying missing critical items.

Voice Assistant: A built-in voice command feature to navigate the app or ask safety questions hands-free.

Leaderboard & Badges: Compete with peers! Earn badges like Bronze Learner, Silver Knight, and Gold Pro based on your XP.

🏫 For School Admins
Preparedness Analytics: Visualize student engagement and course completion rates through interactive Chart.js graphs.

Drill Management: Schedule and track the status of mock drills (Fire, Earthquake, etc.).

Course Management: Create and update safety curriculum content dynamically.

📢 For DDMA Officials (District Disaster Management Authority)
Broadcast Alerts: Issue real-time emergency alerts (Severity: Low to Critical) that instantly appear on school and student dashboards.

Regional Safety: Oversee preparedness across specific regions.

🛠️ Tech Stack
This project is built using a robust Node.js ecosystem:

Backend: Node.js, Express.js

Database: MongoDB (via Mongoose)

Frontend: EJS (Templating), Bootstrap 5 (UI Framework)

AI Integration: Google Gemini 1.5 Flash API (Content Generation & Vision)

VR/3D: A-Frame (WebVR)

Visualization: Chart.js

Voice: Web Speech API

🚀 Getting Started
Follow these steps to get a local copy up and running.

Prerequisites
Node.js (v14+ recommended)

MongoDB (Local or Atlas)

A Google Cloud API Key (for Gemini AI features)

Installation
Clone the repository:

Bash

git clone https://github.com/your-username/disaster-prep-app.git
cd disaster-prep-app
Install dependencies:

Bash

npm install
Configure Environment Variables: Create a .env file in the root directory and add the following keys:

Code snippet

PORT=3000
MONGO_URI=your_mongodb_connection_string
GOOGLE_API_KEY=your_google_gemini_api_key
Run the application:

Bash
npm start
Visit the App: Open your browser and navigate to http://localhost:3000.

📂 Project Structure
/models: MongoDB Schemas for Users, Courses, Drills, and Alerts.

/routes: Contains the main application logic and API endpoints.

/views: EJS templates for different user roles (Student, Admin, DDMA).

/public: Static assets including:

js/assistant.js: Voice recognition logic.

js/quiz.js: Gamified quiz logic.

sounds/: Audio assets for alarms and feedback.

images/: 360° panoramas for VR drills.

🎮 How to Use
Landing Page: Choose your role (Student, School Admin, or DDMA).

DDMA: Go to the DDMA dashboard to post a test "Flood Warning".

School Admin: Check the dashboard to see the alert, then go to "Manage Courses" to add a new lesson.

Student:

Log in (Demo User ID is pre-configured in code for ease of testing).

Check your dashboard for the Flood Warning.

Try the "Check My Kit" feature by uploading a photo of a backpack.

Launch the VR Drill and try to "escape" the virtual classroom!

🤖 AI & Future Enhancements
Current AI: We use gemini-1.5-flash-latest for instant answers to safety questions and analyzing emergency kit images.

Roadmap:

Real-time SMS integration for alerts.

Multi-language support for diverse communities.

GPS-based "Safe Shelter" locator.

📄 License
This project is licensed under the ISC License.

<p align="center"> Made with ❤️ for a Safer Tomorrow. </p>
