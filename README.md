# 🎟️ EventHub — Event Management REST API

EventHub is a backend REST API built using **Django** and **Django REST Framework** to manage events and reservations. It provides API endpoints for working with events, reserving seats, and managing reservations.

The project uses **PostgreSQL** as its database, with Docker Compose for database container management.

## 🚀 Features

- **Event Management:** Create, retrieve, update, and delete events.
- **Reservation Management:** Create and manage event reservations.
- **RESTful APIs:** API endpoints built using Django REST Framework.
- **Data Validation:** Validate reservation details and event availability.
- **Seat Availability:** Check available seats before accepting reservations.
- **Reservation Cancellation:** Support for cancelling reservations.
- **PostgreSQL Database:** Store application data in PostgreSQL.
- **Docker Integration:** Run PostgreSQL using Docker Compose.

## 🛠️ Tech Stack

- Python
- Django
- Django REST Framework
- PostgreSQL
- Docker
- Docker Compose
- Git and GitHub

## 📁 Project Structure

```text
EventHub/
│
├── eventhub/
│   ├── eventhub/
│   │   ├── settings.py
│   │   ├── urls.py
│   │   ├── asgi.py
│   │   └── wsgi.py
│   │
│   ├── events/
│   │   ├── migrations/
│   │   ├── models.py
│   │   ├── serializers.py
│   │   ├── views.py
│   │   ├── urls.py
│   │   └── admin.py
│   │
│   ├── manage.py
│   ├── docker-compose.yml
│   └── requirements.txt
│
├── .gitignore
└── README.md
```

*Note: The structure above is illustrative. Your actual project structure may differ.*

## ⚙️ Prerequisites

Install the following tools before running the project:

- Python 3.10 or later
- Docker Desktop
- Git

You should also have a GitHub account if you want to contribute or host the source code.

## 📥 Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/HARSHRATHI2005/EventHub.git
cd EventHub
```

### 2. Navigate to the Django Project

```bash
cd eventhub
```

### 3. Create a Virtual Environment

**Windows PowerShell:**

```powershell
python -m venv .venv
```

Activate the environment:

```powershell
.\.venv\Scripts\Activate.ps1
```

### 4. Install Dependencies

If `requirements.txt` is available,
