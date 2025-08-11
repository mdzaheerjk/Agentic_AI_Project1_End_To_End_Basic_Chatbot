# 🤖 Agentic AI Project 1: End-to-End Basic Chatbot

![Python](https://img.shields.io/badge/Python-3.13%2B-brightgreen)
![License](https://img.shields.io/badge/License-GPL--3.0-orange)

A modern, agentic end-to-end basic chatbot platform built using modular agent design and a graph-based orchestration approach. This project demonstrates how to build, extend, and deploy a simple conversational AI assistant using clean Python, with a focus on agentic workflows.

> 📁 **Repository:** `Agentic_AI_Project1_End_To_End_Basic_Chatbot`

---

## 🚀 Project Highlights

- 🧠 **Agentic AI Chatbot:** Modular chatbot built with agent and node abstraction.
- 🔗 **LangGraph-Oriented:** Graph-based agent orchestration for extensibility.
- 🏗️ **Clean Python:** Clear separation of core logic, graph, nodes, state, tools, and UI.
- 🖥️ **Simple Web UI:** User-friendly interface for interacting with the chatbot.
- 🧩 **Extensible:** Easily add more nodes, tools, and agent behaviors.

---

## 🧠 Technical Stack

- **Python 3.13+**
- **Agentic AI Patterns**
- **LangGraph-inspired graph orchestration**
- **Modular agent, node, and state abstractions**
- **No heavy dependencies – lightweight and hackable**

---

## 🏗️ Project Structure

```bash
Agentic_AI_Project1_End_To_End_Basic_Chatbot/
├── app.py                     # Entry point for running the chatbot app
├── requirements.txt
├── LICENSE
├── README.md
└── src/
    ├── __init__.py
    ├── langgraphagenticai/
    │   ├── __init__.py
    │   ├── LLMS/
    │   │   ├── __init__.py
    │   │   └── groqllm.py
    │   ├── graph/
    │   │   ├── __init__.py
    │   │   └── graph_builder.py
    │   ├── nodes/
    │   │   ├── __init__.py
    │   │   └── basic_chatbot_node.py
    │   ├── state/
    │   │   ├── __init__.py
    │   │   └── state.py
    │   ├── tools/
    │   │   └── __init__.py
    │   └── ui/
    │       ├── __init__.py
    │       └── main.py
    └── __pycache__/
```

---

## ⚡ Installation & Usage

### 1. Clone the repository
```bash
git clone https://github.com/mdzaheerjk/Agentic_AI_Project1_End_To_End_Basic_Chatbot.git
cd Agentic_AI_Project1_End_To_End_Basic_Chatbot
```

### 2. Set up a virtual environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the chatbot
```bash
python app.py
```
or (if there is a UI):
```bash
python src/langgraphagenticai/ui/main.py
```

---

## 🧪 Example Usage

- **Basic Chat:**  
  Say hello or ask questions; the chatbot responds using agentic logic.
- **Easily Extendable:**  
  Add more nodes (skills), tools, or change agent state logic for smarter conversations.

---

## 📚 Documentation

See code comments and structure for details on extending the agentic graph, nodes, and state.

---

## ✍️ Author

**Mohammed Zaheeruddin**  
🎓 First-Year B.Tech Student | AI/ML & GenAI Enthusiast  
🏫 Shetty Institute of Technology, Gulbarga  
📧 info.zaheerjk@gmail.com

---

## 📜 License

This project is licensed under the **GPL-3.0 License** – see the LICENSE file for details.

---

#### Key Features:
1. Modular, agentic chatbot with graph-based orchestration
2. Clean, extensible Python codebase (add more agents, tools, UIs)
3. Designed for learning, research, and quick prototyping
