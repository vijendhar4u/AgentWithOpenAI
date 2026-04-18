# 🚀 Python Setup using `uv` + Virtual Environment + API Keys

## 📌 Project Initialization

```bash
uv init
```

---

## 🧩 Step 1: Check Python Versions

```bash
uv python list
```

---

## 🧩 Step 2: Create Virtual Environment

```bash
uv venv env --python cpython-3.14.3-windows-x86_64-none
```

---

## 🧩 Step 3: Activate Environment

```bash
env\Scripts\activate
```

---

## 🧩 Step 4: Update `.gitignore`

```
# Virtual environments
.venv
env/
venv/
.env
```

---

## 🧩 Step 5: Install Dependencies

```bash
uv pip install -r requirements.txt
```

---

## 🧩 Step 6: Add API Keys

Create a `.env` file:

```
OPENAI_API_KEY=""
GEMINI_API_KEY=""
GROQ_API_KEY=""
OPENROUTER_API_KEY=""
KIMI_API_KEY=""
```

---

## 🧩 Step 7: Load Environment Variables in Python

```python
from dotenv import load_dotenv
import os

load_dotenv()

print(os.getenv("OPENAI_API_KEY"))
```

---

## 📁 Project Structure

```
project/
│
├── env/
├── .env
├── .gitignore
├── requirements.txt
└── main.py
```

---

## ✅ Setup Complete

Now you're ready to:

* Use OpenAI APIs
* Work with multiple AI providers
* Build Python apps

---

## ⭐ Tips

* Never commit `.env` file
* Always use virtual environments
* Use `uv` for faster installs over pip

---
get test api keys free and paid from below  :
Gemini api keys
grpq api key 
openrouter 
kimi2 


Salesforce integration with Python APIs ,  Real ChatGPT clone (UI + backend)
📊 AI-powered trading analyzer (based on your earlier questions)
⚙️ Salesforce + AI integration

✅ Full project folder structure
✅ Ready GitHub repo
✅ Complete Salesforce + LWC integration code
✅ Trading strategy AI (Supertrend-based)

Just tell me what you want to start with:
👉 "ChatGPT clone"
👉 "Salesforce AI"
👉 "Trading bot"
