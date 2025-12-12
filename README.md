<img width="1364" height="601" alt="Screenshot 2025-12-12 124421" src="https://github.com/user-attachments/assets/af5b846c-c3a6-466e-8d6a-ea7e2760cb9b" />
<img width="1352" height="597" alt="Screenshot 2025-12-12 124435" src="https://github.com/user-attachments/assets/48da0d2d-dcd4-4d68-9d0b-a1999cd4308f" />
<img width="1331" height="593" alt="Screenshot 2025-12-12 124449" src="https://github.com/user-attachments/assets/17ebf8da-fbeb-42ed-b691-6d81408a88f5" />
<img width="1346" height="650" alt="Screenshot 2025-12-10 153300" src="https://github.com/user-attachments/assets/55bfa227-590d-40b6-bd27-7815688eaaad" />
<img width="1359" height="666" alt="Screenshot 2025-12-12 124519" src="https://github.com/user-attachments/assets/03c0d986-50f0-4978-9f05-3133bef809d1" />

📚 AI-Powered Educational Communication Chatbot (Python Only)

A fully Python-based intelligent chatbot designed to streamline communication between students, parents, and educators. This system uses Natural Language Processing (NLP), automated deadline checking, document reading, and messaging features to deliver accurate, real-time educational assistance.

🚀 Features
🤖 1. AI-Powered NLP Chatbot

Built entirely with Python using NLP libraries and/or LLM APIs.

Provides human-like responses to questions about units, deadlines, registration, academics, fees, and institutional information.

📄 2. Document Upload & Smart Reading

Accepts PDF or text files.

Extracts content using Python libraries (PyPDF2, pdfplumber, Tesseract OCR if needed).

Answers user queries based on document content.

🗂️ 3. Automated Deadline Tracking

Reads CSV files containing:

assignment deadlines

registration dates

exam schedules

Automatically sends reminders using:

Email

WhatsApp API

SMS (Twilio or other API)

💬 4. Web or Desktop Interface (Python-Based)

Choose any UI method:

Flask / Django web interface OR

Tkinter / PyQt desktop chatbot UI
(No React or Node.js used.)

🗄️ 5. Dataset-Based Chatbot Training

Trained using Python on education-related CSV datasets.

Improves its accuracy and responses over time.

🛠️ Tech Stack (Python Only)
Core Technologies

Python 3.x

NLP: Transformers / spaCy / OpenAI API

Pandas (CSV and dataset processing)

SQLAlchemy

MS SQL Server / SQLite (depending on project scale)

Backend Framework

Flask or Django (your choice)

Document Processing

PyPDF2

pdfplumber

pytesseract (OCR)

Notifications

smtplib (Email)

Twilio / WhatsApp API

APScheduler for automated reminders

UI Options (No React, No JS frameworks)

Flask HTML templates

Bootstrap / Tailwind CSS (optional)

Or a desktop GUI (Tkinter/PyQt)

📁 Project Structure
├── chatbot/
│   ├── app.py                     # Flask/Django main application
│   ├── nlp/
│   ├── services/
│   ├── utils/
│   ├── models/
│   ├── static/                    # CSS (optional)
│   ├── templates/                 # HTML templates (no JS frameworks)
│   └── data/
│       ├── deadlines.csv
│       ├── education_dataset.csv
│       └── sample_documents/
└── README.md

⚙️ Installation & Setup
1. Clone the Repository
git clone https://github.com/yourusername/ai-education-chatbot.git
cd ai-education-chatbot

2. Install Dependencies
pip install -r requirements.txt

3. Run the Chatbot App

For Flask:

python app.py


For Django:

python manage.py runserver

🔧 Environment Variables

Create a .env file:

AI_API_KEY=
DB_HOST=
DB_USER=
DB_PASSWORD=
EMAIL_USER=
EMAIL_PASSWORD=
WHATSAPP_API_KEY=
SMS_API_KEY=

🔄 System Workflow

User interacts with the chatbot via a Python-based UI (Flask, Django, or desktop app).

Message is processed by the Python NLP engine.

If a document is uploaded, system extracts text and analyzes it.

Deadlines in CSV files are checked automatically.

Email, WhatsApp, or SMS reminders are sent if deadlines approach.

Chatbot returns accurate, context-aware responses.

🎯 Project Objective

To create a fully Python-based, AI-powered chatbot that enhances educational communication by automating queries, reading documents, tracking deadlines, and delivering timely reminders.
