# CS440 Lab 4 — Strategy 1: Persistent Memory

This repository contains the Strategy 1 configuration for the vacuum robot lab. The purpose is to show how an AI coding agent can reuse consistent project context across sessions instead of requiring the team to repeat the same information in every prompt.

## Files

```text
cs440-lab4-persistent-memory/
├── CLAUDE.md                 Project-level memory and agent instructions
├── context/
│   ├── environment.md        Grid layout and known environment details
│   └── requirements.md       Assignment scope and open questions
└── README.md                 Explanation of this repository
```

## How Strategy 1 works here

`CLAUDE.md` provides the project's stable instructions. The two files under `context/` hold supporting details, keeping the main instructions short. An agent working on the vacuum robot can refer to these files instead of depending on earlier chat history.

For example, before discussing the robot's possible moves, the agent should read `context/environment.md`. Before proposing new code, it should check `context/requirements.md` and avoid implementing Q-learning prematurely.

This demonstrates **project-level persistent memory**, one part of Strategy 1 in the lecture (pages 21–28). The lecture also discusses personal memory and dynamic imports; those are not configured in this initial repository.

## Status

This is the initial **file-based configuration**, not an implemented Q-learning agent or a tested automated hook. We will confirm any additional expectations in class before extending it.

The companion repository demonstrates Strategy 4 (sub-agent isolation).
