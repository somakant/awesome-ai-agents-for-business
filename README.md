# Awesome AI Agents for Business [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated, practical list of open-source AI agents, frameworks and tools that real businesses can run today — organised **by department**, with **starter stacks** for common business types. Written from an operator's point of view: what saves time, what customers notice, and where a human must stay in the loop.

Most AI lists are made for developers. This one is for founders, operations heads and CX leaders who need to decide **what to use for which job**. Every entry is open source or free to self-host unless marked.

⭐ **Star the repo** to follow updates · ✍️ **[Suggest a tool](CONTRIBUTING.md)** · 💬 **[Discussions](https://github.com/somakant/awesome-ai-agents-for-business/discussions)**

## Contents

- [Starter stacks by business type](#starter-stacks-by-business-type)
- [Customer support and front desk](#customer-support-and-front-desk)
- [Contact centre and voice](#contact-centre-and-voice)
- [Sales and CRM](#sales-and-crm)
- [Marketing and content](#marketing-and-content)
- [Operations and back office](#operations-and-back-office)
- [Finance](#finance)
- [HR and recruiting](#hr-and-recruiting)
- [Agent frameworks](#agent-frameworks)
- [No-code and low-code agent builders](#no-code-and-low-code-agent-builders)
- [Human in the loop, evaluation and safety](#human-in-the-loop-evaluation-and-safety)
- [Run models yourself](#run-models-yourself)
- [Guides worth reading](#guides-worth-reading)

## Starter stacks by business type

Pick one stack, run it for 30 days, measure one number. Adding tools is easy; adoption is the hard part.

| Business | Start with | Measure |
|---|---|---|
| **Clinic, salon, gym, local service** | [WhatsApp AI Front Desk](https://github.com/somakant/whatsapp-ai-front-desk) for FAQs and bookings + [Cal.com](https://github.com/calcom/cal.com) for scheduling + [Chatwoot](https://github.com/chatwoot/chatwoot) as the shared inbox | Enquiries answered in under 1 minute |
| **B2B services firm** | [Twenty](https://github.com/twentyhq/twenty) CRM + [n8n](https://github.com/n8n-io/n8n) to enrich and route leads + [Agent Command Centre](https://github.com/somakant/agent-command-centre) for approval-gated outreach | Days from enquiry to first meeting |
| **E-commerce brand** | [Chatwoot](https://github.com/chatwoot/chatwoot) + an FAQ bot for order status and returns + [Listmonk](https://github.com/knadh/listmonk) for email | Share of "where is my order?" handled without an agent |
| **Contact centre / BPO** | [CX Toolkit](https://github.com/somakant/cx-toolkit) for staffing and QA + [Pipecat](https://github.com/pipecat-ai/pipecat) or [LiveKit Agents](https://github.com/livekit/agents) for voice pilots + [Langfuse](https://github.com/langfuse/langfuse) to review every AI conversation | Repeat contacts within 7 days |
| **Lending, fintech, advisers** | [india-loan-cost](https://github.com/somakant/india-loan-cost) for honest APR and EMI maths + [Typebot](https://github.com/baptisteArno/typebot.io) for qualification flows + human review of every decision | Leads that reach an adviser with complete details |

## Customer support and front desk

- [Chatwoot](https://github.com/chatwoot/chatwoot) — Omnichannel support inbox (web chat, WhatsApp, email, social) with bots and human agents in one place.
- [WhatsApp AI Front Desk](https://github.com/somakant/whatsapp-ai-front-desk) — Answers WhatsApp and web chat from your own FAQs and hands off to a person for complaints, refunds and unknown questions. Works with or without an AI key.
- [Rasa](https://github.com/RasaHQ/rasa) — Framework for building conversational assistants with full control over dialogue and data.
- [Botpress](https://github.com/botpress/botpress) — Platform for building and deploying chatbots and AI agents across channels.
- [Typebot](https://github.com/baptisteArno/typebot.io) — Visual chatbot builder for forms, qualification and support flows; embeds on any site.
- [Zammad](https://github.com/zammad/zammad) — Helpdesk and ticketing system for support teams.

## Contact centre and voice

- [CX Toolkit](https://github.com/somakant/cx-toolkit) — Erlang C staffing calculator, weighted QA scorecards and clearly defined CX metrics; runs in the browser.
- [Pipecat](https://github.com/pipecat-ai/pipecat) — Framework for real-time voice and multimodal AI agents.
- [LiveKit Agents](https://github.com/livekit/agents) — Build real-time voice agents that join calls and rooms.
- [Vocode](https://github.com/vocodedev/vocode-core) — Library for voice-based LLM agents over phone and web.
- [Asterisk](https://github.com/asterisk/asterisk) — The long-standing open-source telephony engine behind many contact centres.

## Sales and CRM

- [Twenty](https://github.com/twentyhq/twenty) — Modern open-source CRM.
- [EspoCRM](https://github.com/espocrm/espocrm) — Lightweight CRM for small and mid-size teams.
- [Cal.com](https://github.com/calcom/cal.com) — Scheduling infrastructure: booking pages, routing forms and calendar sync.
- [Agent Command Centre](https://github.com/somakant/agent-command-centre) — Blueprint for running a small team of scheduled AI agents (research, outreach, content, inbox) with a human approval gate on everything outbound.

## Marketing and content

- [Mautic](https://github.com/mautic/mautic) — Marketing automation: segments, campaigns, email and landing pages.
- [Listmonk](https://github.com/knadh/listmonk) — Fast self-hosted newsletter and mailing-list manager.
- [Postiz](https://github.com/gitroomhq/postiz-app) — Social media scheduling across many platforms.
- [Umami](https://github.com/umami-software/umami) — Privacy-friendly website analytics.
- [Plausible](https://github.com/plausible/analytics) — Simple, cookie-free website analytics.

## Operations and back office

- [ERPNext](https://github.com/frappe/erpnext) — Full ERP: accounting, inventory, manufacturing, projects.
- [Paperless-ngx](https://github.com/paperless-ngx/paperless-ngx) — Scan, OCR, index and archive documents.
- [Docling](https://github.com/docling-project/docling) — Turn PDFs and office documents into clean, structured data for AI pipelines.
- [Invoice Ninja](https://github.com/invoiceninja/invoiceninja) — Invoicing, quotes, payments and expenses.
- [Orkas](https://github.com/Orkas-AI/Orkas) — Local-first desktop AI workspace that coordinates specialist agents to turn business files into reports and presentations.

## Finance

- [india-loan-cost](https://github.com/somakant/india-loan-cost) — EMI, true APR with fees, flat-to-reducing conversion and offer comparison for Indian loans.
- [Firefly III](https://github.com/firefly-iii/firefly-iii) — Personal and small-business finance manager.
- [Actual](https://github.com/actualbudget/actual) — Local-first budgeting app.

## HR and recruiting

- [Frappe HR](https://github.com/frappe/hrms) — HR and payroll: employees, leave, attendance, appraisals.
- [OpenCATS](https://github.com/opencats/OpenCATS) — Applicant tracking system for recruiters.

## Agent frameworks

- [LangGraph](https://github.com/langchain-ai/langgraph) — Build stateful, multi-step agents as graphs, with human-in-the-loop checkpoints.
- [CrewAI](https://github.com/crewAIInc/crewAI) — Role-based multi-agent teams.
- [AutoGen](https://github.com/microsoft/autogen) — Multi-agent conversation framework from Microsoft.
- [Semantic Kernel](https://github.com/microsoft/semantic-kernel) — SDK for adding AI agents to C#, Python and Java apps.
- [LlamaIndex](https://github.com/run-llama/llama_index) — Connect agents to your documents and data.
- [Haystack](https://github.com/deepset-ai/haystack) — Pipelines for search, RAG and agents.
- [Pydantic AI](https://github.com/pydantic/pydantic-ai) — Type-safe agent framework for Python.
- [Model Context Protocol](https://github.com/modelcontextprotocol) — Open standard for connecting AI assistants to tools and data; see the [reference servers](https://github.com/modelcontextprotocol/servers).

## No-code and low-code agent builders

- [n8n](https://github.com/n8n-io/n8n) — Workflow automation with AI agent nodes; self-hostable.
- [Activepieces](https://github.com/activepieces/activepieces) — Open-source automation, an alternative to Zapier.
- [Dify](https://github.com/langgenius/dify) — Build LLM apps and agents with a visual workflow editor.
- [Flowise](https://github.com/FlowiseAI/Flowise) — Drag-and-drop builder for LLM flows and agents.
- [Langflow](https://github.com/langflow-ai/langflow) — Visual builder for agents and RAG apps.

## Human in the loop, evaluation and safety

- [Langfuse](https://github.com/langfuse/langfuse) — Tracing, evaluation and prompt management: see what every AI conversation actually did.
- [Promptfoo](https://github.com/promptfoo/promptfoo) — Test prompts and agents, and red-team them before customers do.
- [Guardrails](https://github.com/guardrails-ai/guardrails) — Validate and structure LLM outputs.

## Run models yourself

- [Ollama](https://github.com/ollama/ollama) — Run open models locally with one command.
- [Open WebUI](https://github.com/open-webui/open-webui) — Self-hosted chat interface for local and API models.
- [vLLM](https://github.com/vllm-project/vllm) — High-throughput model serving for production.

## Guides worth reading

- [Building effective agents](https://www.anthropic.com/research/building-effective-agents) — Anthropic's practical guide: start simple, add complexity only when it pays.
- [OWASP Top 10 for LLM Applications](https://genai.owasp.org/) — The security risks to check before an agent touches customer data.

## Operator rules of thumb

1. **Automate the question, not the relationship.** Let AI handle the repeatable 60–80% (status, hours, prices, bookings) and route the rest to a person fast.
2. **Every outbound message gets a human gate** until the agent has earned trust on real data.
3. **Measure one number per agent.** If you cannot say what it improved, switch it off.
4. **Hand-off is the product.** If a customer has to repeat their story to a human, the automation failed.

## Contributing

Additions welcome. Read the [guidelines](CONTRIBUTING.md): open source or free to self-host, actively maintained, and useful to a non-developer business team. One tool per pull request.

## About

Curated by [SK Pokhrel](https://www.linkedin.com/in/somakant), 20+ years in operations, CX and go-to-market. If you want these set up for your business, [House of AI](https://housofai.com/?utm_source=github&utm_medium=oss&utm_campaign=awesome-agents) builds and runs AI agents for customer service, sales and operations.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/) To the extent possible under law, the author has waived all copyright to this list.
