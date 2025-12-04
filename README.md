# 🏫 Nova School Management System - Backend

A robust, scalable, and secure RESTful API for the Nova School Management System, built with **Django** and **Django REST Framework**. This backend powers the frontend application, managing data consistency, user authentication, and business logic.

## 🚀 Live API

**Base URL:** [https://school-managment-app-backend.onrender.com](https://school-managment-app-backend.onrender.com)

## 🛠️ Technologies Used

-   **Framework:** [Django](https://www.djangoproject.com/) (v5.x) - High-level Python web framework.
-   **API Toolkit:** [Django REST Framework (DRF)](https://www.django-rest-framework.org/) - For building Web APIs.
-   **Database:**
    -   **Development:** SQLite
    -   **Production:** PostgreSQL (Recommended for scaling)
-   **Authentication:** Token-based authentication (DRF Auth).
-   **Server:** [Gunicorn](https://gunicorn.org/) - WSGI HTTP Server for UNIX.
-   **CORS:** `django-cors-headers` - Handling Cross-Origin Resource Sharing.
-   **Deployment:** [Render](https://render.com/)

## ✨ Key Features

-   **RESTful Endpoints:** Comprehensive API endpoints for CRUD operations.
-   **Authentication & Authorization:** Secure user registration, login, and role-based access control.
-   **Data Management:**
    -   **Teachers:** Manage profiles, subjects, and images.
    -   **Students:** Grade tracking and profile management.
    -   **Programs:** Course details, pricing, and schedules.
    -   **Events:** Event planning and announcements.
-   **Media Handling:** Serving static and media files (images, documents).
-   **Admin Panel:** Built-in Django Admin interface for easy content management.

## 📂 Project Structure

```bash
backend/
├── school/                 # Core application logic
├── teachers/               # Teacher management app
├── programs/               # Academic programs app
├── events/                 # Event management app
├── testimonials/           # Feedback system app
├── school_management_app/  # Project settings and configuration
├── media/                  # Uploaded media files
└── manage.py               # Django command-line utility
```

## 🔧 Installation & Setup

To run this project locally:

1.  **Clone the repository**
    ```bash
    git clone https://github.com/Osama-2024-Ahmad/school_managment_app_backend.git
    cd school_managment_app_backend
    ```

2.  **Create a Virtual Environment**
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3.  **Install Dependencies**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Apply Migrations**
    ```bash
    python manage.py migrate
    ```

5.  **Create a Superuser (Optional)**
    ```bash
    python manage.py createsuperuser
    ```

6.  **Start the Development Server**
    ```bash
    python manage.py runserver
    ```
    The API will be available at [http://127.0.0.1:8000/](http://127.0.0.1:8000/).

## 🤝 Frontend

This backend serves the Nova School Management Frontend.
**Frontend Repository:** [Link to Frontend Repo](https://github.com/Osama-2024-Ahmad/school_managment_app_frontend)
**Live App:** [https://school-managment-app-frontend.vercel.app/](https://school-managment-app-frontend.vercel.app/)


