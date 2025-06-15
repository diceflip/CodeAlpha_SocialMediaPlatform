# FeedFlip - Social Media Platform

FeedFlip is a mini social media platform built with Python and Django as part of the CodeAlpha Full Stack Development Internship.

## Features

*   User Registration and Login
*   User Profiles with Bio and Profile Pictures
*   Create, View, Edit, and Delete Posts (with optional image uploads)
*   Commenting on Posts
*   Liking/Unliking Posts
*   Following/Unfollowing Users
*   User Search Functionality
*   Responsive Design for Desktop and Mobile

## Technologies Used

*   **Backend:** Python, Django
*   **Frontend:** HTML, CSS, JavaScript
*   **Database:** SQLite (for development)
*   **Key Django Packages:**
    *   `Pillow` (for image handling)
    *   `python-decouple` (for environment variable management)
*   **Frontend Libraries/Frameworks (if any):**
    *   Font Awesome (for icons)

## Setup and Run Locally

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/CodeAlpha_SocialMediaPlatform.git
    cd CodeAlpha_SocialMediaPlatform
    ```
2.  **Create and activate a virtual environment:**
    ```bash
    python -m venv venv_social
    # On Windows:
    # venv_social\Scripts\activate
    # On macOS/Linux:
    # source venv_social/bin/activate
    ```
3.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
4.  **Create a `.env` file** in the project root and add your settings:
    ```env
    SECRET_KEY=your_very_secret_random_key_here
    DEBUG=True
    # Add other necessary environment variables if any
    ```
5.  **Apply migrations:**
    ```bash
    python manage.py makemigrations
    python manage.py migrate
    ```
6.  **Create a superuser (for admin access):**
    ```bash
    python manage.py createsuperuser
    ```
7.  **Run the development server:**
    ```bash
    python manage.py runserver
    ```
    The application will be available at `http://127.0.0.1:8000/`.

## Live Demo (Optional)

[Link to your live demo if you deploy it]

## Internship Task

This project fulfills Task 2 of the CodeAlpha Full Stack Development Internship.