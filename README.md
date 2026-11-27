# Zillow Agents CRM

Call-list CRM for agent outreach: Dashboard (50 calls/day goal, today's meetings and follow-ups),
Call List, No Answer, Talked To, Video Call Set, Video Call Met, Closed, Not Interested.

- `index.html` is the whole app.
- `agents.json` is the agent contact list (1,137 agents).
- `state.json` is a snapshot of call statuses (Nov 27, 2026) for views outside Claude.

Statuses, dates, and notes are saved by the Claude artifact this was built for
(https://claude.ai/artifact/HHveEKM8mjM5FbimxsDa7r). Opened anywhere else, such as GitHub Pages,
the page shows a read-only snapshot of statuses from `state.json` (no notes) and cannot save changes.

Keep this repo private: `agents.json` holds phone numbers and emails.
