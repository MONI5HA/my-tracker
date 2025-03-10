My  Personal Tracker

🚀 Overview

My-Tracker is a dynamic and interactive web application built with React.js and Firebase that allows users to store and retrieve questions and answers categorized under different topics. Users can:

📌 Add questions & answers under specific categories.

🔍 Fetch and display them in a clean, responsive UI.

🎨 Select different categories dynamically.

📊 Store data in Firebase in an organized way.

🛠️ Tech Stack

Frontend: React.js, Tailwind CSS

Backend: Firebase Realtime Database

Hosting: Firebase Hosting

Version Control: Git & GitHub

🌟 Features

✅ Category-based Data Storage – Organizes questions under topics like Web Development, AI/ML, DevOps, etc.
✅ Beautiful & Responsive UI – Fully mobile-friendly layout with Tailwind CSS.
✅ Firebase Integration – Realtime database to store and retrieve questions dynamically.
✅ Smooth Animations – Interactive hover and transition effects.
✅ Easy Deployment – Hosted on Firebase for quick access.

📂 Project Structure

my-tracker/
│-- src/
│   │-- components/
│   │   ├── CardView.js  # Card layout for displaying questions
│   │   ├── QuestionsList.js  # Fetch & display questions dynamically
│   │   └── Navbar.js  # Navigation bar (if added)
│   │-- firebaseConfig.js  # Firebase configuration
│   ├── App.js  # Main application file
│   ├── index.js  # Entry point
│
│-- public/
│   ├── index.html  # Main HTML file
│
│-- package.json  # Dependencies & scripts
│-- README.md  # Project Documentation

🏗️ Installation & Setup

Follow these steps to set up the project on your local machine:

1️⃣ Clone the Repository

git clone https://github.com/MONI5HA/my-tracker.git
cd my-tracker

2️⃣ Install Dependencies

npm install

3️⃣ Setup Firebase

Go to Firebase Console

Create a new project & enable Firebase Realtime Database.

Copy your Firebase config and update firebaseConfig.js.

4️⃣ Run the Project Locally

npm start

The app will be available at http://localhost:3000.

🚀 Deployment (Firebase Hosting)

Build the project:

npm run build

Deploy to Firebase:

firebase deploy

Your project will be live at https://your-project-name.web.app/ 🎉

🎯 Future Enhancements

🔹 Add user authentication with Firebase Auth.

🔹 Implement search & sorting features.

🔹 Store additional metadata like difficulty level.

🔹 Improve UI with animations & filters.


📞 Contact

👩‍💻 Developer: MONI5HA

🚀 Happy Coding! 🎉
