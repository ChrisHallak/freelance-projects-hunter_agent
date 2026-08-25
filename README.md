# freelance-projects-hunter_agent
AI-powered n8n automation that monitors freelance projects, matches them against my skills using an LLM, and sends relevant opportunities to Telegram.

# Freelance Projects Hunter

An AI-powered automation that monitors freelance projects, evaluates them against my technical skills using an LLM, and sends Telegram notifications when a relevant opportunity is found.

The goal is simple: **find relevant freelance projects as soon as they are published, so I don't miss good opportunities because I saw them too late.**

---

## How It Works

The workflow automatically monitors new projects on **Mostaql**, retrieves the project details, and uses an LLM to determine how well the project matches my skills.

```text
Mostaql
   ↓
New Projects
   ↓
Filter Relevant Projects
   ↓
Get Project Details
   ↓
LLM Skill Matching
   ↓
Match Score & Analysis
   ↓
Telegram Notification
