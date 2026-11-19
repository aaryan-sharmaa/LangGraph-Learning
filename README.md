# LangGraph Learning

A hands-on collection of Jupyter notebooks documenting my journey of learning **LangGraph**, from basic workflows to building stateful AI agents.

This repository focuses on understanding LangGraph concepts through practical Python implementations, experiments, and small projects.

## Topics Covered

### 01 — Fundamentals

Exploring the four fundamental workflow patterns in LangGraph:

| Workflow | Description |
|---|---|
| Sequential | Executing nodes in a predefined order, passing state between them. |
| Parallel | Running independent nodes concurrently and merging their results using reducers. |
| Conditional | Dynamically routing execution based on conditions or LLM-generated decisions. |
| Iterative | Repeating steps through feedback loops until a condition is satisfied or an iteration limit is reached. |

**Implementations include:**
- BMI calculator
- LLM question answering
- Blog generation using prompt chaining
- Cricket statistics workflow
- Essay evaluation
- Quadratic equation solver
- Customer review handling
- X (Twitter) post generator with an evaluation and optimization loop

### Upcoming Topics

- State management and reducers
- Persistence and checkpointing
- Human-in-the-loop workflows
- Tool integration and AI agents
- Advanced agentic workflows

## Tech Stack

- **Python**
- **LangGraph** — Graph-based workflow orchestration
- **LangChain** — LLM integration
- **Groq** — LLM inference
- **Pydantic** — Structured data validation
- **Jupyter Notebook** — Learning and experimentation

## Repository Structure

```text
LangGraph-Learning/
├── 01_Fundamentals/
│   └── 8 Jupyter notebooks
├── .env.example
├── .gitignore
├── requirements.txt
└── README.md
```

Additional folders will be added as I progress through LangGraph.

## Getting Started

**1. Clone the repository**

```bash
git clone https://github.com/YOUR_USERNAME/LangGraph-Learning.git
cd LangGraph-Learning
```

**2. Create a virtual environment**

```bash
python -m venv .venv
```

Activate it on Windows:

```powershell
.venv\Scripts\Activate.ps1
```

**3. Install dependencies**

```bash
pip install -r requirements.txt
```

**4. Configure environment variables**

Copy `.env.example` to `.env` and add your Groq API key.

```env
GROQ_API_KEY=your_groq_api_key_here
```

**5. Run the notebooks**

Open the repository in VS Code or Jupyter and explore the notebooks inside `01_Fundamentals`.

## Learning Approach

This repository is part of my practical AI/ML learning journey.

My approach is to:
- Understand the concepts behind each workflow.
- Implement them using small, understandable examples.
- Experiment with graph execution, state updates, and routing.
- Gradually move from basic workflows toward real-world AI agents.

The code is primarily intended for learning and experimentation, rather than production use.

---

*Learning LangGraph, one workflow at a time.*