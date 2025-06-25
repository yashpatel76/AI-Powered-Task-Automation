
# AI-Powered Automation Workflows using n8n

This repository showcases two practical, AI-driven automation workflows built using the powerful no-code platform **n8n**. These projects demonstrate how to integrate APIs, leverage Large Language Models (LLMs), and orchestrate real-time decision-making through smart assistants.

---

## 🚍 Commute Assistant – Ahmedabad BRTS Recommendation System

### 📌 Objective
Automate the process of suggesting the most optimal Ahmedabad BRTS bus route each morning based on your schedule, live weather conditions, and available routes.

### 🔧 Features
- Pulls event time from **Google Calendar** to determine when the user needs to leave.
- Fetches **real-time weather** using the **OpenWeather API**.
- Reads pre-saved **BRTS bus route data** from **Google Sheets** (includes distance, frequency, service type).
- Sends a **context-aware, HTML-formatted email** to the user with the recommended bus route.
- Uses an **OpenAI Chat Model** (LLM) for natural language response generation.

### 🧠 Tech Stack & Integrations
- **n8n** (No-code workflow builder)
- **OpenWeatherMap API** (weather data)
- **Google Calendar API** (calendar events)
- **Google Sheets** (route data)
- **OpenAI API** (LLM for reasoning and response)
- **Gmail** (email delivery)

### 🌐 Workflow Highlights
- Triggered every morning using a **Schedule node**.
- A **ChatGPT Agent** processes the inputs and uses **Simple Memory** for context.
- The AI responds with a bus recommendation that considers weather, timing, and available routes.

---

## 📈 Stock Price Analysis Agent – AI Trading Insight Bot

### 📌 Objective
Automate the process of analyzing stock performance using charts, news sentiment, and technical indicators like MACD, and generate insights using an AI agent.

### 🔧 Features
- Accepts a company name or stock symbol as input.
- Fetches real-time **MACD chart images** using **Chart-IMG API**.
- Extracts relevant **stock-related news** via **Tavily API**.
- Uses an **OpenAI LLM** to analyze both the chart and sentiment.
- Outputs a human-like insight via a chat-based interaction.

### 🧠 Tech Stack & Integrations
- **n8n**
- **Chart-IMG API** (technical chart rendering)
- **Tavily API** (news & sentiment)
- **OpenAI Chat Model** (LLM)

### 🌐 Workflow Highlights
- Accepts a company name as prompt input.
- Generates a technical chart image with MACD overlay.
- Finds and summarizes relevant recent news.
- AI Agent interprets both sources and generates a natural language explanation (e.g., "Tesla shows bearish MACD trend with negative news sentiment").

---

## 🔍 LLM Usage in Both Projects
In both workflows, **OpenAI’s Large Language Model** (LLM) is used to:
- Perform reasoning over multi-source data
- Generate personalized, natural language responses
- Maintain memory context with **Simple Memory** plugin

---

## 📬 Output Examples
- **Commute Assistant:** Sends an HTML email with the optimal BRTS route, travel time, weather, and event timing.
- **Stock Agent:** Outputs a chat-style response like "AAPL is currently showing bullish MACD with positive market sentiment."

---

## 🤖 Key Learnings & AI Concepts Applied
- Contextual task automation
- API integration using REST
- Prompt engineering for LLMs
- NLP-based insights and summary generation
- Real-world AI application via n8n orchestration

---

## 👨‍💻 Author
**Yash Patel** 

[LinkedIn/yashpatel76]

[GitHub/yashpatel76]
