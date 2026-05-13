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
