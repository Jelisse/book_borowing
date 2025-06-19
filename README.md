# book_borowing
an AI-powered Book Borrowing Recognition System using webcam-based face classification and a Flask backend.
Project Overview Bullet Points: - Real-time student recognition via webcam - Log borrow events to a
database - Frontend: HTML + JavaScript (ml5.js) - Backend: Flask + SQLite

Part 1: Training the Student Recognition Model Bullet Points: - Capture webcam input with p5.js -
Extract features using MobileNet - Label images and train classifier - Save model as JSON + weights

Part 2: Loading the Trained Model Bullet Points: - Load MobileNet feature extractor - Load saved
classifier model - Begin classification loop

Part 3: Flask Backend & SQLite Bullet Points: - app.py handles routes - SQLite DB stores logs - Table
includes student, book, date/time

Part 4: Web Interface Bullet Points: - HTML form: webcam + book input - JS sends fetch POST request
- Flask stores data


Viewing Logs Bullet Points: - Flask route /alldata - View all logs in a table format - Useful for
admins
