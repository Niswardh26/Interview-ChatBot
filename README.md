# 💬 Interview ChatBot – AI HR Interview Simulator

An AI-powered Interview Chatbot that simulates a real HR interview experience using Large Language Models.

This application collects candidate details (name, experience, skills, role, company) and conducts an interactive HR-style interview.  
After completing the interview, the bot automatically analyzes answers and provides a score + feedback.

Built using Streamlit + LLM APIs.

---

## 🚀 Features

✅ Personal information form  
✅ HR-style AI interviewer  
✅ Real-time chat interface  
✅ Conversation memory  
✅ Streaming responses  
✅ Limits interview questions  
✅ Automatic feedback generation  
✅ Interview performance score (1–10)  
✅ Supports FREE models (Groq / Ollama)  
✅ Works locally & online  

---

## 🛠 Tech Stack

- Python
- Streamlit
- LLM APIs:
  - OpenAI (GPT models – Paid)
  - Groq (Free + Very Fast)
  - Ollama (Local + 100% Free)
- Git & GitHub

---

## 📦 Installation

### 1️⃣ Clone the repository

```bash
git clone https://github.com/Niswardh26/Interview-ChatBot.git
cd Interview-ChatBot
```

---

### 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

If requirements.txt not available:

```bash
pip install streamlit openai groq langchain-community
```

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

Open browser:

```
http://localhost:8501
```

---

## 🔑 API Setup

Choose ANY one option:

---

### ✅ Option 1 – OpenAI (Paid)

Create:

```
.streamlit/secrets.toml
```

Add:

```toml
OPENAI_API_KEY="your_key_here"
```

---

### ✅ Option 2 – Groq (FREE + Fastest)

Create:

```toml
GROQ_API_KEY="your_key_here"
```

Models example:

- llama-3.1-8b-instant
- mixtral-8x7b

---

### ✅ Option 3 – Ollama (BEST – 100% Free, Local)

Install Ollama:

👉 https://ollama.com

Then:

```bash
ollama pull llama3
```

No API key required.

---

## 🧠 How the Project Works

### Step-by-step flow:

1️⃣ User enters details (name, skills, experience)  
2️⃣ System prompt configures AI as HR interviewer  
3️⃣ Chat history stored using Streamlit session_state  
4️⃣ LLM generates questions and responses  
5️⃣ After fixed number of answers → interview ends  
6️⃣ Entire conversation analyzed  
7️⃣ AI gives feedback + score  

---

## 📁 Project Structure

```
Interview-ChatBot/
│
├── app.py
├── README.md
├── requirements.txt
└── .streamlit/
    └── secrets.toml
```

---

## 💡 Example Screens

You can add screenshots here later:

- Setup Form
- Chat Interface
- Feedback Screen

(Optional)

---

## 🔮 Future Improvements

- Voice-based interview
- Resume upload (PDF parsing)
- Save interview history
- Multi-round interviews
- Database integration
- Admin dashboard
- Authentication system

---

## 👨‍💻 Author

**Niswardh**

AI/ML Developer  
GitHub: https://github.com/Niswardh26

---

## ⭐ Support

If you like this project, please ⭐ the repository on GitHub.

It helps others discover it and supports development ❤️
