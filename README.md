# AI Healthcare Assistant & Medical Report Analyzer
AI Healthcare Assistant & Medical Report Analyzer is a **Python and Flask-based healthcare application** developed to help users understand their medical reports and access general health-related assistance. It provides a centralized platform for **user authentication, AI-based health assistance, medical report analysis, and health insights**.

## ✨ Key Features

* 👤 **User Authentication** – Register and login securely to access the application.
* 🤖 **AI Healthcare Assistant** – Ask health-related questions and receive AI-generated general guidance.
* 📄 **Medical Report Upload** – Upload medical reports for analysis and information extraction.
* 🔍 **Report Analysis** – Analyze report values and identify important, high, low, or abnormal values.
* 📊 **Health Insights** – Provide simple explanations of medical report information and health-related insights.
* 💬 **Health Queries** – Interact with the AI assistant for general health-related questions.
* 🧠 **User Memory** – Maintain relevant user information to provide more personalized assistance.
* 📋 **Medical Report History** – Store and manage uploaded medical reports and related analysis.
* 🗄️ **Database Management** – Store user, report, analysis, and AI interaction data using MySQL.
* 🛡️ **Safe Health Guidance** – Provides general health information without giving medical diagnosis or prescriptions.

## 🛠️ Tech Stack

* **Python** – Core application development and backend logic
* **Flask** – Web application framework
* **MySQL** – Database management
* **HTML & CSS** – User interface
* **JavaScript** – Frontend interactions
* **Hugging Face** – AI model integration
* **PyMuPDF / PDF Processing** – Medical report text extraction
* **Pillow & Tesseract** – Image processing and OCR
* **python-dotenv** – Environment configuration

## 🔄 How It Works

```text
User Registration / Login
          ↓
       Dashboard
          ↓
   AI Assistant / Report Upload
          ↓
   ┌───────────────┐
   │               │
   ↓               ↓
Health Query    Medical Report
   ↓               ↓
AI Response     Text Extraction
                   ↓
              Report Analysis
                   ↓
          High / Low / Important Values
                   ↓
             Health Insights
```

## 💡 Project Highlights

* Developed a **complete AI-powered healthcare assistance application** using Python, Flask, and MySQL.
* Implemented **user authentication** with database-driven access.
* Integrated **Hugging Face AI** for health-related conversational assistance.
* Implemented medical report processing to **extract and analyze information from uploaded reports**.
* Provides simple explanations for **high, low, abnormal, and reference-range values**.
* Maintains structured records for **users, medical reports, blood analysis, symptom checks, health insights, and AI interactions**.
* Uses **MySQL and Flask** to manage application data and backend operations.
* Demonstrates practical implementation of **Python, Flask, SQL, database management, AI integration, file processing, and web application development**.

## 📂 Project Structure

```text
Healthcare_Assistant/
│
├── app.py
├── requirements.txt
│
├── templates/
│   ├── index.html
│   ├── login.html
│   ├── register.html
│   ├── dashboard.html
│   ├── ai_assistant.html
│   └── adding medical_reports.html
│
├── static/
│   ├── css/
│   │   └── style.css
│   │
│   └── js/
│       └── script.js
│
└── README.md
```

## 🎯 Objective

The main objective of this project is to provide a **centralized AI-powered healthcare assistance system** where users can upload medical reports, understand important health information, and interact with an AI assistant for general health guidance through a simple and accessible platform.

## 🔮 Future Enhancements

* Support for additional medical report formats
* Medical report comparison over time
* Improved personalized health insights
* Health reminders and notifications
* Voice-based healthcare assistance
* Health trend visualization
* Integration with wearable health data
