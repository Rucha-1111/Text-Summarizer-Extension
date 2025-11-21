# 🧠✨ Text Summarizer Extension

Tired of reading long boring paragraphs?
Meet **Text Summarizer**, your mini AI assistant that turns TL;DR nightmares into bite-sized brilliance 🍿.

A Chrome Extension powered by a **Flask backend + AI summarizer model** — it lives in your browser, ready to summarize whatever you highlight!

---   

## 🚀 Features

✅ Summarizes any selected text (50+ words) instantly.
✅ Works right inside your Chrome browser.
✅ Copy summaries in one click 📋.
✅ AI-powered and locally hosted for privacy 🔒.
✅ Sleek pop-up interface — minimalist, clean, and fast ⚡.

---

## 🧩 How It Works

1. You select some text on a webpage (something long and boring 🥱).
2. A cute little popup appears with a “Summarize” button.
3. Click it — and voilà 🎉 — your AI buddy gives you a neat, short summary!

---

## 🛠️ Setup Instructions

### 1️⃣ Clone or Download This Repo

```bash
git clone https://github.com/Rucha-1111/Text-Summarizer-Extension.git
cd Text-Summarizer-Extension
```

### 2️⃣ Install Backend Dependencies

Make sure you have Python 3 installed, then run:

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Flask Backend

```bash
python app.py
```

You should see something like: Running on <http://127.0.0.1:5000>

Keep this terminal window open! It’s your extension’s brain 🧠.

### 4️⃣ Load the Extension in Chrome

1. Open Chrome and go to 👉 `chrome://extensions/`
2. Turn on **Developer Mode** (top right corner).
3. Click **Load unpacked**.
4. Select the folder where your project files are.

**BOOM 💥 — your extension is now live!**

---

## 🧠 How to Use It

1. Go to any webpage.
2. Select a long paragraph (50+ words).
3. A popup will appear. Click **Summarize**.
4. Wait a few seconds ⏳.
5. Copy or close the summary.

**Easy peasy lemon squeezy 🍋.**

---

## 🐞 Common Issues

❌ **"Failed to summarize"**
Make sure your Flask app (`python app.py`) is still running.

❌ **Nothing happens**
Ensure Developer Mode is ON and the extension is loaded correctly.

❌ **“CORS” or network errors**
Your backend must be running on `http://127.0.0.1:5000`.

---

## 🧑‍💻 Tech Stack

- **Frontend:** HTML, CSS, JavaScript (Chrome Extension API)
- **Backend:** Flask (Python)
- **AI Model:** Hugging Face Transformers 🧬

---

## 💬 Fun Fact

This extension doesn’t just summarize text…
It summarizes your entire will to read long essays 😆.

---

## 🌟 Contribute / Star ⭐

If this made your life easier,
give it a ⭐ on GitHub — it helps more people discover it!
