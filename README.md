# -MediSynth
 MediSynth: AI-Powered Prescription Synthesizer, Medication Reminder & Safety Assistant
🩺 Project Overview
MediSynth is an advanced AI-integrated healthcare assistant designed to bridge the gap between complex medical prescriptions and patient understanding. By combining OCR (Optical Character Recognition), Natural Language Processing (NLP), multilingual voice interaction, real-time medication risk analysis, and smart reminders, MediSynth empowers patients to take control of their health—safely, smartly, and in their own language.

🎯 Key Objectives
✅ Convert handwritten prescriptions into readable and understandable text.

✅ Offer multilingual, voice-based interactions for broader accessibility.

✅ Track medication history and flag potentially dangerous drug combinations.

✅ Set intelligent reminders for medications based on doctor’s instructions.

✅ Empower patients with side-effect monitoring and emergency alerts.

🌟 Core Features
🖋️ 1. Prescription OCR & Explanation Engine
Uses OCR (Tesseract/EasyOCR) to extract:

Medicine names

Dosages

Timings (e.g., "before food", "morning", "daily 2x")

Duration

AI agent interprets and explains:

What each drug does

How/when to take it

Common side effects

Dietary precautions

🗣️ 2. Real-Time Multilingual Voice Assistant
Converts speech to text (using Whisper/Google STT) and speaks responses (via gTTS/Bark).

Supports regional languages: Telugu, Hindi, Tamil, Malayalam.

Voice interactions:

“What is this tablet for?”

“When should I take my next dose?”

“What are the side effects?”

🧠 3. AI-Integrated Medication Reminder System 🕒
Automatically sets reminders based on extracted data from the prescription:

Example: “Take Paracetamol 500mg at 8 AM before breakfast for 5 days.”

Features:

Push/mobile or desktop notifications

Voice alerts in user's chosen language

Smart repeat scheduling (daily, weekly, 3 times/day)

"Snooze" or "Taken" confirmation options

Integration with:

Google Calendar or local device alarms

Optional WhatsApp/SMS reminders for rural users

📖 4. Medication History & Side Effect Tracker
Logs all past prescriptions, medicine names, dosages, and schedules.

User can:

Manually log side effects

View medication timeline

Receive alerts for recurring symptoms

AI detects patterns and suggests:

Possible allergies

When to consult a doctor

🚨 5. Drug Interaction Risk Detection & Emergency Alerts
Checks for harmful combinations using:

DrugBank / RxNorm / OpenFDA APIs

AI flags:

Duplicate medicines

Allergic combinations

Black-box warnings (e.g., interactions with alcohol, other drugs)

Displays emergency alerts and suggestions for safer alternatives

⚙️ Technology Stack
Layer	Tools / Libraries
OCR	Tesseract, EasyOCR
AI Agent	GPT-4 / Gemini + LangChain
STT / TTS	Whisper, Google STT, gTTS, Bark, Polly
Reminder System	Python scheduler (APScheduler), push notifications, Google Calendar API
Multilingual NLP	IndicNLP, iNLTK, Google Translate
Database	SQLite / PostgreSQL
Drug APIs	DrugBank, RxNorm, OpenFDA
Frontend	Streamlit / Flutter / React
Backend	Flask / FastAPI
Deployment	AWS / Heroku / GCP

🔐 Privacy & Security
Medical history and reminder schedules are encrypted and stored securely.

User controls notification settings and language preferences.

No data is shared without user consent.

🔮 Future Enhancements
Integration with IoT pillboxes for real-time intake confirmation.

Use of LLMs for symptom triaging and doctor consult recommendations.

Add support for wearable voice commands (smartwatch integration).

🧾 Sample Use Case (User Journey)
User uploads a photo of a doctor’s prescription.

MediSynth extracts text, understands dosage, and sets reminders.

AI explains medications in Telugu using speech output.

User logs side effects after 3 days.

AI cross-checks side effects and warns about a risky combination.

Emergency alert shown, with a suggestion to contact the doctor.

💬 Tagline Suggestions
“MediSynth – Smarter care. Safer medicine. In your voice.”

“AI that understands your prescription—and speaks your language.”

“Decode. Remind. Protect. Your health, synthesized.”


