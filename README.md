Women-Chama :rocket:
Empowering Women’s Financial Independence
Women-Chama is a web application designed to streamline the management of women’s savings and investment groups (chamas). Built with React.js for a dynamic frontend and Node.js for a robust backend, this platform simplifies financial tracking, group coordination, and communication for chama members. :star:
Table of Contents

Features
Technologies
Installation
Usage
Project Structure
Contributing
License
Contact

Features :sparkles:
What Women-Chama Offers

Group Management :busts_in_silhouette:Create and manage chama groups, add members, and assign roles (e.g., treasurer, secretary).
Savings Tracking :moneybag:Record and track individual and group contributions with automated balance updates.
Payout Schedules :calendar:Plan and manage merry-go-round or investment payout schedules.
Communication Hub :speech_balloon:In-app messaging and notifications to keep members connected.
Reports & Analytics :bar_chart:Generate financial reports and visualize savings progress with charts.
Secure Authentication :lock:User login and role-based access control for data privacy.
Responsive Design :iphone:Accessible on desktop and mobile for a seamless experience.

Technologies :gear:
Tech Stack

Frontend :computer:
React.js: Dynamic, component-based UI.
Tailwind CSS: Modern, responsive styling.
Axios: API requests to the backend.
React Router: Client-side routing.


Backend :server:
Node.js: Scalable server-side runtime.
Express.js: RESTful APIs.
MongoDB: Data storage for users, groups, and transactions.
JWT: Secure user authentication.


Other Tools :wrench:
Git: Version control.
npm: Package management.
ESLint & Prettier: Code linting and formatting.
Docker (optional): Containerized deployment.



Installation :hammer_and_wrench:
Setting Up Locally
Prerequisites

Node.js (v16 or higher)
MongoDB (local or MongoDB Atlas)
Git

Steps

Clone the Repository :inbox_tray:
git clone https://github.com/stevovenom/women-chama.git
cd women-chama


Install Backend Dependencies :package:
cd backend
npm install


Install Frontend Dependencies :package:
cd ../frontend
npm install


Configure Environment Variables :key:

In backend/.env:PORT=5000
MONGODB_URI=your-mongodb-connection-string
JWT_SECRET=your-jwt-secret


In frontend/.env:REACT_APP_API_URL=http://localhost:5000/api




Run the Backend :rocket:
cd backend
npm start


Run the Frontend :rocket:
cd frontend
npm start


Access the Application :globe_with_meridians:Open http://localhost:3000 in your browser.


Usage :clipboard:
How to Use Women-Chama

Sign Up :pencil:Create an account to join or start a chama.
Create a Group :busts_in_silhouette:Set up a chama, invite members, and define contribution rules.
Track Contributions :money_with_wings:Log payments and view savings progress.
Communicate :e-mail:Use messaging to discuss group activities.
Generate Reports :chart_with_upwards_trend:Download summaries or view analytics dashboards.

Project Structure :file_folder:
Code Organization
women-chama/
├── backend/                  # Node.js/Express backend :server:
│   ├── config/               # Database config
│   ├── controllers/          # API request handlers
│   ├── models/               # MongoDB schemas
│   ├── routes/               # API routes
│   ├── middleware/           # Auth middleware
│   └── server.js             # Backend entry point
├── frontend/                 # React.js frontend :computer:
│   ├── public/               # Static assets
│   ├── src/                  # React source code
│   │   ├── components/       # Reusable UI components
│   │   ├── pages/            # Page components
│   │   ├── context/          # State management
│   │   ├── assets/           # Images
│   │   └── App.js            # Main app component
│   └── package.json          # Frontend dependencies
├── README.md                 # Project docs :book:
└── .gitignore                # Git ignore rules

Contributing :handshake:
Join the Community
We welcome contributions! To contribute:

Fork the repository :fork_and_knife:.
Create a branch (git checkout -b feature/your-feature).
Commit changes (git commit -m "Add your feature").
Push to the branch (git push origin feature/your-feature).
Open a Pull Request :pull_request:.

Follow the project’s ESLint and Prettier rules.
License :page_with_curl:
Legal Info
This project is licensed under the MIT License. See the LICENSE file.
Contact :mailbox:
Get in Touch

Email: your-email@example.com
GitHub: your-username

Thank you for supporting Women-Chama! Let’s empower women’s financial independence together! :heart:
