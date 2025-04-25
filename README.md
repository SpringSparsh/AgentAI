# AgentAI
The Web Research AI Agent is designed to act as an intelligent digital research assistant that automates online research tasks. Its primary function is to take a user-provided query, search the internet, extract relevant and trustworthy information from various sources, and generate a well-structured and easy-to-understand research report.

# 🌐 Web Research AI Agent 🤖

A fully automated AI-powered agent that searches the web, extracts relevant content, analyzes it, and summarizes research findings — all based on a user-defined topic. Built using **CrewAI**, **LangChain**, **Gemini Pro**, and **Serper.dev**, this project acts as your intelligent digital research assistant.

---

## 🚀 Features

- 🔍 **User-Prompted Search**: Automatically triggers web search based on user input.
- 🧠 **LLM-Driven Agents**: Leverages multi-role agents (e.g., researcher, writer) using CrewAI.
- 🌐 **Live Web Data**: Fetches real-time data using Serper.dev.
- ✨ **Summarization**: Synthesizes extracted content into a concise and structured report.
- 📄 **Markdown Output**: Saves results to `web_research_summary.md` for easy sharing or publishing.

---

## 🧠 Tech Stack

| Tool/Library   | Purpose                            |
|----------------|------------------------------------|
| Python         | Main programming language          |
| CrewAI         | Multi-agent orchestration          |
| LangChain      | LLM chaining and prompt templating |
| Gemini Pro     | Language model for reasoning       |
| Serper.dev     | Google Search API (via LangChain)  |
| dotenv         | Environment variable management    |

---

## 📦 Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/web-research-ai-agent.git
cd web-research-ai-agent

Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Create a .env file in the root directory with the following:

env
Copy
Edit
SERPER_API_KEY=your_serper_api_key
GOOGLE_API_KEY=your_gemini_api_key
🧪 How to Use
bash
Copy
Edit
python web_research_agent.py
Enter the topic when prompted (e.g., AI in Healthcare)

The agent will search the web, extract insights, and generate a web_research_summary.md file.
