# MultiAgent AI Project

## Overview
This project is a Multi-Agent AI system that handles mentoring and leave applications using artificial intelligence. It includes agents that manage mentoring interactions and process leave applications efficiently.

## Features
- Utilizes Groq API for AI processing
- AI-powered mentoring system
- Leave application processing
- JSON-based data storage
- FastAPI backend with Uvicorn
- Streamlit-based UI
- Deployment-ready configuration

## Installation

### Prerequisites
Ensure you have the following installed:
- Python 3.8+
- pip (Python package manager)

### Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/MultiAgent_AI_Project.git
   cd MultiAgent_AI_Project
   ```
2. Create a virtual environment and activate it:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage
To run the project, you only need to start these two services:

1. **Backend (FastAPI with Uvicorn):**
   ```sh
   uvicorn mentoringAgent:app --reload
   ```
2. **Frontend (Streamlit UI):**
   ```sh
   streamlit run app.py
   ```

Ensure both are running simultaneously in separate terminal windows to allow the frontend to communicate with the backend.

## Deployment
The project includes deployment configuration for platforms like Heroku. Ensure the `Procfile` and `runtime.txt` are correctly set up.

## License
This project is licensed under the MIT License.

## Contributors
- Nibedita Mohanty (@Nibedita-1)

## Acknowledgments
Special thanks to all contributors and AI research teams for inspiration.


