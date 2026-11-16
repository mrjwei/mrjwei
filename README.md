## Hi, I'm Jesse 👋

**Product designer and engineer. I turn how a business really works into software people keep using.**

Ten years of B2B product work in Japan, with product design and frontend engineering in one head, and now LLM features with a person at every decision that matters. I'm based in Brisbane, completing a Master of IT at QUT in December 2026, and I work in Chinese, English, Japanese and Korean.

### What I'm building now

- **[agent-loop](https://github.com/mrjwei/agent-loop)**: an autonomous issue-to-PR loop on headless Claude Code. A read-only triage agent syncs issues with the plan, work agents build in parallel worktrees, an independent review checks each acceptance criterion, and the loop merges low-risk PRs judged from the diff. I merge the high-risk ones and answer blocked issues. Now: hardening the review step as autonomy goes up, and closing the outer loop from an empty directory to plan, issues, PRs, merges and re-planning.
- **AI-drafted compliance records** (DEN, pilot moving onto AWS): deterministic checks in code, LLM self-assessment and mandatory human sign-off, so nothing is issued that a person hasn't confirmed.
- **[yuho-rag](https://github.com/mrjwei/yuho-rag)** (early): a RAG service over Japanese securities filings (有価証券報告書) from the EDINET API. Spec and first filings are in; retrieval and an eval suite in CI come next.
- **Design in Git**: design-system work moved into a repository, so tokens, components and decisions sit under version control and review. Start with [I Was Reinventing Git in Figma](https://jessewei.net/posts/design-in-git/i-was-reinventing-git-in-figma).

### Recent work

- **[Interlixir](https://github.com/mrjwei/interlixir-public)**: turns interview and usability-test recordings into structured research documents. Event-driven AWS pipeline with self-hosted Whisper on Fargate (scales 0–8 on queue backlog), PII redaction, schema-driven synthesis on Bedrock and a tool-using chat agent (MCP). [Write-up](https://jessewei.net/projects/interlixir).
- **[LLM security triage evaluation](https://jessewei.net/projects/ai-sec)** (QUT capstone, 2026): an evaluation harness over 146 labelled attacks across 14 techniques on a Wazuh SIEM. Logging design, not model choice, explained most detection gaps. The method is in [llm-evals](https://github.com/mrjwei/llm-evals).
- **An LLM proofreader for technical manuals** (client work, 2026): five weeks in a team delivering for a Japanese manufacturer. I evaluated its checks on real pages, traced a class of false positives to text extraction and fixed it at the source.
- **[LingoBun](https://jessewei.net/projects/lingobun)**: my own AI vocabulary app, built like production software. Rate limits and cost caps on every AI call, validated configuration and 180 automated tests.
- **[Strobe Assistant](https://jessewei.net/projects/strobe)**: a conversational agent, async photo-search pipeline and daily autonomous agent on AWS (Bedrock, ECS Fargate, S3 Vectors).
- **[nextjs-hp](https://github.com/mrjwei/nextjs-hp)**: jessewei.net itself, bilingual, with a Claude-run pipeline that proofreads, translates and publishes posts from an Obsidian backlog.

Client code lives in private repos. The case studies are on [jessewei.net](https://jessewei.net/projects).

### How I work

1. **Understand the operation.** Start from how work is done today and what actually needs to change.
2. **Decide who decides.** Separate what code decides, what a model drafts and what a person signs off.
3. **Design and build together.** Interface and production frontend in one pair of hands, so nothing is lost in a handoff.
4. **Prove it and make it stick.** Tests, evaluation, field feedback and a design system.

### A few results

- Redesigned a ski-pass booking flow at WAmazing, cutting peak-season inquiries from 200+ a week to about 4
- Helped a paper-run welfare business at DEN grow from one 20-person facility to a multi-site operation of about 80 staff on digital workflows
- Set up the first design process and design system at Zerospec as its first product designer, then rebuilt the system in code on shadcn/ui
- Led frontend development on an enterprise HR SaaS at Money Forward

### Stack

TypeScript · React · Next.js · Tailwind · shadcn/ui · Python · FastAPI · Claude Code · MCP · Amazon Bedrock · AWS (ECS Fargate, Lambda, SQS, DynamoDB) · PostgreSQL · Redis · Vitest · Figma

### Open to

Senior IC roles where design, engineering and AI meet inside real operations: AI solutions or forward-deployed engineer, AI product engineer, or design/UX engineer. Tokyo, from early 2027.

### Find me

[jessewei.net](https://jessewei.net) · [LinkedIn](https://www.linkedin.com/in/jesse-wei-profile/) · jesseweijapan@gmail.com
