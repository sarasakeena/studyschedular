# 📅 Smart Study Scheduler

**Smart Study Scheduler** is a productivity app that helps students and professionals break down their tasks into daily plans based on deadlines, priority, and available time per day. It uses 🧠 intelligent logic to distribute work and gives you a motivational quote for each day.

Built with:
- 🧪 **FastAPI** – for backend scheduling logic
- 🎨 **Streamlit** – for interactive frontend UI
- ⚡ **FastMCP** – custom task distribution logic
- 💬 Motivational quotes to boost morale

---

## 🚀 Features

- ✅ Add unlimited tasks with:
  - Hours + Minutes estimate
  - Deadline
  - Priority (High / Medium / Low)
- 📆 Smart scheduler splits tasks across days
- 🔥 Motivational quotes per day
- 📊 Weekly priority overview in sidebar
- 👁️ Automatically displays full schedule

---

## 🛠️ Tech Stack

| Layer       | Tech          |
|-------------|---------------|
| Backend     | FastAPI       |
| Frontend    | Streamlit     |
| Logic Core  | Custom FastMCP scheduler |
| Language    | Python 3.12+  |

---

## 📦 Installation

1. **Clone the repo**:

```bash
git clone https://github.com/yourusername/smart-study-scheduler.git
cd smart-study-scheduler
```
2.Install dependencies:
pip install -r requirements.txt
3.Run FastAPI backend:
uvicorn main:app --reload
Run Streamlit frontend (in a new terminal):
streamlit run app.py
