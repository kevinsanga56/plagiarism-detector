📚 Plagiarism Detector

An innovative tool to help educators maintain academic integrity by detecting plagiarism in student submissions.

Developed as a 3rd-year group project at Meru University of Science and Technology (Group 1, 6 members), this project allows teachers to create exams, collect student submissions, and automatically evaluate content originality.

Table of Contents

Introduction

Features

Installation

Usage

How It Works

Study Background

Contributing

License

References

Introduction 🚀

The Plagiarism Detector is a web-based application designed to assist educators in maintaining academic integrity. It allows teachers to create exams, receive student submissions, and automatically evaluate the originality of the content. By generating detailed reports with plagiarism percentages and potential sources of duplication, the system fosters fairness and encourages students to produce original work.

Features 🌟

User-Friendly Interface: Easy navigation for teachers and students.

Exam Creation & Uploading: Quickly create exams and upload questions in multiple formats.

Student Submissions: Secure submission system supporting text and document uploads (.docx, .pdf).

Plagiarism Detection: Uses advanced algorithms to detect copied content, paraphrasing, and improper citations.

Automated Marking: Evaluates student answers based on predefined criteria.

Detailed Reports: Comprehensive originality reports with export options (PDF/Excel).

Installation ⚙️

Clone the repository:

git clone https://github.com/kevinsanga56/plagiarism-detector.git
cd plagiarism-detector


Set up the virtual environment and install dependencies:

pipenv shell
pipenv install flask flask-sqlalchemy


Initialize the database:

python
>>> from app import db
>>> db.create_all()
>>> exit()


Run the application:

python app.py


Access the application:
http://127.0.0.1:5000

Usage 🚀

For Teachers:

Log in to create new exams, upload questions, and review student submissions.

View detailed originality reports and export them for records.

For Students:

Submit answers via the platform.

Receive feedback on originality and highlighted potential sources of plagiarism.

How It Works 🛠️

The Plagiarism Detector uses a combination of advanced techniques:

Text Matching: Identifies copied phrases and sentence structures.

Fingerprinting: Detects paraphrasing and structural similarities.

Citation Analysis: Checks for proper referencing and reduces false positives.

These methods provide a robust evaluation to ensure fair and accurate plagiarism detection.

Study Background 🎓

This project was inspired by research at Meru University of Science and Technology, which identified gaps in current plagiarism detection methods. By integrating automated tools with academic assessments, this project enhances fairness, encourages originality, and reduces academic misconduct.

Contributing 🤝

Contributions are welcome!

Fork the repository.

Create a branch for your feature:

git checkout -b feature/YourFeature


Submit a pull request for review.

License 📄

This project is licensed under the MIT License. See the LICENSE file for details.

References 🔗

Meru University of Science and Technology – Academic inspiration and study background.

GitHub Repository – Project source code and collaboration platform.

✅ Group Members:

Kevin Kiptum - Group Leader

Ismael Kipyegon

Timon Opiyo

Valilian Peterson Mwendwa

Dennis Korir

John Karanja
