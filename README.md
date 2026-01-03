CMP2808-Cloud-and-Web-Services---Assessment-1-React-Native-# CMP2808 Cloud and Web Services - Assessment 1



📖 Project Description

This project is a RESTful API developed using **Python** and **FastAPI** for the CMP2808 Assessment 1. The application is designed to interface with the **AdventureWorks** database, providing a set of endpoints to perform CRUD (Create, Read, Update, Delete) operations.

The project demonstrates:
-   **REST API Architecture**: Implementation of GET, POST, PUT, and DELETE methods.
-   **Data Validation**: Utilization of **Pydantic** models to ensure data integrity.
-   **Documentation**: Automatic interactive API documentation via Swagger UI and ReDoc.
-   **Testing**: HTTP file based testing for endpoint verification.

🚀 Features

-   **FastAPI Framework**: High-performance web framework for building APIs with Python 3.7+.
-   **Interactive Documentation**:
    -   Swagger UI available at `/docs`
    -   ReDoc available at `/redoc`
-   **Basic Endpoints** (Current Implementation):
    -   `GET /`: Root endpoint returning a welcome message.
    -   `GET /hello/{name}`: Personalized greeting endpoint.

🛠️ Prerequisites

Ensure you have the following installed on your local machine:
-   **Python 3.x**
-   **pip** (Python Package Installer)
-   **Visual Studio Code** (Recommended IDE)

📦 Installation & Setup

1.  **Clone or Download the Repository**
    Extract the project files to your desired directory.

2.  **Set Up Virtual Environment**
    It is recommended to run this project within a virtual environment.
    ```bash
    # Create virtual environment
    python -m venv venv

    # Activate virtual environment (Windows)
    .\venv\Scripts\activate
    ```

3.  Install Dependencies**
    Install the required packages (FastAPI and Uvicorn).
    ```bash
    pip install fastapi uvicorn
    ```

## 🏃‍♂️ Running the Application

To start the local development server, run the following command in your terminal:

```bash
uvicorn main:app --reload
