# Expense Management System

A smart, fast, and user-friendly way to track your expenses — powered by FastAPI & Streamlit.

🚀 Overview

The Expense Management System is a full-stack application designed to help users record, visualize, and manage daily expenses effortlessly.
Built with a clean architecture and modern technologies, it features a Streamlit-powered interactive UI and a FastAPI backend for blazing-fast data processing.

This project is perfect for learning or demonstrating skills in:
- ✅ API design
- ✅ Data handling
- ✅ UI/UX for dashboards
- ✅ Full-stack Python development
- ✅ Testing and modular architecture

## Tech Stack
| Layer    | Technology Used                  |
| -------- | -------------------------------- |
| Frontend | Streamlit                        |
| Backend  | FastAPI + Uvicorn                |
| Database | MySQL / SQLite (customizable)    |
| Testing  | Pytest                           |
| API Docs | Swagger & ReDoc (Auto-generated) |


## Project Structure

- **frontend/**: Contains the Streamlit application code.
- **backend/**: Contains the FastAPI backend server code.
- **tests/**: Contains the test cases for both frontend and backend.
- **requirements.txt**: Lists the required Python packages.
- **README.md**: Provides an overview and instructions for the project.


## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/expense-management-system.git
   cd expense-management-system
   ```
1. **Install dependencies:**:   
   ```commandline
    pip install -r requirements.txt
   ```
1. **Run the FastAPI server:**:   
   ```commandline
    uvicorn server.server:app --reload
   ```
1. **Run the Streamlit app:**:   
   ```commandline
    streamlit run frontend/app.py

   ```
