# Project Memory — CS440 Vacuum Robot

## Project goal
This project uses a 4 × 4 vacuum robot grid as the shared example for CS440 Lab 4. This repository demonstrates **Strategy 1: Write (Persistent Memory Architecture)** from the context engineering lecture.

Keep the project's established facts and working guidelines in files so a coding agent can recover the same context in a new session without relying on past chat messages.

## Persistent instructions
- Use `context/environment.md` as the reference for the grid layout.
- Use `context/requirements.md` for the current lab scope.
- Distinguish confirmed information from missing specifications. Ask before making choices that would change robot behavior.
- Keep additions consistent with the existing environment. When a rule is confirmed, update the relevant context file so future sessions use the same information.
- Do not implement Q-learning for this lab; the assignment says that work comes later.

## Context organization
- **Project memory (this file):** Stable goals, conventions, and instructions shared by the team.
- **Detailed context (`context/`):** The environment and assignment boundaries, separated so the agent can consult only what is needed.
- **Personal memory:** Individual preferences are not included because this is a shared class repository.

This is a file-based persistent memory setup. It does not configure automatic context-selection hooks.
