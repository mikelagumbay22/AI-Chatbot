# AI Chatbot

A simple chatbot powered by Claude (Anthropic API) with a Streamlit UI.

## Setup

```bash
python -m venv venv
source venv/Scripts/activate   # Git Bash on Windows
pip install -r requirements.txt
cp .env.example .env           # then add your Anthropic API key
```

## Run

```bash
source venv/Scripts/activate
streamlit run app.py
```

Open http://localhost:8501 in your browser.
