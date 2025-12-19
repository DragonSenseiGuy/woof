# Woof YSWS
Woof YSWS is a YSWS where you code a dog themed website for 5 hours and get a dog plushie!

[![Status: Work in Progress](https://img.shields.io/badge/status-work%20in%20progress-yellow)](#)

> **Note:** This project is currently a work in progress. Features and documentation may change.
[woof-mu.vercel.app](https://woof-mu.vercel.app)

## Installation
First make a virtual environment:
```commandline
python -m venv .venv
```

then activate it
on macOS/Linux:
```commandline
source .venv/bin/activate
```

on windows:
```commandline
.\venv\Scripts\activate.bat
```

Install dependencies:
```commandline
pip install -r requirements.txt
```

run the server:

for dev:
```commandline
flask --app main run --debug
```

for production:
you need to use gunicorn, which I will set up later
