# 🍕 Pizzeria System

A web-based pizzeria management system built with **Python and FastAPI**, designed to handle core restaurant operations through a modular backend architecture.

This project is an ongoing development initiative focused on backend development, API design, application organization, and restaurant management workflows.

## 🚀 Technologies

- **Python** — Main programming language.
- **FastAPI** — Backend framework for building APIs.
- **Uvicorn** — ASGI server for running the application.

## ✨ Project Structure

The application follows a modular structure, separating different responsibilities into dedicated directories.

```text
pizzeria-system/
│
├── core/       # Core application components
├── models/     # Data models
├── routes/     # Application routes and endpoints
├── styles/     # Styling resources
│
└── main.py     # Application entry point
```

## 📌 Main Modules

- **Authentication:** Dedicated routes for authentication-related operations.
- **Login:** User login functionality.
- **Orders:** Routes dedicated to order management.
- **Main:** Main application routes and navigation.

## ⚙️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/murilohfms1/pizzeria-system.git

cd pizzeria-system
```

### 2. Create a virtual environment

**Windows:**

```bash
python -m venv venv
venv\Scripts\activate
```

**Linux / macOS:**

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install fastapi uvicorn
```

Install any additional dependencies required by the project.

### 4. Run the application

```bash
uvicorn main:app --reload
```

The application will be available at:

```text
http://127.0.0.1:8000
```

## 📖 API Documentation

FastAPI automatically provides interactive API documentation.

Once the application is running, access:

- **Swagger UI:** http://127.0.0.1:8000/docs
- **ReDoc:** http://127.0.0.1:8000/redoc

## 🛠️ Development

This project is continuously evolving, with ongoing improvements to its architecture, backend functionality, and application structure.

The main goal is to develop a maintainable and organized system while exploring backend development practices using Python and FastAPI.

## 👨‍💻 Author

**Murilo**

GitHub: [@murilohfms1](https://github.com/murilohfms1)

---

*This project is under active development.*
