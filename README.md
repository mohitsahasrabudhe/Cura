# Cura
A personal health and insurance assistant app that integrates wearable data, manual health inputs, and insurance documents to provide actionable wellness insights, reminders, and cost-efficient medical recommendations.


cura-personal-medical-assistant/
├── README.md
├── LICENSE
├── .gitignore
├── backend/
│   ├── app/
│   │   ├── main.py         # FastAPI entrypoint
│   │   ├── models.py       # DB models
│   │   ├── routes.py       # API endpoints
│   │   ├── services/       # AI & health logic
│   │   └── utils/          # helpers, CPT/insurance parsing
│   ├── requirements.txt    # Python dependencies
├── frontend/
│   ├── mobile/             # React Native / Flutter app
│   │   ├── App.js
│   │   ├── components/
│   │   └── screens/
├── docs/                   # Architecture diagrams, API specs
└── tests/
    ├── backend/
    └── frontend/



# Cura Personal Medical Assistant

Cura is a personal health and insurance assistant app that integrates wearable data, manual health inputs, and insurance documents to provide actionable wellness insights, reminders, and cost-efficient medical recommendations.

## Features
- Sync data from smartwatches and wearable devices
- Track health metrics manually (bowel movements, mood, hydration, supplements)
- Personalized nudges and reminders
- Insurance document parsing and coverage recommendations
- CPT code-based preventive checkup guidance
- Scheduling and lab/provider suggestions

## Tech Stack
- Backend: Python + FastAPI
- Frontend: React Native (iOS & Android)
- Database: PostgreSQL / Firebase
- AI Layer: GPT-style model for personalized insights
- Integrations: Apple Health, Google Fit, Zocdoc API, LabCorp API

## Repo Structure
- `backend/` - FastAPI server and health logic
- `frontend/` - Mobile app
- `docs/` - Diagrams, specs
- `tests/` - Unit & integration tests
