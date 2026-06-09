# AI Resume Adapter Bot

AI Resume Adapter Bot is a local MVP web assistant for job description analysis and resume tailoring workflow.

The project was created as part of a vibe-coding course.

## Purpose

The goal of this project is to support a structured job search process for the German job market.

The assistant helps analyze a job description, estimate ATS match, detect red flags, and prepare a truthful resume adaptation strategy.

## Main Workflow

The tool follows a strict staged workflow:

- Stage 0: Resume Selection
- Stage 1: Checkup
- Stage 1.5: Hiring Manager Scan
- Stage 2: Tailoring only after human approval

## Key Features

- Job description analysis
- Resume fit check
- Simulated ATS match score
- Risk flag detection
- Human approval before tailoring
- Prompt Builder for Resume ATS workflow
- EN / RU interface switch
- Local-only prototype

## Important Rule

The tool must not invent experience.

Resume adaptation must stay truthful.

The user must review the result before sending any application.

## Current Status

This is a first MVP prototype.

It works locally in the browser.

No backend, database, LinkedIn automation, or external API is used.

## Future Ideas

Future versions may include:

- Resume file upload
- LLM API integration
- Telegram assistant
- Job board tracking
- Application status dashboard
- Semi-automatic job search workflow with human approval

## Portfolio evolution

This repository is part of an evolving AI-automation portfolio, not a one-off demo. The projects show a growth path from job-search automation and local MVPs toward safer IT/cloud/security operations with agentic workflows.

Current portfolio map:

- **[Hermes SecOps Copilot](https://github.com/gdc88/boris-hermes-secops-portfolio)** — Newest portfolio layer: Hermes/OpenClaw-style AI automation for cloud security operations, M365/Azure readiness, Copilot governance, and agentic workflows. Live page: https://gdc88.github.io/boris-hermes-secops-portfolio/
- **[AI Automation Ops Lab](https://github.com/gdc88/boris-ai-automation-ops-lab)** — Operational base layer: self-hosted AI automation patterns, Telegram delivery, scheduled agents, browser-assisted workflows, and infrastructure operations thinking.
- **[Ops Agent Playbook Runner](https://github.com/gdc88/ops-agent-playbook-runner)** — Engineering proof layer: safe, auditable, dry-run-first operations playbooks with evidence bundles and policy controls.
- **[AI Resume Adapter Bot](https://github.com/gdc88/ai-resume-adapter-bot)** — Career automation layer: ATS/job-description analysis and truthful resume tailoring workflow for the German market.
- **[JobMatch AI](https://github.com/gdc88/JobMatch-AI)** — Course/final-project layer: static MVP for job-match analysis, recruiter message drafting, and portfolio demonstration.

Growth direction:

- Keep public repositories sanitized and recruiter-safe.
- Prefer clear architecture, safety boundaries, screenshots/visuals, and evidence over private operational data.
- Update each project as the overall system matures: better runbooks, stronger guardrails, clearer German-market positioning, and more polished demos.
- Use GitHub as the proof layer and LinkedIn as the recruiter funnel once the LinkedIn profile is aligned with the same positioning.
