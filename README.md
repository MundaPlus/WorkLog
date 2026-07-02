# WorkLog

> A self-hosted productivity platform that helps freelancers and small teams track time, manage knowledge, and get AI-powered assistance — all from a single, privately hosted application.

![Status](https://img.shields.io/badge/status-active-brightgreen)

## Overview

Freelancers and small agencies lose hours every week switching between time-tracking tools, note apps, bookmark managers, and AI assistants. WorkLog consolidates all of these into one privately hosted web application — with no subscription fees, no third-party data exposure, and full control over where data lives.

It is actively used in production by Munda Plus d.o.o. and is available for licensing or custom deployment to other businesses.

## Key Capabilities

- **Time tracking with client and project context** — log tasks against specific clients and projects, start and stop timers across sessions, and view daily, weekly, and historical breakdowns at a glance
- **Project budgeting and deadline tracking** — monitor hours consumed versus budget and track progress toward project deadlines across the full portfolio
- **AI assistant for natural language task entry** — instruct the platform in plain language ("log 2 hours on the Acme deployment for today") and it creates tasks, updates statuses, and manages timers automatically; works with Anthropic Claude, any OpenAI-compatible provider, or a fully local model
- **Semantic knowledge base** — upload documents, audio recordings, meeting transcripts, or PDFs; the platform indexes them with vector search so relevant context surfaces automatically and task suggestions are generated from the content
- **Rich notes with cross-user sharing and sync** — a full WYSIWYG note editor with private and shared modes; notes can be linked across contexts and kept in sync with a one-click push/pull
- **Bookmark manager with live previews** — save URLs with automatic title, description, and image fetching; organise into nested folders; share across team members
- **Analytics dashboard** — visualise hours by day, client, task type, and project; review AI usage and cost history with date-range filtering
- **Encrypted backups on demand** — administrators can create password-protected archives of all data directly from the UI, with automatic snapshots taken before every system update

## Tech Highlights

| Layer | Technology |
|-------|------------|
| Backend API | Python (FastAPI) |
| Frontend | React — installable as a Progressive Web App |
| Rich text editor | TipTap (WYSIWYG, tables, colors, links) |
| AI integration | Anthropic Claude, OpenAI-compatible APIs, or local LLM (Ollama) |
| Semantic search | Vector database (ChromaDB) with local embeddings |
| Audio transcription | Local speech-to-text (faster-whisper) — no cloud audio upload |
| Data storage | SQLite — isolated per user, no shared data leakage |
| Authentication | JWT tokens + long-lived API tokens for integrations |
| Deployment | Single self-hosted service, runs on any Linux server |
| Backups | AES-256 encrypted zip archives |

## Screenshots

> *Screenshots available on request or at the project demo URL*

## Status & Availability

WorkLog is a mature, actively maintained application running in daily production use. Core features — time tracking, AI agent, knowledge base, notes, and bookmarks — are stable. Ongoing development is focused on team collaboration features and deeper AI integration. The platform is designed for straightforward deployment on a private server or VPS and can be customised for specific business workflows.

## Interested?

This is a proprietary project by **Munda Plus d.o.o.**  
The full codebase is available for review upon request.

📧 marko@munda.si  
🌐 [munda.si](https://www.munda.si)
