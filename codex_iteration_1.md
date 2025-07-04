 # Iteration 1: University Course for AI, LLM, Python, and Git

 **Session Information**
 - **Model**: o4-mini
 - **Provider**: openai
 - **Approval**: suggest
 - **Workdir**: ai-the-new-hope-for-scientific-programming

 ## User Goal

 Create a new university course focused on AI, LLM, Python, and Git, promoting teamwork among students of various academic levels (Bachelors, Masters, PhDs).

 ## Course Outline

 ### 1. Course Objectives

 - Show how to set up and run a data-science/AI project end-to-end using Python, Git/GitHub, and cloud/LLM APIs.
 - Teach students to think in “agents + pipelines” rather than one-off scripts.
 - Build real teamwork skills: Git workflows, code review, role-based collaboration.
 - Expose everyone to prompt engineering, basic LLM internals, and how to wrap an LLM into a Python tool.
 - Produce a polished code + documentation deliverable at the semester’s end.

 ### 2. Prerequisites & Setup

 - Python 3.8+ (basic fluency: lists, dicts, functions; pointers to a self-study Python mini-course).
 - Git & GitHub account.
 - VS Code (or another IDE).
 - Basic Unix shell comfort.
 - We’ll run on everyone’s laptop; optional AWS S3 buckets for larger data.

 ### 3. Course Format

 - Weekly 2-hour lecture (concepts + demos) + 2-hour hands-on lab (guided exercises).
 - Teams of 3–4, balanced across program levels.
 - All code + write-ups live in a team GitHub repo; use GitHub Classroom to automate repo creation, CI checks, and code-review assignments.
 - Mid-semester “sprint” presentations and peer evaluations.
 - Final deliverable: a working “agentized” scientific-programming pipeline (code + Sphinx-generated docs + short report + screencast).

 ### 4. High-Level Weekly Breakdown

 - **Week 1: Onboarding & GitHub–VSCode workflow**
   - Git fundamentals, branching, PRs, code reviews
   - GitHub Classroom & CI basics
   - Team formation + charter
 - **Week 2: Python tooling for teamwork**
   - Virtual environments, packaging, linters, pre-commit
   - Quick pandas/plotly refresher notebooks
 - **Week 3: LLM + ChatGPT primer**
   - “What really is a transformer?” + chain-of-thought
   - Prompt patterns: zero-shot, few-shot, instruction tuning
 - **Week 4: OpenAI API + building a Python wrapper**
   - openai Python library, rate limits, cost monitoring
   - Designing a reusable “LLMClient” module
 - **Week 5: Agents & orchestration**
   - Agent architectures (ReAct, AutoGPT, custom pipelines)
   - Building a simple multi-stage agent in Python
 - **Week 6: Mid-course mini-project Sprint 1**
   - Teams propose a short “data+AI” use case
   - 1-page proposal + rough prototype + 5 min demo
 - **Week 7: Scientific-programming workflows**
   - Structuring long-running simulations or analysis in stages
   - Logging (rich), config (dynaconf/YAML), serialization (ruamel)
 - **Week 8: Sphinx & docs-as-code**
   - Auto-generated API docs, custom RST, gallery examples
   - Integrating Sphinx build in CI
 - **Week 9: Advanced prompt engineering & retrieval**
   - Retrieval-augmented generation, embeddings, vector stores
 - **Week 10: Cloud & data management (optional)**
   - AWS S3 (or Git LFS) for big data, access control, cost tracking
 - **Week 11: Testing & quality at scale**
   - Unit tests for agent code, CI pipelines, Git hooks
 - **Week 12: Final project sprint & dry run**
   - Teams finalize code, docs, report, screencast
 - **Final exam week:**
   - 10-min team demo + peer evaluation + QA from instructors

 ### 5. Team Project (End-to-End)

 - Pick a small scientific problem (e.g., process data, generate a CFD-like setup, build a toy digital twin).
 - Write an “agent” that:
   1. Ingests raw data
   2. Calls Python routines + LLM prompts to generate config or code
   3. Runs a short analysis or visualization
   4. Assembles results into a Markdown/Sphinx report
 - **Deliverables:**
   - Code in a GitHub repo with PR history
   - Auto-generated API + user guide via Sphinx
   - Short written report (PDF/HTML) and screencast demo

 ### 6. Assessment & Teamwork

 - Weekly lab checkpoints (20%)
 - Mid-term mini-project presentation (15%)
- Final project deliverable (40%)
 - Peer evaluations + code-review contributions (25%)
 - Masters/PhDs can opt for deeper “research challenge” extensions (e.g., fine-tuning, custom embeddings, multi-agent workflows)

 ### 7. Resources & Readings

 - **Git & GitHub**: Pro Git (Ch.2–7)
 - **LLMs**: “Attention Is All You Need” (overview), OpenAI Cookbook recipes
 - **Python**: Official packaging guide, Sphinx tutorial
 - **CI/CD**: GitHub Actions examples

 ---

 With this scaffold, teams get real, collaborative, scientific-programming practice from day 1—blending Python, Git, and LLM-powered agents—while the mixed-level setting is handled by role-assignment, peer teaching, and optional advanced tracks.