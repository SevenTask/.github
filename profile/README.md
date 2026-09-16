<h1 align="center">SevenTask</h1>

<p align="center">
  <strong>Collaborative work management for teams that don't all work the same way.</strong>
</p>

<p align="center">
  Kanban boards · Real-time chat · Time tracking · Shared calendar · Audited activity history
</p>

---

## What SevenTask is

SevenTask is a **collaborative project and task management platform** — in the same category as Jira, ClickUp, and Trello — built for teams that want their tool to match their workflow instead of the other way around.

Teams organize work across **personal boards, project boards, and team boards**, collaborate in real time, track time against tasks, and get a complete, localized audit trail of everything that changed.

## What makes it different

**🔀 Your workflow, not ours.**
Most tools ship a fixed `To Do → Doing → Done` pipeline and ask you to adapt. In SevenTask, **board columns are data, not code**. A dev team runs `Backlog → Sprint → Code Review → QA → Deployed`. A marketing team runs `Idea → Draft → Design → Approval → Published`. A consultancy adds client-approval gates mid-pipeline. No configuration ceremony, no plan upgrade, no waiting on us to ship a release.

**⚡ Real-time by default.**
Move a card and it moves for everyone, instantly — across every device and tab they have open. Chat, notifications, and live time tracking all run over the same persistent connection. No refresh button anywhere in the product.

**📜 A complete, honest history.**
Every status change, assignment, comment, and edit is recorded permanently and immutably. You can always answer *who moved this, when, and from where* — months later.

**🌍 Genuinely multilingual.**
Ten locales with full **right-to-left** support. Activity history is stored as structured events rather than pre-rendered text, so the same event renders correctly in each person's own language — a Persian-speaking teammate and a Spanish-speaking teammate read the same history in their own locale, at the same time.

**⏱️ Time tracking that fits real work.**
Start, pause, and resume timers on any task. Estimates are **per-person**, not per-task — because two people on the same task rarely estimate it the same way.

## Core features

| | |
|---|---|
| **Boards & tasks** | Custom columns, drag-and-drop, priorities, urgency flags, tags, checklists, attachments, due dates |
| **Organization** | Teams → Departments → Projects, with granular per-member access control |
| **Communication** | Team, project, department, and direct-message channels with pinning, replies, edit history, and read receipts |
| **Time** | Start/pause/stop tracking, per-assignee estimates, workload views |
| **Calendar** | Shared events linked to projects — Gregorian and Solar Hijri calendars |
| **Awareness** | In-app and email notifications, plus web push when the tab is closed |
| **History** | Full audit trail across tasks, teams, projects, departments, and events |

## Repositories

| Repository | What it is |
|---|---|
| [`seventask-app`](https://github.com/SevenTask/seventask-app) | Main web client — Angular SPA with server-side rendering |
| [`seventask-api`](https://github.com/SevenTask/seventask-api) | Core backend — REST API, real-time hub, and the domain model |
| [`seventask-admin-app`](https://github.com/SevenTask/seventask-admin-app) | Internal admin console |
| [`seventask-admin-api`](https://github.com/SevenTask/seventask-admin-api) | Admin backend |

> Application repositories are private. Each carries its own README with full setup instructions, version requirements, and architecture notes.

## Built with

**Frontend** — Angular · TypeScript · RxJS · Angular Material & CDK · SignalR client · Firebase Cloud Messaging

**Backend** — ASP.NET Core · Entity Framework Core · SQL Server · SignalR · ASP.NET Identity + JWT

**Operations** — Serilog + Seq for structured logging · Prometheus metrics · Locust load testing

---

<p align="center"><sub>MIT licensed.</sub></p>
