# ⚡ n8n Automation & Backend Engineering Portfolio

### Hi there! I'm Gabriel España 👋
**Telecom Engineer (in training) | n8n Certified Expert | Cisco CCNA**

I specialize in designing scalable automation architectures that bridge the gap between complex APIs, AI Agents, and Business Logic. My background in Network Infrastructure (CCNA) allows me to build robust, secure, and efficient backend workflows.

---

## 🛠️ Tech Stack & Tools

* **Orchestration:** n8n (Certified), Make.
* **Languages & Scripting:** JavaScript (Node.js environment), SQL, Python.
* **AI & LLMs:** OpenAI (GPT-4), Google Gemini, Stability AI, Replicate, Retell AI (Voice).
* **Infrastructure:** Docker, Webhooks, REST/GraphQL APIs.
* **Platforms:** Kommo CRM, Aloware (VoIP), Simvoly, Airtable, Postgres.

---

## 📂 Featured Workflows

Below is a curated collection of advanced automation workflows I have engineered.

### 🤖 1. AI Voice Agents & Telephony
| Project | Description | Key Tech |
| :--- | :--- | :--- |
| **[Retell Call Analysis Logger](./01-ai-voice-agents/retell-call-analysis-logger.json)** | Listen for AI voice agent webhooks, analyze sentiment/outcome, and log structured data to Airtable & CRM. | `Retell AI` `Airtable` `JS Regex` |
| **[Lead Confirmation Agent](./01-ai-voice-agents/lead-confirmation-voice-agent.json)** | Triggers outbound AI calls to confirm event attendance and updates CRM pipeline stages in real-time. | `Kommo API` `Voice AI` |
| **[Recall Campaign Engine](./01-ai-voice-agents/retell-ai-recall-campaign.json)** | Re-engagement system that deploys negotiation AI agents to recover cold leads or cancellations. | `LLM Injection` `CRM` |
| **[VoIP Recording Logger](./01-ai-voice-agents/aloware-call-recording-logger.json)** | Captures "Call Ended" events from Aloware, extracts recording URLs, and pushes transcripts to the deal timeline. | `Aloware` `Webhooks` |

### 🚀 2. CRM & Marketing Operations
| Project | Description | Key Tech |
| :--- | :--- | :--- |
| **[VIP Ticket Router](./02-crm-marketing-ops/vip-ticket-management-system.json)** | Parses high-value e-commerce orders, extracts complex tags (time-slots), and routes leads to priority pipelines. | `Simvoly` `JSON Parsing` |
| **[Bidirectional Enrichment](./02-crm-marketing-ops/gsheets-to-crm-enrichment.json)** | Fixes missing CRM data by performing lookups against a master Google Sheet database using email keys. | `Google Sheets` `Merge Data` |
| **[CRM Archiver](./02-crm-marketing-ops/crm-lead-migration-archiver.json)** | "Garbage collection" system that classifies lost leads, archives them to Sheets, and cleans up the active pipeline. | `Data Hygiene` `Cron` |

### 🎨 3. Generative AI Tools
| Project | Description | Key Tech |
| :--- | :--- | :--- |
| **[Telegram AI Avatar Bot](./03-generative-ai-tools/telegram-ai-image-generator.json)** | Full-stack bot: Receives user selfies, analyzes biometrics with Gemini Vision, and generates stylized avatars (Simpson/Lego) via Replicate. | `Telegram API` `Gemini Vision` `Stable Diffusion` |
| **[Web Style Transfer](./03-generative-ai-tools/web-image-style-transfer.json)** | Backend for a web app that processes multipart form data to generate and email AI artwork. | `Binary Handling` `Gmail SMTP` |

### 📊 4. Analytics & Reporting
| Project | Description | Key Tech |
| :--- | :--- | :--- |
| **[Meta Ads Reporter](./04-reporting-analytics/meta-ads-automated-reporting.json)** | Automated pipeline fetching recursive Graph API data (Campaigns -> AdSets -> Insights) to build granular KPI reports. | `Facebook Graph API` `Pagination` |

---

## 🔧 How to Use These Workflows

1.  **Download** the `.json` file of the workflow you are interested in.
2.  Open your **n8n** instance (self-hosted or cloud).
3.  Go to **Workflows** > **Import from File**.
4.  Configure your own credentials (API Keys are stripped for security).

---

## 📫 Contact

* **GitHub:** [Shinra2105](https://github.com/Shinra2105)
* **Role:** Open to L1-L3 Support & Automation Engineer roles.
* **Location:** Caracas, Venezuela (Available for Remote/Freelance).