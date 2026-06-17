# Hi, I'm Mehdi Reza 👋

**Aspiring AI Engineer** · Mumbai, India  
BMS graduate. Self-taught. Learning by building.

I didn't start with a CS degree or a bootcamp. I started with zero Python knowledge and a decision to figure it out by making real things. I'm currently in a deliberate phase: shipping small Python projects consistently to build strong fundamentals before moving to complex agent systems.

Every repo here is something I built myself and understood before pushing it.

---

## 🗂 Projects on GitHub

### 🤖 Quil — Personal AI Butler
> *An AI agent that manages my email, calendar, and finances through natural conversation.*

Quil is my most complete project. A personal AI agent built on **n8n (self-hosted)**, powered by **Groq + LLaMA 3.3 70B**, and connected to real Google services. It runs every day.

- 📧 Drafts and sends emails via Gmail API with a confirmation step before sending
- 📅 Creates and reads Google Calendar events through natural language
- 💸 Logs expenses to Google Sheets — manually or auto-parsed from HDFC bank alert emails (custom regex parser)
- 📸 Reads GPay/PhonePe screenshots via Gemini 1.5 Flash and logs the transaction automatically
- 🌅 Sends a morning briefing with emails, events, and expenses

`n8n` · `Groq API` · `LLaMA 3.3 70B` · `Gemini 1.5 Flash` · `Gmail API` · `Google Calendar API` · `Google Sheets API` · `Regex`

---

### 🔍 Research Analyst Agent
> *Give it a topic. It searches the web, analyzes the results, and saves a structured report.*

A CLI tool that chains two APIs: **Tavily** for live web search and **Groq (LLaMA 3.3 70B)** for analysis and summarization. Output is saved as a `.txt` report file.

First project where I combined web search with an LLM — understanding how to pass search results as context to a language model was the core learning.

`Python` · `Groq API` · `Tavily API` · `LLaMA 3.3 70B` · `python-dotenv`

---

### 👤 GitHub User Finder
> *Enter a GitHub username. Get their profile info back instantly.*

A Python CLI tool that hits the GitHub REST API and returns name, bio, public repos, and followers — with proper handling for missing fields and invalid usernames.

Built to solidify API fundamentals: HTTP requests, JSON parsing, error handling, and graceful failure.

`Python` · `GitHub REST API` · `requests`

---

## 🔨 Currently Building — Python Foundation Series

I'm deliberately building ~20 small Python projects this month before moving to larger agent systems. The goal is to own the fundamentals, not borrow them.

Projects cover: APIs, data handling, file processing, automation, web scraping, CLI tools, and basic LLM integrations. Uploading consistently — check back soon.

---

## 🧰 Tech Stack

**AI & LLMs**  
`Groq API` · `LLaMA 3.3 70B` · `Gemini 1.5 Flash` · `Prompt Engineering`

**Automation**  
`n8n (self-hosted)` · `Playwright`

**APIs & Integrations**  
`GitHub REST API` · `Tavily API` · `Gmail API` · `Google Calendar API` · `Google Sheets API`

**Programming**  
`Python` · `JSON` · `REST APIs` · `Error Handling` · `Regex`

**Data & Analytics**  
`SQL` · `Excel` · `Power BI (learning)`

**Tools**  
`Git` · `GitHub` · `VS Code`

---

## 📚 Roadmap

```
Python Fundamentals          ✅
JSON & APIs                  ✅
LLM API Integration          ✅  (Groq, Gemini)
n8n Workflow Architecture    ✅
Google API Integration       ✅
Python Foundation Projects   🔄  (~20 projects, in progress)
OOP & Software Design        ⬜  up next
AI Agents in Python          ⬜
RAG & Vector Databases       ⬜
Multi-Agent Systems          ⬜
Production AI Systems        ⬜
```

---

## 🎯 2026 Goals

- Complete the Python foundation project series
- Build and ship 5–6 serious AI engineering projects
- Master OOP and clean code principles
- Build a Multi-Agent Research Assistant and RAG Document Q&A system
- Launch a portfolio website
- Land an AI Engineering role

---

## 💡 Philosophy

*"Learn by building. Ship small projects. Improve through repetition."*

I don't move forward until I understand what I just built. That slows things down short-term and speeds everything up long-term.

---

*Currently in the foundation phase — uploading consistently. Follow along if you're on a similar path.*
