# Transparency Label Study (Flask + Prolific)

This study is built with Flask and deployed with Gunicorn. It supports both local testing and production-ready deployment on a server.

---

## 🔧 Local Development (on Mac/Linux)

1. **Clone the repository** (or copy the source files).

2. **Create a virtual environment**:
```bash
python3 -m venv venv
source venv/bin/activate
```

3. **Install dependencies**:
```bash
pip install -r requirements.txt
```

4. **Run the app with Flask**:
```bash
flask --app app run --debug
```
