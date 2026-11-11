# Social Network App

Full-stack social network application built as a team project, according to the requirements of kood/Jõhvi: https://github.com/01-edu/public/tree/master/subjects/social-network

A live demo is hosted on Oracle Cloud Infrastructure: http://92.5.159.165:3000
> ⚠️ **Note on the Demo**
> Some features may not work as expected because this demo is an unrefactored snapshot of our original student project, originally developed solely for local `npm run dev` environments without strict containerization. The core codebase has been intentionally left as-is, as a complete re-architecture is planned (see [Future Plan](#future-plan) below).


## Tech Stack
- **Frontend:** Next.js (TypeScript)
- **Backend:** Go (REST API / WebSockets)
- **Database:** SQLite
- **Infrastructure:** Docker, Docker Compose, Nginx, OCI (Ampere A1 Flex)

## Original Project Context
Created during a fast-paced team sprint based on the kood/Jõhvi requirements.

### Team
- [@jvillem](https://01.kood.tech/git/jvillem)
- [@mlutter](https://01.kood.tech/git/mlutter)
- [@mpuusaag](https://01.kood.tech/git/mpuusaag)
- [@skoppelm](https://01.kood.tech/git/skoppelm)

*(Check the contributors section for GitHub profiles where applicable)*

###  Project Reflection

- **Team Workflow Insights:** A tight schedule with an ad-hoc student team led to haphazard development without a structured plan or clear task distribution, resulting in architectural inconsistency and inefficient workflows.
- **Key Takeaways:** Realized the critical necessity of team alignment, up-front planning, and careful application design before jumping into coding.

### Infrastructure & Hosting Updates (2026)

Originally developed as a local-only environment since deployment was not part of the kood/Jõhvi requirements. To make it publicly accessible, I containerized the frontend and backend using Docker Compose and deployed it onto an Oracle Cloud Infrastructure (OCI) ARM instance (Ubuntu 24.04).

### Future plan

Based on the lessons learned from this team project, I am currently re-developing this app **as a solo project leveraging AI-assisted development tools (Cursor/LLMs)**. This new iteration will feature a proper Product Requirements Document (PRD), modern UI/UX design, and a scalable serverless architecture (Vercel + Supabase). Following document and design are in progress.

- **PRD (In Progress):** [View Notion PRD](https://app.notion.com/p/PRD-SNS-App-Reloaded-39f7d3e40494804d839eee5bc1ac7f2e?source=copy_link)
- **UI Design (In Progress):** in Penpot *(The screenshots below are part of the design)*