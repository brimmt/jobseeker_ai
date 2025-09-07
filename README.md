# Job Seeker AI

## Overview
SaaS tool to reduce job application time by up to 70% via automation + AI-assisted workflows (resume parsing, role matching, templated outreach).

## Stack
- Backend: Python (FastAPI), Pydantic
- Data: Supabase/PostgreSQL
- AI: OpenAI API
- Frontend: Tailwind + JavaScript (React planned)
- Infra: Vercel/Render (dev), AWS EC2 (planned)

## Features
- [x] Auth + basic dashboard (prototype)
- [x] Resume upload → parse key skills/experience
- [ ] Job matching pipeline
- [ ] 1-click cover letter draft
- [ ] Application tracker

## Getting Started
```bash
# Backend
uvicorn app.main:app --reload

# Frontend (if separate)
npm install && npm run dev
