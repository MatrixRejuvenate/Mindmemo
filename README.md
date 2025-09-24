A flash card app for easy memorization
Flashcard App

A simple web application for creating, editing, and managing flashcards. Built using Flask, this app allows users to register, log in, and organize flashcards with CRUD (Create, Read, Update, Delete) functionality.

📂 Project Structure
├── instance
│   └── mydb.db           # SQLite database
├── static
│   ├── img/              # Images used in the app
│   └── styles.css         # CSS and styling
├── templates
│   ├── card.html         # Flashcard view template
│   ├── delete.html       # Flashcard deletion page
│   ├── edit.html         # Edit flashcard page
│   ├── flash.jpeg        # Example/branding image
│   ├── index.html        # Home page
│   ├── login.html        # Login page
│   ├── main.html         # Main dashboard
│   ├── register.html     # Registration page
│   └── time.html         # Extra page (time tracking, etc.)
├── .gitattributes        # Git attributes file
├── app.py                # Flask application entry point
└── README.md             # Documentation

⚙️ Features

User registration & login

Create, view, edit, and delete flashcards

Store flashcards securely in a SQLite database

Simple UI with HTML templates

Static assets for images and styling

🚨 Current Issues
-Security: Passwords may not be hashed properly. Session management improvements needed.
-User Integrity: Flashcards are not strictly tied to individual users (possible data leaks).

Possible Improvements
UI/UX Enhancements:
-Better styling with modern CSS frameworks (Bootstrap/Tailwind).
-Responsive design for mobile users.

Security Improvements:
Hash and salt user passwords (e.g., bcrypt).
Implement role-based authentication.

Data Integrity:
Ensure flashcards are user-specific (no cross-user access).
Add validation for input fields.

Extra Features:

Tagging and categorization of flashcards.
Timer or spaced-repetition system (SRS).
Export/import flashcards.



TechStack:
Flask
SQLlite
HTML/CSS