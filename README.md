# LLM Zoomcamp 2026 — Homework & Project Repository

This repository contains my solutions, notebooks, and experiments for the **LLM Zoomcamp 2026**.  
Each module has its own folder with the corresponding homework and helper scripts.

---

## 📁 Repository Structure

```
llm-zoomcamp-2026/
├── 01-agentic-rag/
│   ├── homework1.ipynb
│   └── rag_helper.py
├── 02-vector-search/
│   └── ...
├── pyproject.toml
├── uv.lock
├── README.md
└── .gitignore
```

- **Module folders** contain the homework notebooks and any supporting code.
- **pyproject.toml** defines all project dependencies (managed with `uv`).
- **uv.lock** ensures reproducible environments.
- **.gitignore** keeps the repo clean from temporary or local files.

---

## 🚀 Getting Started

### 1. Clone the repository
```
git clone https://github.com/sfragkiadakhs/llm-zoomcamp-2026.git
cd llm-zoomcamp-2026
```
### 2. Install dependencies using uv
``` 
uv sync
```
### 3. Launch Jupyter Lab
```
uv run jupyter lab
```
---
## 🧩 Dependencies

All dependencies are declared in `pyproject.toml`. 

## 📝 Notes

- This is a **personal learning repository** for the Zoomcamp.
- The environment is managed with **uv**, and the `.venv/` folder is ignored.
- Each module’s work is isolated in its own directory.
- Notebooks use the project’s kernel for consistent dependencies.

---

## 🎯 Goal

Document my progress through the LLM Zoomcamp and build a clear, organized collection of exercises and experiments.

## 📚 Course Source

Official course materials:
👉 https://github.com/DataTalksClub/llm-zoomcamp/tree/main/cohorts/2026