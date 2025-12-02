# n8n-ai-lead-qualification-engine
Automating lead scoring and intent-based routing using n8n and LLMs.
# 💰 AI-Powered CRM Lead Qualification Engine

This project demonstrates a high-ROI workflow designed to maximize sales efficiency by instantly scoring and routing inbound leads, eliminating manual qualification time.

**Problem Solved:** Sales team time wastage on unqualified leads; slow speed-to-lead for hot prospects.

## Architecture & Features

### 1. Structured Scoring & Routing
The core logic forces AI to make actionable decisions that directly impact revenue.

* **Webhook Ingestion:** Catches form data instantly from any external source.
* **Enrichment:** Simulates API call to enrich lead data (company size, industry).
* **AI Judge & Jury:** Employs a Gemini LLM to score leads (0-100) against an Ideal Customer Profile (ICP) and provides a written justification.
* **Logic Routing:** Uses a Switch Node to send "Hot Leads" to an immediate Slack alert and "Cold Leads" to a nurture archive.

### 2. Output and Impact
The system ensures that Sales Development Reps (SDRs) spend 100% of their time on prospects most likely to close.


## Files in this Repository

* `crm_lead_qualification.json`: The sanitized n8n workflow file.
* `README.md`: This document.

## How to Run Locally

1.  Import the workflow file.
2.  Configure the Gemini API Key and relevant Slack/CRM credentials.
3.  Trigger the Webhook with sample lead data.
