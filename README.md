# Flask Cloud App

A simple Python Flask web application configured for deployment on cloud Platform as a Service (PaaS) platforms (Render) with automated continuous deployment.

## Features
- Lightweight Python Flask web application
- Production-ready WSGI configuration with Gunicorn
- Automated Continuous Deployment (CD) via GitHub integration

## Tech Stack
- **Language**: Python 3.11+
- **Framework**: Flask
- **WSGI Server**: Gunicorn
- **PaaS Platform**: Render

## Local Setup & Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Dhruvi-tech/flask-cloud-app.git
   cd flask-cloud-app
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application:**
   ```bash
   python app.py
   ```

4. **Access in browser:**
   Open [http://127.0.0.1:5000](http://127.0.0.1:5000)

## Deployment on Render PaaS
- **Build Command**: `pip install -r requirements.txt`
- **Start Command**: `gunicorn app:app`
