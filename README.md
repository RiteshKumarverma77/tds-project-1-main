---
title: Tds Project 1 Main
emoji: 📚
colorFrom: red
colorTo: indigo
sdk: docker
pinned: false
---

This is a FastAPI-based automation service that receives task briefs, generates apps using LLMs, creates GitHub repositories, and pings evaluation servers.

### How to run locally

```bash
# 1. Create virtual environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run server
uvicorn app.main:app --reload
```


