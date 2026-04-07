# Enterprise Agentic AI Evaluation Framework
> Multi-agent workflows with autonomous tool use, self-reflection, and LLM-as-a-judge evaluation

## Problem
Customer service teams waste hours on manual triage of return/refund tickets.
This project automates ~65% of ticket resolution using a multi-agent AI system.

## What I Built
- Multi-agent orchestration with autonomous web search, iterative self-reflection, and planning
- Mixed-LLM pipeline routing fast tasks to Groq (~1.1s) and complex synthesis to OpenAI
- LLM-as-a-judge evaluation framework to score outputs against a ground-truth SQLite database
- Human-in-the-loop Gradio web app for final review before decisions are applied

## Tech Stack
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat)
![Gradio](https://img.shields.io/badge/Gradio-FF7C00?style=flat)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)

## Key Results
- Reduced average API response time from ~4s to ~1.1s via LLM routing strategy
- LLM-as-a-judge protocol catches edge-case failures before reaching end users

## How to Run
1. Clone the repo: `git clone https://github.com/cgy11102/agentic-workflow-engineering`
2. Install dependencies: `pip install -r requirements.txt`
3. Add your OpenAI + Groq API keys to `.env`
4. Run: `jupyter notebook` and open the main notebook
