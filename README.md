# Python Web Server Demo
A simple python web server demo I made while learning uvicorn, FastAPI, and python.

# Usage
Create a virtual environment:
```bash
python -m venv .venv
source .venv/bin/activate
```

Install requirements:
```bash
pip install -r requirements.txt
```

Start the webserver:
```bash
uvicorn main:app --reload
```

Access http://localhost:8000

When finished run the following command to exit the virtual environment for python:
```bash
deactivate
```
