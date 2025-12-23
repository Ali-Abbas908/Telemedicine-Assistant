Telemedicine Assistant

A lightweight, web-based Telemedicine Assistant designed to support basic healthcare interactions through a conversational interface. The application enables users to perform symptom checking using AI assistance and medicine availability lookup from a live pharmacy dataset, with full multilingual support (English & Punjabi).

📌 Features

Conversational Chat Interface

Clean, responsive UI built with Tailwind CSS

Real-time chat experience

AI-Based Symptom Analysis

Uses Google Gemini API for symptom interpretation

Provides general health guidance (non-diagnostic)

Displays mandatory medical disclaimers

Medicine Availability Checker

Fetches live data from Google Sheets (CSV)

Supports medicine name matching

Language-specific results

Multilingual Support

English

Punjabi (ਪੰਜਾਬੀ)

Quick Reply Buttons

Symptom Check

Medicine Availability

🛠️ Tech Stack

Frontend:

HTML5

Tailwind CSS

Vanilla JavaScript

APIs & Services:

Google Gemini AI (for symptom analysis)

Google Sheets (CSV export for medicine stock)

2. Configure Google Sheets (Medicine Stock)

Create a Google Sheet with the following columns:

Medicine (EN)	Status (EN)	Medicine (PA)	Status (PA)

Export it as CSV

Copy the CSV export URL

Paste it into the code:

3. Configure Google Gemini API

Create a Google Cloud project

Enable Generative Language API

Generate an API key

⚠️ Medical Disclaimer

This application does not provide medical diagnosis.
All AI-generated responses are for informational purposes only.
Users must consult a qualified medical professional for actual medical advice.

This disclaimer is automatically included in all AI symptom analysis responses.

🌍 Target Use Case

Rural and semi-urban healthcare support

Academic projects (AI, Web Development, HCI)

Telemedicine proof-of-concept applications

🚀 Future Enhancements

Backend integration (Node.js / Django / Flask)

User authentication

Voice input support

Mobile app (Android / Flutter)

Hospital & doctor directory integration

👤 Author

Ali Abbas
Bachelor’s Student – Computer Science & Engineering
