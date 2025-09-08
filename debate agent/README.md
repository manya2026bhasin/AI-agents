# 🗣️ Debate Agent

The **Debate Agent** is a multi-agent system built using **LangGraph** and **LangChain**.
It simulates a structured debate on any given topic:

* 🟢 **Supporter Agent** → argues *for* the topic
* 🔴 **Opponent Agent** → argues *against* the topic
* ⚖️ **Judge Agent** → listens to both sides and provides a **neutral summary**

This project demonstrates how multiple LLM agents can coordinate and exchange information within a graph.

---

## 🚀 How It Works

1. The user provides a debate topic (e.g., *“Should mobile phones be allowed in schools?”*).
2. The **Supporter Agent** generates arguments in favor.
3. The **Opponent Agent** generates counter-arguments.
4. The **Judge Agent** summarizes the debate in a structured manner.

---

## 📂 Files

* `main.py` → Python script to run the debate agent
* `debate_agent.ipynb` → Notebook version with step-by-step explanation
* `requirements.txt` → Dependencies
* `.env` → Store your API keys here (not included in repo, ignored via `.gitignore`)

---

## ⚙️ Setup

1. Clone the repo and go to the debate-agent folder:

```bash
git clone https://github.com/<your-username>/ai-agents.git
cd ai-agents/debate-agent
```

2. Create and activate a virtual environment:

```bash
python -m venv .venv
.venv\Scripts\activate      # Windows
source .venv/bin/activate   # Mac/Linux
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Create a `.env` file and add your Groq API key:

```
GROQ_API_KEY=your_api_key_here
```

---

## ▶️ Usage

Run the script:

```bash
python main.py
```

Or use the notebook:

```bash
jupyter notebook debate_agent.ipynb
```

Example:

```
Input: "Debate on use of mobile phones"
Output: 
Supporter: [LLM-generated arguments in favor]  
Opponent: [LLM-generated arguments against]  
Judge: [Neutral summary of the debate]  
```

---

## 🔮 Future Improvements

* Add **multiple rounds** of debate
* Let the judge **declare a winner** instead of just summarizing
* Improve formatting for cleaner outputs

---

## 👨‍💻 Author

Made with ❤️ by **Manya Bhasin**

---
