# 🏫 School Management System - Backend

A robust and scalable backend API for the Nova School Management System, built with **Django** and **Django REST Framework**. This system manages core educational data including students, teachers, academic programs, events, and testimonials.

## 🚀 Features

-   **User Authentication**: Secure authentication for students, teachers, and administrators.
-   **Teacher Management**: Profiles, subject assignments, and details.
-   **Program & Curriculum**: Management of academic programs, courses, and schedules.
-   **Event Scheduling**: Calendar and event management for school activities.
-   **Testimonials**: System for collecting and displaying feedback from students and parents.
-   **Media Management**: Handling of images and documents (profiles, event banners).

## 🛠️ Tech Stack

-   **Framework**: Django 5.x
-   **API**: Django REST Framework (DRF)
-   **Database**: SQLite (Development) / PostgreSQL (Production ready)
-   **Authentication**: JWT / Session-based
-   **CORS**: `django-cors-headers` for frontend integration

## 📂 Project Structure

```bash
backend/
├── school/                 # Core app (Students, General Logic)
├── teachers/               # Teacher management app
├── programs/               # Academic programs app
├── events/                 # Event management app
├── testimonials/           # Feedback & Testimonials app
├── school_management_app/  # Project configuration (Settings, URLs)
├── media/                  # User uploaded content
└── manage.py               # Django CLI utility
```

## 🔧 Installation & Setup

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

5.  **Run the Development Server**
    ```bash
    python manage.py runserver
    ```
    The API will be available at `http://127.0.0.1:8000/`.

## 📡 API Endpoints (Examples)

-   `GET /api/teachers/` - List all teachers
-   `GET /api/programs/` - List available programs
-   `GET /api/events/` - Upcoming events
-   `POST /api/testimonials/` - Submit a testimonial

## 🤝 Contributing

1.  Fork the repository
2.  Create your feature branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## 📝 License

This project is licensed under the MIT License.
