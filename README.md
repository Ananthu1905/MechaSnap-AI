# 🔧 MechSnap AI

### AI-Powered Mechanical Engineering Study Assistant

MechSnap AI is an AI-powered study assistant designed for mechanical engineering students.

It allows students to upload a photo of a mechanical engineering question, diagram, drawing, graph, or technical notes and receive a clear AI-generated explanation.

The application also supports follow-up questions and allows the generated explanation to be shared through email.

---

## 🚀 Features

- 📸 Upload mechanical engineering images
- 🤖 AI-powered image analysis using Google Gemini
- 📚 Simple explanations of engineering concepts
- 🧮 Step-by-step solutions for numerical problems
- 📐 Engineering drawing explanation
- 💬 Follow-up questions and conversation
- 📧 Email explanations directly from the application
- 🔄 Automatic Gemini model fallback
- ⚡ Automatic retry for temporary API errors
- 🔐 Secure API credentials using Streamlit secrets

---

## 🛠️ Technologies Used

- Python
- Streamlit
- Google Gemini API
- Gmail SMTP
- GitHub

---

## 📂 Project Structure

```text
Mechasnap/
│
├── app.py
├── prompts.py
├── requirements.txt
├── .gitignore
├── secrets.toml.example
│
└── .streamlit/
    └── secrets.toml