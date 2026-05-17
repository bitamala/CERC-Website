# EduCheck

EduCheck is a student-driven oversight platform for schools and educational services, stewarded by CRAC and hosted on Azure. Inspired by Integrity Action’s DevelopmentCheck, EduCheck empowers students, parents, and community members to report and track issues affecting education quality, infrastructure, accessibility, and relevance.

## Quickstart

1. Install dependencies:  
   - `cd frontend && npm install`
   - `cd backend && npm install`

2. Run locally:  
   - Frontend: `npm start` (in `frontend/`)
   - Backend: `npm start` (in `backend/`)

3. Deploy to Azure:  
   - Use the infra/bicep template, or let GitHub Actions deploy automatically.

## Repo Structure

- `frontend/` – React web app (PWA, multi-language, accessible)
- `backend/` – Express REST API (issue tracking, roles, Azure AD ready)
- `infra/` – Azure App Service Bicep template
- `.github/workflows/` – CI/CD pipeline for Azure
- `docs/` – Design docs and specs

See [`docs/educheck-design.md`](docs/educheck-design.md) for detailed feature and architecture overview.