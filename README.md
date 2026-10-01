<div align="center">

  <h1>🤖 AgentReasoning</h1>
  <p><strong>A Comprehensive Hands-on Guide to LLM Agent Reasoning, TAO Frameworks, and ReAct Workflows</strong></p>

  <p>
    <a href="https://github.com/Melikeda/AgentReasoning/stargazers"><img src="https://img.shields.io/github/stars/Melikeda/AgentReasoning?style=for-the-badge&logo=github&color=yellow" alt="Stars"></a>
    <a href="https://github.com/Melikeda/AgentReasoning/network/members"><img src="https://img.shields.io/github/forks/Melikeda/AgentReasoning?style=for-the-badge&logo=github&color=orange" alt="Forks"></a>
    <a href="https://github.com/Melikeda/AgentReasoning/blob/main/LICENSE"><img src="https://img.shields.io/github/license/Melikeda/AgentReasoning?style=for-the-badge&color=blue" alt="License"></a>
    <img src="https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python&logoColor=white" alt="Python Version">
  </p>

  <p>
    <a href="#-about-the-project">About</a> •
    <a href="#-repository-structure">Structure</a> •
    <a href="#-key-concepts-covered">Key Concepts</a> •
    <a href="#-quickstart">Quickstart</a> •
    <a href="#-acknowledgements--credits">Acknowledgements</a> •
    <a href="#-license">License</a>
  </p>

</div>

---

## 📌 About The Project

**AgentReasoning** is a structured, production-focused repository dedicated to exploring and implementing modern **Large Language Model (LLM) Agentic Workflows**. It provides step-by-step Jupyter Notebook implementations of core cognitive architectures, reasoning patterns, and tool-augmented decision-making loops.

Whether you are building autonomous assistants, implementing complex decision trees, or fine-tuning agent loops, this repository serves as a reference implementation for key agentic paradigms.

---

## 📂 Repository Structure

The project is organized in a progressive learning sequence:

```text
AgentReasoning/
├── 📁 src/agentreasoning/       # Core modules and utility scripts
├── 📓 01_reasoning.ipynb       # LLM Reasoning Foundations & Prompting Strategies
├── 📓 02_agent_karari.ipynb    # Dynamic Agent Decision-Making & Tool Selection
├── 📓 03_tao.ipynb             # Thought-Action-Observation (TAO) Architecture
├── 📓 04_tao_dongusu.ipynb     # Iterative TAO Loops for Multi-Step Tasks
├── 📓 05_react.ipynb           # End-to-End ReAct (Reasoning + Acting) Implementation
├── 📄 .python-version          # Python version configuration
├── 📄 .gitignore              # Standard git ignore rules
└── 📄 README.md               # Project documentation
```

---

## 🛠 Key Concepts Covered

- **Reasoning Architectures:** Structured prompting and step-by-step cognitive deduction.
- **Autonomous Decision Making:** Evaluating context to dynamically select and execute appropriate tools.
- **TAO Framework (Thought-Action-Observation):** Decoupling reasoning traces from execution steps.
- **ReAct Pattern:** Combining reasoning and action steps for complex problem-solving.

---

## 🚀 Quickstart

### Prerequisites

Ensure you have **Python 3.10+** installed.

### Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Melikeda/AgentReasoning.git](https://github.com/Melikeda/AgentReasoning.git)
   cd AgentReasoning
   ```

2. **Set up virtual environment & install dependencies:**

   - **Using `uv` (Recommended):**
     ```bash
     uv venv
     source .venv/bin/activate  # On Windows use: .venv\Scripts\activate
     uv pip install -r requirements.txt
     ```

   - **Using standard `pip`:**
     ```bash
     python -m venv .venv
     source .venv/bin/activate  # On Windows use: .venv\Scripts\activate
     pip install -r requirements.txt
     ```

3. **Launch Jupyter Notebooks:**
   ```bash
   jupyter lab
   # or
   jupyter notebook
   ```

---

## 💻 Tech Stack

- **Language:** Python
- **Environment:** Jupyter Notebook / JupyterLab
- **Concepts:** LLM Agents, ReAct, TAO Loop, Tool Selection, Agentic Workflows

---

## 🙏 Acknowledgements & Credits

This repository contains practical implementations and notes developed during the **[AI Agents Bootcamp | Gathin](https://gathin.com)**.

Special thanks to the instructors and organizers at **Gathin** for providing a comprehensive curriculum on agentic AI workflows and reasoning architectures.
