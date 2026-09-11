# Session Context & System State Summary

## System & Environment Health
* **OS / Environment:** Clean Ubuntu WSL2 on Windows (`SMNH-DaddyLappy`).
* **Working Directory:** `/home/venkate/projects/euron-agentic-ai-engineering`
* **Python Virtual Env:** `.venv` managed by `uv` (Python 3.14 at `.venv/bin/python3`).
* **Repository Sync:** Connected via SSH to `https://github.com/Venkat-de/euron-agentic-ai-engineering` (`main` branch).
* **Workspace Structure:** Mirroring official Euron course folders (`agents/`, `Advance_RAG/`, `Deep_Agents/`, `Experiments/`, `Langchain_Agents/`, `MCP/`, `RAG_embedding/`, `WhatsApp_Agent/`). Personal context and notes isolated in `workspace_meta/`.

## Key Workspace Rules & Preferences
1. **Repository Layout:** Keep all official Euron course code intact at root. Keep all course notes, custom agent skills, and state summaries under `workspace_meta/`.
2. **Dependency Management:** Always use `uv sync` from root when dependencies update.
3. **Git Hygiene:** Stage and push progress to `origin main` after completing exercises.

## History & Milestones
* **Restructure Completed:** Wiped initial temporary layout (`src/`, `notebooks/`, etc.) and copied complete Euron course materials.
* **Environment Synced:** Ran `uv sync` to align dependencies with Euron's official `pyproject.toml` and `uv.lock`.
* **Git Initial Push:** Pushed commit `c1f0a70` containing all 111 course files to GitHub.
