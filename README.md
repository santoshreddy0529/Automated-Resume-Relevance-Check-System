# Automated-Resume-Relevance-Check-System

Automated Resume Relevance Check System
A complete Flask web application for Innomatics Research Labs Hackathon that automates resume screening, scoring, and candidate evaluation against job requirements.

Features
PDF/DOCX Resume Parsing: Upload and analyze resumes in PDF/DOCX format.

Job Description Processing: Select sample JDs or create custom job requirements.

Automated Scoring: Relevance Score (0-100%) based on Skills (40%), Experience (30%), Education (30%).

Skills Gap Analysis: Highlights missing skills, qualifications, or certifications.

High/Medium/Low Verdict: For each candidate, instantly classifies resume suitability.

Personalized Feedback: Generates actionable suggestions for candidates.

Dashboard: User-friendly, professional web dashboard with analytics & filters.

Analytics Panel: Track statistics, average scores, and common skill gaps.

Installation
Install Python 3.7+

Clone or Download the project files.

Install dependencies:

text
pip install -r requirements.txt
Usage
Run the Flask application:

text
python app.py
or for user convenience:

text
python run.py
or use start.bat (Windows) or start.sh (Linux/Mac).


Project Structure
text
project/
├── app.py                  # Main Flask backend app
├── templates/
│   └── index.html          # Web UI template
├── requirements.txt        # Dependencies
├── run.py                  # Launcher script
├── start.bat               # Windows startup
├── start.sh                # Linux/Mac startup
└── uploads/                # Upload directory (auto-created)
How It Works
Set Job Requirements: From sample JDs or custom entry

Upload Resume: System parses and extracts candidate data

Scoring and Analysis: Automated match, skill gaps highlighted

View Results: Suitability, missing elements, custom feedback

Analytics: Track batch stats and common issues to improve candidates

Technology Stack
Backend: Flask (Python)

Text Parsing: PyPDF2, docx2txt

Frontend: HTML, CSS, JavaScript

Data Handling: In-memory for demo; easy to adapt for database

Scripts: Includes run.py, start.bat, start.sh for easy launching

Hackathon Compliance
Automated resume evaluation and scoring at scale

Output of Relevance Score (0-100), skills gap, and verdict

Personalized feedback for improvement

Dashboard for placement team

Hybrid rule-based and semantic scoring

Sample data and UI integration

Future Improvements
Add database (SQLite/PostgreSQL) for persistent storage

Integrate advanced NLP/ML models for semantic checking

Develop user authentication for multi-role access

Connect to job portals and LinkedIn for real-world data

License
This project was developed as part of the Innomatics Research Labs hackathon and is provided for educational & demonstration purposes.

Author
Built using original hackathon sample JDs and resumes
