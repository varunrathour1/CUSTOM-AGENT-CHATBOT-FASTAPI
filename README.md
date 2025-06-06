# 🚀 Project Setup Guide

Welcome to the official setup guide for this project! This walkthrough will help you set up your development environment using your preferred Python environment manager (Pipenv, pip+venv, or Conda), and show how to run the different parts of the application.

---

## 📚 Table of Contents

- [🛠 Setting Up a Python Virtual Environment](#🛠-setting-up-a-python-virtual-environment)
  - [📦 Using Pipenv](#📦-using-pipenv)
  - [🐍 Using pip and venv](#🐍-using-pip-and-venv)
  - [🍃 Using Conda](#🍃-using-conda)
- [🏃 Running the Application](#🏃-running-the-application)
- [⚠️ Important Notes](#⚠️-important-notes)

---

## 🛠 Setting Up a Python Virtual Environment

Choose one of the following methods based on your preference:

<details>
<summary><strong>📦 Using Pipenv</strong></summary>

1. Install Pipenv:
 
Install project dependencies:




pipenv install
Activate the environment:




pipenv shell
 <details> <summary><strong>🐍 Using pip and venv</strong></summary>
Create a virtual environment:




python -m venv venv
Activate the environment:

macOS/Linux:




source venv/bin/activate
Windows:




venv\Scripts\activate
Install dependencies:




pip install -r requirements.txt
 <details> <summary><strong>🍃 Using Conda</strong></summary>
Create an environment:




conda create --name myenv python=3.11
Activate the environment:




conda activate myenv
Install dependencies:




pip install -r requirements.txt

🏃 Running the Application
The project is divided into three phases. Run them individually in the terminal:

📌 Phase 1: Create AI Agent



python ai_agent.py
⚙️ Phase 2: Setup Backend with FastAPI



python backend.py
💻 Phase 3: Setup Frontend with Streamlit



python frontend.py
⚠️ Important Notes
✅ Ensure the backend (backend.py) is running in a separate terminal before launching the frontend.

🧠 Tip
To keep everything tidy and manageable, consider using tmux or multiple terminal tabs/windows to run each phase.

Made with ❤️ by [YourName or GitHub handle]
