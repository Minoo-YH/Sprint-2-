# Sprint 2 — README

## Overview

This document summarizes **Sprint 2** for our Scrum project, including the team structure, Sprint goal, delivered work, repositories, and a retrospective (what went well / what didn’t / improvements).

- **Sprint Name:** Sprint 2
- **Sprint Timebox:** `02-02-26` → `13-02-26`
- **Sprint Goal:**
  - Frontend:
  -
- **Product/Project:** HelpConnect
- ~~**Version/Release (if any):** 
- **Prototype:** https://www.figma.com/make/qMKm053W5kn1JNJOwQ51h0/Help-App?t=hXBCaRWimu2RI1rC-1

---

## Team & Roles :


### Scrum Master

- **Name:** Minoo Yaghoubi — _Frontend Developer_
- **GitHub:** _[https://github.com/Minoo-YH]_

### Product Owner

- **Name:** Markus Kannisto — _Frontend Developer_
- **GitHub:** _[https://github.com/Marakusa]_

### Developers (2)

1. **Name:** Mikael Nyman — _Backend Developer_
   - GitHub: _[https://github.com/MiksuNy]_
2. **Name:** Maria Kuznetsova — _Backend Developer_
   - GitHub: _[https://github.com/makuzaza]_

---

## Repositories (All Members)

### Main Team Repository

- **Team Repo:** _[https://github.com/MiksuNy/web-project]_

### Project Board

- **Trello:** _[https://trello.com/b/kDm20dKm/web-project-team-6]_

---

## Sprint 2 Plan

### Sprint Goal

The goal of Sprint 2 was to create the backend API and frontend UI without any integration yet, and make everything ready for that integration.

### Scope (What we planned)

List the main backlog items / user stories planned for Sprint 2:

- Authentication: Frontend & Backend
- Post browser: Frontend & Backend
- Post form: Frontend & Backend
- Admin dashboard: Frontend & Backend

---

## Sprint 2 Work Details

### Completed (Done)

✅ Items fully completed and meet the Definition of Done:

- Authentication: Frontend & Backend
- Post browser: Frontend & Backend
- Post form: Frontend & Backend

### In Progress / Not Completed

⚠️ Items not finished and reasons:

- Admin dashboard: Frontend & Backend
  - Reason: Only post and user management implemented
- Message box and chat: Frontend & Backend
  - Reason: Needs polishing

### Backlog Updates

Changes to backlog during Sprint 2:

- Added: AI integration, mobile responsiveness, integrate frontend to backend (sprint 3)
- Removed: Payments (not to be implemented yet, would expand scope too much)
- Refined: Only one endpoint for requests and offers -> unified posts API endpoint

---

## Definition of Done (DoD)

An item is considered **Done** only if:

- Code implemented and reviewed (PR approved)
- No critical bugs open
- Tests written/updated (unit/integration as appropriate)
- Documentation updated (README / comments / API docs)
- Deployed or packaged (if relevant)
- Meets acceptance criteria

---

## Sprint 2 Deliverables

Provide a clear list of what the team delivered.

- **Login/Registration pages:** _Forms for logging in and registration_
- **Post browser/form:** _Browse user created posts and create them using the form_
- **Admin panel:** _Admins can manage posts and users_
- **Backend API:** _API connecting backend to frontend and database_

### Evidence (Screenshots / Demo / Video)

Demo videos in the presentation.

---

## How to Run the Project (Quick Start)

> Replace the commands below with your real steps.

### Requirements

- _[Node.js 18+]_
- _[MongoDB]_

### Setup

```bash
# clone
git clone https://github.com/MiksuNy/web-project

# backend install
cd web-project/backend
npm install

# frontend install
cd ../frontend
npm install

# configure environment
cd ../backend
cp .env.example .env
# update .env values
```

### Run backend and frontend in separate terminals
```bash
# navigate to backend folder
cd web-project/backend
# run
npm run dev
```
```bash
# navigate to frontend folder
cd web-project/frontend
# run
npm run dev
```
