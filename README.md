# SDSF – Smart Design Storage Facilities

A single-file web app for managing a storage facility — rooms, customers, waiting list, maintenance, finance, and invoices.

## Features

- **Dashboard** — Live KPIs, occupancy pie chart, revenue trend, alerts, activity feed
- **Room Management** — Add, view, delete rooms; filter by status; click any room for details
- **Customer Management** — Add, delete customers; track payment status
- **Waiting List** — Add/remove leads; assign them to rooms; priority badges
- **Maintenance Board** — Kanban with Open / In Progress / Closed; create and delete tickets; move tickets between columns
- **Finance** — Revenue and expense breakdown
- **Invoices** — Generate, filter (All / Paid / Overdue / Pending), delete; PDF export and email send
- **Settings** — Toggle notifications; share dashboard with time-limited links
- **Share System** — Owner generates a link with an expiry date; clients see a read-only view that shows a lock screen when the link expires; only the owner can share

## Data Persistence

All data is saved to `localStorage` so it persists across page refreshes. Seed data is pre-loaded on first visit.

## Deployment (Vercel)

1. Push both `index.html` and `vercel.json` to a GitHub repository
2. Go to [vercel.com](https://vercel.com) → **Add New Project** → import your repo
3. Framework: **Other** (no build step needed)
4. Click **Deploy** — done

## Local Preview

Open `index.html` directly in any browser — no server required.
