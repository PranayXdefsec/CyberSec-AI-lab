# 🛡️ CyberSec AI Lab

### Local LLM Deployment + Cybersecurity AI Learning Agent

![Cybersecurity](https://img.shields.io/badge/Cybersecurity-Lab-red?style=for-the-badge)
![AI](https://img.shields.io/badge/AI-LLM-blue?style=for-the-badge)
![Ollama](https://img.shields.io/badge/Ollama-Local%20LLM-black?style=for-the-badge)
![OpenClaw](https://img.shields.io/badge/OpenClaw-AI%20Agent-purple?style=for-the-badge)
![Kali Linux](https://img.shields.io/badge/Kali-Linux-557C94?style=for-the-badge)
![Telegram](https://img.shields.io/badge/Telegram-Bot-26A5E4?style=for-the-badge)

---

# 🧠 About This Project

**CyberSec AI Lab** is a hands-on project exploring the use of
Large Language Models and AI agents for cybersecurity learning,
research and controlled security experimentation.

The project combines two major components:

### 🧠 Module 01 — Local Cybersecurity LLM

Deployment and evaluation of an 8B cybersecurity-focused Large
Language Model using **Ollama**.

The objective was to understand local LLM deployment,
model selection, hardware compatibility, GPU/VRAM usage
and cybersecurity-oriented AI experimentation.

### 🤖 Module 02 — Cybersecurity AI Learning Agent

Development of an AI-powered cybersecurity assistant using
**OpenClaw**, an LLM backend, **Telegram** as the communication
interface and **Tavily** for web search.

The agent was also tested with cybersecurity tooling such as
**Subfinder** in an authorized learning environment.

---

# 🎯 Project Objectives

The main objectives of this project were:

- Understand how Large Language Models can be deployed locally
- Evaluate an 8B cybersecurity-focused model
- Study GPU and VRAM requirements for local inference
- Build an AI agent capable of interacting through Telegram
- Integrate an LLM backend with an AI agent framework
- Add web-search capabilities to the agent
- Explore AI-assisted cybersecurity workflows
- Experiment with security-tool interaction
- Understand the limitations of free-tier AI infrastructure
- Document the complete deployment and testing process

---

# 🏗️ Project Architecture

```text
                         🛡️ CYBERSEC AI LAB
                                  │
                 ┌────────────────┴────────────────┐
                 │                                 │
                 ▼                                 ▼
        🧠 MODULE 01                      🤖 MODULE 02
        LOCAL LLM LAB                     AI AGENT LAB
                 │                                 │
              Ollama                           OpenClaw
                 │                                 │
          8B Cyber LLM                      OpenRouter
                 │                                 │
        Local Inference                      Telegram
                 │                                 │
          GPU / VRAM                          Tavily
                 │                                 │
                 │                       Security Tools
                 │                                 │
                 └────────────────┬────────────────┘
                                  │
                                  ▼
                         🔐 CYBERSECURITY
                           LEARNING LAB


