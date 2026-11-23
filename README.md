# math-prep-hub
Tutoring hub for math lessons, student progress, exam prep, study files, and AI-powered study support.

A web application built to organize online math tutoring sessions, track student progress across school levels and national exams, manage weekly curriculum coverage, and share study resources—designed to grow into an AI-assisted study and messaging workspace.

## Why This Project Exists

Tutoring sessions, exam prep notes, curriculum pacing, and study materials often end up scattered across chats, spreadsheets, and folders. **Math Prep Hub** brings the tutor and student workflow into one structured place so every session builds intentionally toward exam readiness.

## Core Features (MVP)

- **Tutor & Student Views:** Dedicated access and views for the tutor and each student to track what has been covered and what comes next.
- **Online Session Launch (Google Meet):** Quick access to Google Meet links for starting and joining online lessons directly from the app.
- **Progress Tracking:** Per-student tracking across middle school, high school, the 8th-grade national exam (*Evaluarea Națională*), and the Baccalaureate (*Bacalaureat* across tracks), including topic mastery and test/exam practice history.
- **Weekly Curriculum Structure:** A structured weekly plan so the tutor can see which lessons should be covered each week and stay on track with the syllabus (for instance, moving cleanly from plane geometry to solid geometry).
- **Study Materials Hub:** Upload and organize worksheets, formula sheets, and practice exam sets that students can open and use easily.

## Planned Next Phases

1. **AI Q&A Over Uploaded Materials:** Allow students to ask questions grounded in study files and notes uploaded by the tutor, with clear explanations and examples.
2. **Direct In-App Messaging:** Enable students to send questions and updates directly inside the platform between sessions.
3. **Smarter Practice & Insights:** Generate targeted practice problems and progress summaries based on recurring mistakes.

## Tech Stack (Initial Setup)

- **Language:** Python
- **Web Interface:** Streamlit (rapid interactive UI and deployment)
- **Version Control:** Git & GitHub

## Local Setup

```bash
git clone [https://github.com/mariasarosi8-wq/math-prep-hub.git](https://github.com/mariasarosi8-wq/math-prep-hub.git)
cd math-prep-hub
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
streamlit run app.py
