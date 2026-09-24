# 🤖 GenAI Chatbot - Flask + OpenAI + Vercel

A simple beginner-friendly GenAI chatbot built with:

- Python
- Flask
- HTML
- CSS
- OpenAI API
- Vercel

## Run locally

### 1. Install dependencies

```bash
pip install -r requirements.txt
```

### 2. Create `.env`

Copy `.env.example` to `.env` and add your OpenAI API key:

```text
OPENAI_API_KEY=your_api_key_here
```

Never upload `.env` to GitHub.

### 3. Run

```bash
python app.py
```

Open:

http://127.0.0.1:5000

## Deploy to Vercel

1. Upload this project to GitHub.
2. Import the GitHub repository into Vercel.
3. Add an Environment Variable:

```text
OPENAI_API_KEY = your_api_key
```

4. Deploy.

## Project structure

```text
genai-chatbot-vercel/
├── app.py
├── requirements.txt
├── vercel.json
├── .env.example
├── .gitignore
├── README.md
├── templates/
│   └── index.html
└── static/
    └── style.css
```
