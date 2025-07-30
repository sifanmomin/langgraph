# 🚀 LangGraph: Building llm Powered Agents

[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)](https://jupyter.org/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)](https://www.python.org/)
[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/sifanmomin1/langgraph/pulls)

> **Unlock the power of Language Models through interactive, modular workflows—right in your browser.**

---

## ✨ What is LangGraph?

**LangGraph** is an open-source Python library built on top of LangChain that enables the creation of complex, stateful, and cyclic workflows for AI agents—especially those powered by Large Language Models (LLMs).  

<p align="center">
  <img src="images/langgraph_overview.png" alt="LangGraph Overview" width="700"/>
</p>

---

## 🧩 How LangGraph Works

LangGraph represents workflows as **directed graphs**, where:
- **Nodes:** Define LLM calls, tools, or decision logic  
- **Edges:** Define the data flow between steps  
- **Loops:** Enable retry/iteration until a condition is met  

### Example 1: Sequential + Conditional Workflow

<p align="center">
  <img src="images/workflow_conditional.png" alt="LangGraph Conditional Workflow" width="400"/>
</p>

### Example 2: Parallel Workflow

<p align="center">
  <img src="images/workflow_parallel.png" alt="LangGraph Parallel Workflow" width="600"/>
</p>

### Example 3: Full Graph Overview

<p align="center">
  <img src="images/langgraph_graph_demo.png" alt="LangGraph Graph Demo" width="700"/>
</p>
## 🗂️ Notebook Catalog

| Notebook                   | Description                                                      |
|----------------------------|------------------------------------------------------------------|
| `bmi.ipynb`                | Calculate BMI using code logic and LLM reasoning                 |
| `customer_sentiment.ipynb` | Analyze customer feedback sentiment using LLMs                   |
| `llm_workflow.ipynb`       | Build modular agent workflows and evaluate their output          |
| `parallel.ipynb`           | Run concurrent prompt chains for faster results                  |
| `prompt_chaining.ipynb`    | Train LLMs for multi-step reasoning and chaining                 |
| `quadratic.ipynb`          | Solve quadratic equations using LLMs as solvers                  |
| `uspc.ipynb`               | Explore a user-defined structured process chain                  |
| `x_post.ipynb`             | Advanced post-processing and formatting with agents              |
| `chatbot.ipynb`            | Build an interactive LLM-powered chatbot using LangGraph & LangChain which has the memory(RAM Memory)|


---

## 🌟 Why Use LangGraph?

✅ **Modular Design** – Swap, link, or loop your agent blocks with ease  
✅ **Jupyter First** – No special UI, just your familiar playground  
✅ **Educational** – Great for tinkerers, students, and LLM engineers  
✅ **Practical** – Real use cases for agent-based LLM development  

---

## 🚀 Getting Started

```bash
git clone https://github.com/sifanmomin1/langgraph.git
cd langgraph
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook
