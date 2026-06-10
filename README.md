# TORAI
TORAI is an intelligent medical chatbot web application that allows users to upload medical images such as prescriptions, lab reports, or scans—and ask context-based questions. 



# 🩺 TORAI — Medical Chatbot for Image-Based Question Answering

TORAI is a smart medical chatbot that allows users to upload medical images (such as prescriptions, lab reports, or scan results), ask questions about them, and receive helpful, AI-generated responses. It combines OCR and LLMs to make medical documents more understandable to the average person.

<div align="center">
  <img src="https://img.shields.io/badge/FastAPI-async%20web%20framework-green" />
  <img src="https://img.shields.io/badge/OCR-Tesseract-blue" />
  <img src="https://img.shields.io/badge/LLM-Groq%20API-orange" />
  <img src="https://img.shields.io/badge/UI-TailwindCSS-purple" />
</div>

---

## 🧠 Features

- 📸 Upload medical images (PNG, JPG)
- 🔍 Extracts text using Tesseract OCR
- 💬 Accepts natural language questions about the document
- 🤖 Uses **LLMs** like `llama3-8b-8192` to answer queries
- 🎨 Clean UI with Tailwind CSS
- 🧾 Display of AI response in markdown format

---

## 📸 Demo

> Coming soon — or run locally to see it in action!

---

## ⚙️ Tech Stack

| Layer     | Technology               |
|-----------|--------------------------|
| Frontend  | HTML, TailwindCSS, JS    |
| Backend   | FastAPI (Python)         |
| OCR       | Tesseract                |
| AI Model  | Groq API (LLaMA 3)       |
| Templates | Jinja2                   |

---

## 🚀 Installation

### Prerequisites

- Python 3.8+
- [Tesseract OCR installed](https://tesseract-ocr.github.io/tessdoc/Installation.html)
- Groq API key

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/medical-bot.git
cd medical-bot
````

### 2. Create and activate a virtual environment

```bash
python -m venv .venv
source .venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

> If you don’t have a `requirements.txt`, install manually:

```bash
pip install fastapi uvicorn jinja2 python-multipart pytesseract pillow python-dotenv requests
```

### 4. Set up `.env`

Create a file named `.env` in the root:

```env
GROQ_API_KEY=your-groq-api-key
LLM_MODEL=llama3-8b-8192
```

### 5. Run the app

```bash
uvicorn app:app --reload
```

Then open: [http://127.0.0.1:8000](http://127.0.0.1:8000)

---

## 📂 Project Structure

```
medical-bot/
├── app.py
├── main.py
├── templates/
│   └── index.html
├── static/
├── .env
└── README.md
```

---

## 🤔 Future Improvements

* 📄 PDF and multi-image support
* 🗂️ History of previous responses
* 🌍 Multilingual OCR
* 📱 Mobile-friendly responsive UI

---

## 🛡 Disclaimer

This tool is for **educational and experimental purposes only**. It is not a substitute for professional medical advice, diagnosis, or treatment.

---

## 🧑‍💻 Author

**Rohan Kumar**


---

## ⭐️ Give it a Star!

If you like this project, consider starring the repo ⭐ to support it!

