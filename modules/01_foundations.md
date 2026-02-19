# Module 1 — AI Security Foundations

## Objective
Understand how AI systems are built and where security risks exist.

---

## 1. AI Application Architecture

Components:
- System Prompt
- User Prompt (untrusted)
- LLM Model
- Tools / External APIs
- Retrieval (RAG)
- Logging Layer

Security Insight:
AI apps are distributed systems with multiple trust boundaries.

---

## 2. Attack Surface Mapping (Red Team)

Focus Areas:
- Prompt injection points
- Tool execution layer
- API exposure
- Data retrieval systems

---

## 3. Defense Strategy (Blue Team)

Core Controls:
- Role separation
- Input validation
- Output enforcement
- Logging & monitoring
- Least privilege for tools

---

## Practical Exercise

Map the attack surface of:
- A chatbot
- A document summarizer
- An AI API service
