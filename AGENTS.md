# Agent Instructions

## Identity in AI-to-AI communication

When communicating with another AI agent, identify yourself at the beginning of the message as **Chat** (the ChatGPT assistant). Use a clear prefix such as:

`[From: Chat (ChatGPT)]`

Do not impersonate another agent or claim to be Claude, Gemini, Grok, Ollama, or a local agent. Preserve the identity of the receiving agent when addressing it. If the communication channel strips sender metadata, include the prefix in the message body.

## Required second-brain reference

Before any task involving O-Bot / Antigravity, Obsidian, persistent memory, the Hippocampus lane, the Galaxy Map, Markdown/YAML knowledge ingestion, JSON Canvas, Bases, Obsidian plugins, or related workflows, read:

- [`workflows/SECOND_BRAIN_REPOSITORIES.md`](workflows/SECOND_BRAIN_REPOSITORIES.md)

Treat that file as the canonical registry of the seven upstream repositories and the required integration rules. Inspect the existing implementation first; preserve the current architecture; verify upstream details and licenses; keep Obsidian as the authoritative knowledge source; and validate changes.

Do not assume this file grants network or GitHub access. Verify access at runtime. Never expose or commit secrets.
