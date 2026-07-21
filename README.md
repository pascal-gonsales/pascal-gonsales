# Pascal Gonsales

**AI Solutions Analyst.** I turn messy operational data into AI tools that non-technical teams actually use.

Operator background (years running multi-location restaurants), now building practical AI systems. I work the business side of AI adoption: find the real automation opportunity, design the workflow, and ship something a small team can run themselves. Bilingual FR and EN.

## What I build

Three public anchors, each a different slice of applied AI. Every repo is built clean: synthetic demo data only, claims kept honest, no real client data anywhere.

### restaurant-ai-agents (flagship)
A multi-agent prompt system that turns raw restaurant data into decision-ready reports. The headline is the discipline, not the agents: every agent carries a hard anti-fabrication contract (no invented numbers, source-traced citations, mandatory data-quality notes), and a CI test fails the build if any agent drops its rules. Python, pytest.
https://github.com/pascal-gonsales/restaurant-ai-agents

### ai-hr-chatbot
A single-organization HR assistant prototype for frontline staff: a Claude-powered, streaming, tool-using chat with strict "AI is the interface, not the authority" guardrails, and per-user data isolation (Postgres row-level security plus application-level ownership checks on service-role access). Next.js, TypeScript, Supabase, Claude API, vitest.
https://github.com/pascal-gonsales/ai-hr-chatbot

### restaurant-lead-scraper
A B2B lead pipeline that scores and tiers prospects on a transparent 0 to 13 scale. The engineering point: every scoring constant lives once in Python and is interpolated into the generated workflow, with drift-catcher tests that turn CI red if the numbers ever disagree. Python, n8n.
https://github.com/pascal-gonsales/restaurant-lead-scraper

## How I work

- Operator to builder: I have lived the messy-data, thin-margin reality these tools are built for.
- AI as an accelerator: I build these with heavy AI assistance (Claude Code). My value is choosing the right operational decision, turning domain failure modes into constraints, testing the result, and catching confident errors before they ship. I do not claim unaided engineering authorship.
- Honest by construction: demo data is labeled, claims are not inflated, scope limits are stated, and public repos carry no real client data.
- Ship the smallest thing that earns trust, then iterate.

## Tech

Claude API, Python, TypeScript and Next.js, Supabase and Postgres, n8n, pytest and vitest, GitHub Actions.

## Security and development

These repositories contain only synthetic demo data and no real client, venue, or financial information. A CI workflow (`.github/workflows/secret-scan.yml`) runs gitleaks on every push and pull request and fails on any secret or credential finding. My local development setup also uses an untracked private-data blocklist that flags my own venture and client names before they can be committed.

## Contact

- Email: pascal.gonsales@gmail.com
- LinkedIn: https://www.linkedin.com/in/pascalgonsales
