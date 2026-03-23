# Zen Ceramic Staff Portal

Internal staff portal for Zen Ceramic branch operations.

**Live URL:** https://zenceramic-staff.github.io/portal/

## Features
- **Today's Dashboard** — See all bookings for today grouped by time slot, check in customers
- **Week Ahead** — 7-day overview of slot occupancy across all time slots
- **Check-In** — Tap to check in customers when they arrive
- **Manager View** — Switch between branches (manager role only)

## Tech Stack
- Frontend: Static HTML/CSS/JS on GitHub Pages
- Backend: Google Apps Script (Zen Ceramic V6)
- Database: Google Sheets
- Auth: Phone + 4-digit PIN (stateless, validated per request)

## Files
```
index.html    ← Login screen
app.html      ← Main dashboard
README.md     ← This file
```

## Staff Access
Staff accounts are managed in the "Staff" sheet tab in the Google Sheet. Each row contains:
- Phone number
- 4-digit PIN
- Name
- Branch ID
- Role (staff / manager)
- Active (TRUE / FALSE)

---
*Zen Ceramic 陶艺 — Internal Use Only*
