# 📚 AI Study Planner — Concierge Agent

An AI-powered study planning agent that helps students turn their tasks, subjects, deadlines, and available hours into a *clear, personalized study timetable*.  
Built as part of the *Google 5-Day AI Agents Intensive Capstone Project*.

---

## 🎯 Project Overview

Students today juggle multiple subjects, exams, assignments, coaching classes, and personal tasks — often without a structured plan. This leads to stress, missed deadlines, and poor study balance.

The *AI Study Planner Agent* solves this by:

- Taking student inputs (text or uploaded schedule)
- Understanding priorities and available hours
- Generating a structured, optimized study timetable
- Allowing easy updates when tasks or deadlines change

It is designed to help *any student* — school, college, competitive exams, or self-learners.

---

## 💡 Why an Agent?

Traditional scripts or static planners cannot:

- Adapt to changing deadlines  
- Understand natural language schedules  
- Reason about priority vs workload  
- Generate dynamic plans on demand  

Agents *can*, because they combine:

- Reasoning  
- Tools (OCR, parser, generator)  
- Memory  
- Structured planning abilities  

Using Gemini, the agent can follow a multi-step workflow:

1. Parse student inputs  
2. Extract subjects, deadlines, and constraints  
3. Reason about workload  
4. Generate timetable  
5. Return a clean, formatted plan  

This multi-step reasoning makes it far more effective than a simple app.

---

## 🧱 Architecture

### *Components*
- *1. Input Handler*
  - Accepts text, uploaded PDF, or image schedule.
- *2. OCR (if file uploaded)*
  - Extracts text from images/PDFs using Gemini.
- *3. Parser*
  - Identifies: Subjects, hours, deadlines, preferences.
- *4. Reasoning Agent (Gemini)*
  - Plans hours for each subject.
  - Ensures balance and deadline management.
- *5. Output Generator*
  - Returns clear day-wise or week-wise timetable.
- *6. Notebook Demo*
  - Interactive example on Kaggle.

Architecture diagram (to be added later in docs folder).

---

## 🚀 Features

- 📑 *Upload schedule* as text, image, or PDF  
- 🧠 *AI-powered understanding* of exams, deadlines & priorities  
- 🕒 *Automatic distribution* of study hours  
- 📘 *Customizable output* (daily/weekly plan)  
- 🔁 *Re-planning* when user updates tasks  
- 🔍 *OCR support* for handwritten or printed study schedules  
- 🤖 *Gemini-powered reasoning* for accuracy  

---

## 🧪 Demo (Kaggle Notebook)

📎 Link will be added here after notebook is completed.

The Kaggle notebook will show:

- Input examples
- Agent step-by-step reasoning
- Study plan outputs
- OCR demo (optional)
- Final integrated pipeline

---

## 🗂 Folder Structure
---

## 🛠️ Tools & Technologies

- *Python*
- *Gemini API (secure — NO keys in repo)*
- *Google AI Agent Framework*
- *OCR (Gemini Vision)*
- *Kaggle Notebook*
- *GitHub for version control*

No API keys or passwords are included to maintain security.

---

## ⚙️ How to Run

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/concierge-study-planner.git
cd concierge-study-planner

# 📚 AI Study Planner — Concierge Agent
An AI-powered study planning agent...
...
*Made with ❤️ for the Google AI Agents Intensive Capstone*
