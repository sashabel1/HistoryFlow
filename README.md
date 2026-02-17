HistoryFlow ⏳

AI-Powered Interactive Timeline Generator

HistoryFlow is a full-stack web application that allows users to explore history dynamically.
By integrating Wikipedia data and Gemini AI, the app generates rich, visual timelines for any subject, from global wars to scientific breakthroughs.

🚀 Features
AI Search: Enter any topic, and the system fetches relevant historical data using Wikipedia and Gemini AI.

Interactive UI: A fluid, responsive timeline built with React and Tailwind CSS.

Custom Timelines: Registered users can create, save, and edit their own historical flows.

Visual Richness: Automatic image fetching via Unsplash API to match historical events.

User Authentication: Secure login/registration system using JWT and Bcrypt.

🛠️ Tech Stack
Frontend: React.js, Tailwind CSS, Lucide React (Icons).

Backend: Node.js, Express.js.

Database: MongoDB (Mongoose ODM).

AI/External APIs: Google Gemini AI, Wikipedia API, Unsplash API.

Deployment: Vercel.


📦 Installation & Setup
Clone the repository:

Bash
git clone https://github.com/YOUR_USERNAME/historyflow.git
Install dependencies for both client and server:

Bash
# Install frontend dependencies
cd react-timeline && npm install

# Install backend dependencies
cd ../server && npm install
Environment Variables:
Create a .env file in the server folder and add:

Code snippet
MONGODB_URI=your_mongodb_connection_string
GEMINI_API_KEY=your_key
UNSPLASH_ACCESS_KEY=your_key
JWT_SECRET=your_secret
Run the project:

Terminal 1 (Frontend): ```bash
cd react-timeline && npm start

Terminal 2 (Server): ```bash
cd server && node server.js


