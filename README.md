# HealthMate

AI-powered medical assistant and symptom support platform built using Flask and GPT-based workflows. HealthMate provides structured symptom guidance, first-aid support, medicine awareness, and nearby hospital discovery through a responsive conversational interface.

---

## Features

- AI-powered medical chat assistant
- Symptom-based guidance system
- Basic medicine and precaution suggestions
- First-aid assistance workflows
- Nearby hospital locator using geolocation
- GPT-enhanced conversational responses
- Safety-filtered response generation
- RESTful backend architecture
- Rate limiting and caching support
- Responsive multi-query chat interface

---

## Tech Stack

### Backend
- Python
- Flask
- REST APIs

### Frontend
- HTML
- CSS
- JavaScript

### AI Integration
- GPT API
- Prompt engineering
- Rule-based symptom mapping

### APIs & Services
- OpenStreetMap
- Geolocation APIs

---

## System Flow

```text
User Query
   ↓
Frontend Chat Interface
   ↓
Flask Backend
   ↓
Rule-Based Medical Logic
   ↓
GPT Response Processing
   ↓
Safety Validation Layer
   ↓
Structured Response Output
```

---

## Project Structure

```text
HealthMate
├── app.py
├── routes
├── services
├── templates
├── static
├── utils
├── requirements.txt
└── .env
```

---

## Core Modules

- Symptom query processor
- AI response engine
- Medicine suggestion system
- First-aid guidance module
- Hospital locator service
- Safety filter layer
- Chat interface controller

---

## Performance

- Optimized API request handling
- Reduced redundant calls through caching
- Rate limiting for stability
- Designed for scalable conversational flow
- Fast structured AI responses

---

## Use Cases

- Symptom assistance
- Basic healthcare guidance
- First-aid reference
- Nearby hospital search
- Health information support
- Educational medical assistance

---

## Installation

### Clone Repository

```bash
git clone https://github.com/rohit-gotgit/HealthMate.git
cd HealthMate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Setup Environment Variables

Create a `.env` file in the root directory:

```env
OPENAI_API_KEY=your_api_key
FLASK_ENV=development
```

### Run Application

```bash
python app.py
```

---

## Disclaimer

HealthMate is intended for educational and assistance purposes only.

The platform does not replace professional medical advice, diagnosis, or treatment. Users should consult qualified healthcare professionals for medical concerns or emergencies.

---

## Future Improvements

- Voice-based interaction
- Multi-language support
- Doctor appointment integration
- User medical history tracking
- Fine-tuned healthcare models
- Advanced analytics dashboard

---

## Author

Rohit Kumar  
Full Stack & AI Developer
