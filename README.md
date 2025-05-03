Project Setup Guide
This guide provides step-by-step instructions to set up your project environment, including setting up a Python virtual environment using Pipenv, pip, or conda.

Table of Contents
Setting Up a Python Virtual Environment
Using pip and venv
Running the application
Setting Up a Python Virtual Environment
Using pip and venv
Create a Virtual Environment:
python3 -m venv venv
Activate the Virtual Environment:
macOS/Linux:

source venv/bin/activate
Windows:

venv\Scripts\activate
Install Dependencies:
pip install -r requirements.txt

Project Phases and Python Commands
Phase 1: Create AI Agent
python3 ai_agent.py
Phase 2: Setup Backend with FastAPI
python3 backend.py
Phase 3: Setup Frontend with Streamlit
python3 frontend.py
IMPORTANT
Make sure backend python script is running in a separate terminal
