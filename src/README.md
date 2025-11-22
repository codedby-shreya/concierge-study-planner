Concierge Agent

Subtitle: AI-powered study planner that turns subjects, deadlines, and available hours into a clear, personalized study timetable.
Built as part of the Google 5-Day AI Agents Intensive Capstone Project.

🎯 Project Overview

Students today juggle multiple subjects, assignments, exams, and personal tasks — often without a structured plan. This leads to stress, missed deadlines, and poor study balance.

Concierge Agent solves this by:

Accepting student inputs (subjects, available hours, deadlines, priority tasks)

Understanding constraints and preferences

Generating a structured, optimized study timetable

Allowing easy updates when schedules or priorities change

It is suitable for any student — college, school, competitive exams, or self-learners.

💡 Why an Agent?

Traditional scripts or static planners cannot:

Adapt to changing deadlines

Understand varied inputs or schedules

Reason about priority vs workload

Generate dynamic plans instantly

Agents can, because they combine:

Reasoning via LLM

Multi-agent orchestration (primary agent + helper agents)

Tools for parsing, timetable generation, and optional OCR

Memory & Sessions (InMemory service + Memory Bank)

Structured, dynamic planning abilities

Using Gemini/LLM, the agent follows a multi-step workflow:

Parse student inputs

Extract subjects, deadlines, and constraints

Reason about workload and priorities

Generate a personalized timetable

Return a clean, formatted plan

This multi-step reasoning makes it far more effective than a static script or planner.

🧱 Architecture
Components

Input Handler

Accepts subjects, available hours, deadlines, priorities, and optional uploaded schedule.

OCR (Optional)

Extracts text from PDF/image schedules if uploaded.

Parser

Identifies subjects, hours, deadlines, and priorities from inputs.

Reasoning Agent (Gemini/LLM)

Allocates hours per subject

Ensures balance between tasks and deadlines

Handles re-planning dynamically if availability changes

Multi-Agent System

Primary LLM agent coordinates with parallel helper agents:

Subject scheduler

Deadline tracker

Priority handler

Memory & Sessions

InMemory session service for temporary session data

Memory Bank for long-term storage (previous schedules, preferences)

Output Generator

Returns a clear daily/weekly timetable

Notebook Demo

Static chat-style interface in Kaggle

Shows example inputs → reasoning → timetable output

Architecture diagram can be added later in /docs.

🚀 Features

📑 Upload schedule as text, image, or PDF

🧠 LLM-powered reasoning for exams, deadlines, and priorities

🕒 Automatic distribution of study hours

📘 Customizable output: daily or weekly timetable

🔁 Dynamic re-planning when inputs change

🔍 Optional OCR support for handwritten or printed schedules

🤖 Multi-agent orchestration for subjects, deadlines, and priorities

💾 Memory & session tracking for long-term context and smarter planning

🧪 Demo (Kaggle Notebook)

📎 Notebook: notebooks/concierge_agent_demo.ipynb

The Kaggle notebook shows:

Example student inputs

Step-by-step agent reasoning (primary + helper agents)

Generated study timetable in tables

Optional OCR demo

Complete static demonstration of the workflow

All outputs are static examples — no live user input required.

🗂 Folder Structure
concierge-agent/
│
├── notebooks/
│   └── concierge_agent_demo.ipynb
├── docs/
│   ├── architecture_diagram.png
│   └── sample_output.png
├── README.md
└── LICENSE (optional)

🛠️ Tools & Technologies

Python (Kaggle Notebook)

LLM / Gemini API for reasoning and timetable generation

Multi-Agent system (primary + helper agents)

Memory & Session management (InMemory + Memory Bank)

Optional OCR (Gemini Vision)

GitHub for version control and documentation

Markdown & diagrams for architecture explanation

✅ No API keys or passwords are included in the repository.

⚙️ How to Run

Clone the repository:

git clone https://github.com/codeby-shreya/concierge-agent.git
cd concierge-agent


Open notebooks/concierge_agent_demo.ipynb in Kaggle or Jupyter Notebook.

Follow the Markdown instructions in the notebook.

Example inputs are already provided for static demonstration.

No API keys or passwords required.

🔮 Future Enhancements

Real-time schedule adjustment and progress tracking

Calendar export to Google Calendar

Pomodoro timer integration

Personalized learning insights based on study patterns

Web or mobile interface for daily use

This README now fully matches everything we implemented yesterday, including:

Multi-agent system

LLM reasoning

Memory & sessions

Tools and OCR

Static chat-style Kaggle notebook demo

Made with ❤️ for the Google AI Agents Intensive Capstone Project.
