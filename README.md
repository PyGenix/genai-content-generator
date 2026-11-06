# GenAI Content Generator

Python FastAPI backend that generates short-form marketing content with an LLM.

Useful for product blurbs, email drafts, and campaign copy while keeping the API surface small and easy to demo.

## Stack

- **Backend:** Python 3.11+, FastAPI, Uvicorn
- **AI:** OpenAI (`gpt-4o-mini`)
- **Frontend (optional demo UI):** React + Vite

## Features

- Prompted content generation endpoint
- Brand-style drafting for common marketing formats
- `.env`-based key management (example file included)

## Quick start

```bash
cd backend
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
cp .env.example .env   # set OPENAI_API_KEY
uvicorn main:app --reload --port 8000
```

API docs: http://localhost:8000/docs

```bash
cd frontend
npm install
npm run dev
```

## Author

Pooja Sharma — [Pooja101117](https://github.com/Pooja101117)
