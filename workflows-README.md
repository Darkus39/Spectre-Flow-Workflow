# ⚡ Spectre Flow — Workflow Library

> Production-ready n8n automation workflows built by [Spectre Flow](https://spectre-flow-website.vercel.app). Each workflow is structured for real business operations — not demos, not tutorials. Built to run.

[![Website](https://img.shields.io/badge/spectreflow.ai-00C8FF?style=for-the-badge&logo=vercel&logoColor=black)](https://spectre-flow-website.vercel.app)
[![Book a Call](https://img.shields.io/badge/Book_Free_Discovery_Call-00E5C8?style=for-the-badge&logo=googleforms&logoColor=black)](https://forms.gle/cck7MXYo4DW2qLBi6)
[![Instagram](https://img.shields.io/badge/@spectreflow.ai-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/spectreflow.ai)

---

## What's in here?

This repository contains a growing library of plug-and-play n8n workflows across lead generation, social automation, AI pipelines, and meeting intelligence. Every file is a `.json` export ready to import directly into your n8n instance.

**Want one deployed for your business?** → [Book a free discovery call](https://forms.gle/cck7MXYo4DW2qLBi6)

---

## `./workflows`

### 🔍 LinkedIn Lead Scraping & Enrichment
**File:** `LinkedIn_Leads_Scraping_Enrichment_Main.json`

A 66-node end-to-end lead intelligence pipeline. Pulls LinkedIn profiles, scrapes post history and about sections, enriches each lead with verified email addresses via Apollo.io, validates emails, AI-summarizes every prospect using Claude/OpenAI, and auto-populates a structured Google Sheet — fully hands-free.

**What it replaces:** Manual LinkedIn prospecting + VA email finding + manual CRM entry

| Detail | Info |
|--------|------|
| Nodes | 66 |
| Trigger | Google Sheets / Schedule / Manual |
| Integrations | LinkedIn · Apollo.io · OpenAI · Google Sheets |
| Output | Enriched lead database with AI summaries + verified emails |

---

### 🎙️ AI Meeting Intelligence Agent
**File:** `Lmchatopenai_Workflow.json`

Connects to Google Meet after every call, pulls the transcript automatically, uses an AI agent to extract action items, decisions, and follow-up tasks, manages attendee lists, and schedules follow-up calendar events — all without anyone doing anything after the call ends.

**What it replaces:** Manual note-taking + follow-up scheduling + action item tracking

| Detail | Info |
|--------|------|
| Nodes | 28 |
| Trigger | Manual / Execute Workflow |
| Integrations | Google Meet · OpenAI · Google Calendar · Google Drive |
| Output | AI-extracted action items + auto-scheduled follow-ups |

---

### 📣 Facebook Page Comment Monitor
**File:** `Comments_for_facebook_page.json`

Pulls the latest posts from any Facebook page, fetches all comments on each post, filters nulls, and structures everything into clean, queryable data — post ID, timestamp, message, commenter name. Ideal for social listening, reputation management, and lead identification from engagement.

**What it replaces:** Manual Facebook monitoring + comment tracking spreadsheets

| Detail | Info |
|--------|------|
| Nodes | 10 |
| Trigger | Manual (schedulable) |
| Integrations | Facebook Graph API |
| Output | Structured comment dataset per post |

---

### ⛓️ LLM Chaining Engine
**File:** `LLM_Chaining_Examples.json`

A modular multi-step AI pipeline built on Anthropic Claude. Runs LLM chains sequentially and in parallel, maintains conversation memory, handles webhook inputs, and merges outputs from multiple AI steps. Acts as a backbone for any complex AI reasoning workflow — plug your business logic in and it thinks through it step by step.

**What it replaces:** Simple single-prompt AI calls — this enables multi-stage AI reasoning

| Detail | Info |
|--------|------|
| Nodes | 38 |
| Trigger | Manual / Webhook |
| Integrations | Anthropic Claude · HTTP Request · Webhook |
| Output | Chained AI reasoning output with memory |

---

## How to use these workflows

1. Open your n8n instance
2. Go to **Workflows → Import from file**
3. Upload the `.json` file
4. Connect your credentials (API keys for the relevant services)
5. Adjust any parameters marked in sticky notes inside the workflow
6. Activate

> **Don't have n8n set up?** We can deploy the full self-hosted stack for you. [Book a call →](https://forms.gle/cck7MXYo4DW2qLBi6)

---

## Want this deployed for your business?

We don't just hand you a JSON file. We deploy, configure, connect your credentials, test end-to-end, and hand you a running system.

**Discovery call is free. No commitment.**

[![Book a Free Discovery Call](https://img.shields.io/badge/Book_a_Free_Discovery_Call-00C8FF?style=for-the-badge&logo=googleforms&logoColor=black)](https://forms.gle/cck7MXYo4DW2qLBi6)

---

## More systems

Browse the rest of Spectre Flow's deployed infrastructure:

| Repo | What It Does |
|------|-------------|
| [lead-intelligence-engine](https://github.com/Darkus39/lead-intelligence-engine) | AI lead scoring & CRM routing |
| [AI-booking-agent](https://github.com/Darkus39/AI-booking-agent) | 24/7 autonomous meeting scheduling |
| [AI-notification-hub](https://github.com/Darkus39/AI-notification-hub) | Lead routing + Discord/SMS alerts |
| [Document-intelligence-manager](https://github.com/Darkus39/Document-intelligence-manager) | WhatsApp doc analysis + calendar events |
| [Rag-knowledge-bot](https://github.com/Darkus39/Rag-knowledge-bot) | RAG Q&A bot via WhatsApp |

---

```
Systems don't sleep. Neither does the work.
— Spectre Flow
```
