# 🚀 LangGraph: Modular LLM Workflows Playground

[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)](https://jupyter.org/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)](https://www.python.org/)
[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/sifanmomin1/langgraph/pulls)

> **Unlock the power of Language Models through interactive, modular workflows—right in your browser.**

---

## ✨ What is LangGraph?

**LangGraph** is an open-source Python library built on top of LangChain that enables the creation of complex, stateful, and cyclic workflows for AI agents—especially those powered by Large Language Models (LLMs). It adopts a graph-based architecture to model agent behavior, offering more flexible, dynamic, and reusable execution flows than traditional linear pipelines.

Explore patterns like:

- 🤖 Agentic Reasoning  
- 🔁 Iterative Prompting  
- 🔗 Prompt Chaining  
- ⚡ Parallel Inference  
- 🔀 Conditional Routing
- 🔗 Presistent Memory 

All within one interactive playground.

---

## 🧩 Workflow Patterns

LangGraph supports the following modular workflow patterns:

### 🔗 Sequential
Tasks run in order — perfect for multi-step reasoning.

### ⚡ Parallel
Execute multiple prompts or analyses concurrently.

### 🔀 Conditional
Branch your logic based on model output or custom conditions.

### 🔁 Iterative
Loop until the LLM gives you what you want.

---

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
