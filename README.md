# EduNexus AI
### Intelligent Campus Management Platform

**One Campus. One Platform. One Smarter Student Journey.**

EduNexus AI is an AI-powered campus management platform designed to unify academic services, student support, faculty operations, and administrative workflows within a single digital ecosystem.

The platform combines campus management capabilities with AI-assisted academic guidance to help students access essential information, monitor their academic progress, and discover relevant opportunities.

## Overview

Educational institutions often manage attendance, assignments, examinations, fees, timetables, and student support through separate systems and communication channels. This can make information difficult to access and academic progress harder to monitor.

EduNexus AI aims to simplify this experience through a unified platform that connects students, teachers, and administrators while providing intelligent academic insights and recommendations.

## Key Features

### Student Services
- Student dashboard for accessing academic information.
- Attendance tracking and attendance percentage monitoring.
- Assignment management and submission tracking.
- Timetable and examination information.
- Fee and payment record management.
- Student profile and academic information.

### AI-Powered Academic Support
- AI academic assistant for student queries.
- Academic risk analysis using relevant attendance and assignment indicators.
- Personalized recommendations to help students address academic concerns.
- Data-driven insights to support academic progress.

### Faculty & Administration
- Teacher dashboard and class management.
- Student attendance and assignment monitoring.
- Student performance insights.
- Department-level academic monitoring.
- Admission application and verification workflows.
- Campus information and notification management.

### Opportunity Radar
- Centralized discovery of internships and other student opportunities.
- Opportunity submission and review workflows.
- A foundation for connecting students with career-development resources.

## Technology Stack

| Component | Technology |
|---|---|
| Frontend | HTML5, CSS3, JavaScript |
| Backend | Python, FastAPI |
| ASGI Server | Uvicorn |
| Database | MySQL |
| ORM | SQLAlchemy |
| Data Validation | Pydantic |
| AI Capabilities | Academic risk analysis and recommendation logic |

## System Architecture

EduNexus AI follows a frontend–backend architecture.

1. **Frontend:** Provides interfaces for students, teachers, and administrators.
2. **Backend API:** FastAPI handles application routes and business logic.
3. **Database Layer:** MySQL stores application records, accessed through SQLAlchemy.
4. **AI Services:** Process relevant student academic indicators to support risk analysis and recommendations.

## Project Structure

The following is a representative structure; directory names may vary in the implementation.

```text
EduNexus-AI/
├── Backend/
│   ├── app.py
│   ├── models/
│   ├── routes/
│   ├── schemas/
│   └── services/
├── frontend/
│   ├── index.html
│   ├── login.html
│   ├── student/
│   ├── teacher/
│   └── ...
└── README.md
```

## Getting Started

### Prerequisites

- Python 3.10 or a compatible version.
- MySQL Server.
- Git.
- A modern web browser.

### 1. Clone the Repository

```bash
git clone https://github.com/faridishanaz761-hub/EduNexus-AI.git
cd EduNexus-AI
```

### 2. Create a Virtual Environment

```bash
python -m venv .venv
```

Activate it on Windows PowerShell:

```powershell
.venv\Scripts\Activate.ps1
```

### 3. Install Dependencies

If a `requirements.txt` file is available:

```bash
pip install -r requirements.txt
```

Otherwise, install the dependencies specified by the project and generate a requirements file.

### 4. Configure MySQL

- Start your MySQL server.
- Create the required project database.
- Configure the database connection using environment variables or the project's configuration mechanism.
- Keep credentials outside the repository.

### 5. Start the Backend

Run the command from the directory containing `app.py`:

```bash
uvicorn app:app --reload
```

The local API server should be available at:

`http://127.0.0.1:8000`

Interactive API documentation:

`http://127.0.0.1:8000/docs`

### 6. Launch the Frontend

Open the frontend entry page, such as `index.html`, using a browser or a local development server.

Make sure the frontend API URL matches the running backend address.

*Note: Actual setup requirements depend on the project's current configuration, dependencies, and database settings.*

## Project Objectives

- Unify essential campus services in one platform.
- Make academic information easier to access.
- Improve visibility into attendance and assignment progress.
- Provide AI-assisted academic recommendations.
- Support coordination between students, teachers, and administrators.
- Help students discover relevant internship and career opportunities.

## Sustainable Development Goals

**SDG 4 — Quality Education**

Supports access to academic information and personalized academic guidance.

**SDG 8 — Decent Work and Economic Growth**

Supports career awareness and discovery of internships and other opportunities.

## Future Scope

- Improve AI answer reliability through verified academic sources.
- Integrate with other educational institutions and campus systems.
- Expand adaptive learning and predictive academic planning.
- Develop broader academic analytics and decision-support capabilities.

## Security

Security and privacy are essential for educational platforms.

- Never commit `.env` files, API keys, passwords, or database credentials.
- Avoid publishing private student records or confidential institutional data.
- Configure authentication and role-based access controls before production deployment.
- Validate and authorize requests to sensitive APIs.

## Project Information

- **Project Name:** EduNexus AI
- **Category:** AI-Powered Education Technology
- **Team Name:** CampusFlow
- **Event:** National Hackathon 6.0

## License

No license has been specified yet. A suitable license can be added once the project's reuse and distribution terms have been decided.
