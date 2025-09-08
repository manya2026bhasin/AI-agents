# 🤖 AI Agents

A collection of **LangGraph + LangChain powered AI agents** built for different tasks.
Each agent lives in its own folder with a README, requirements, and example usage.

## 📂 Repository Structure

```
ai-agents/
│
├── debate-agent/       # Multi-agent debate system
│   ├── README.md
│   ├── requirements.txt
│   ├── main.py
│   └── debate_agent.ipynb
│
├── travel-agent/       # Multi-agent travel planner (WIP)
│   ├── README.md
│   ├── requirements.txt
│   ├── main.py
│   └── travel_agent.ipynb
│
├── .gitignore          # Ignore venv, env files, cache
└── README.md           # You are here
```

---

## 🚀 Agents Available

### 🗣️ Debate Agent

* **Description:** Multi-agent debate system
* **How it works:**

  * Supporter argues *for* a topic
  * Opponent argues *against*
  * Judge summarizes the debate
* **Tech:** LangGraph, Groq LLMs

➡️ [See details here](./debate-agent/README.md)

---

### 🌍 Travel Agent (Coming Soon)

* **Description:** Multi-agent travel planner
* **How it works:**

  * Preference agent extracts trip details (destination, budget, interests)
  * Itinerary agent proposes a plan
  * Budget checker validates costs
  * Judge finalizes travel plan

➡️ [See details here](./travel-agent/README.md)

---

## ⚙️ Setup

1. Clone the repo:

```bash
git clone https://github.com/<your-username>/ai-agents.git
cd ai-agents
```

2. Create a virtual environment:

```bash
python -m venv .venv
source .venv/bin/activate   # On Mac/Linux
.venv\Scripts\activate      # On Windows
```

3. Install dependencies (for a specific agent):

```bash
cd debate-agent
pip install -r requirements.txt
```

4. Add your `.env` file:

```
GROQ_API_KEY=your_api_key_here
```

---

## 🛡️ Notes

* API keys are never stored in the repo (see `.gitignore`).
* Each agent is **modular** — you can run them independently.

---

## 📌 Roadmap

* ✅ Debate Agent
* 🔄 Travel Agent
* 🧑‍🍳 Recipe Recommender Agent
* 📚 Study Buddy Agent

---

## 👨‍💻 Author

Made with ❤️ by **Manya Bhasin**

---
