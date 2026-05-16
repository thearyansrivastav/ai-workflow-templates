# Daily Briefing Workflow

**Status:** Active  
**Platform:** n8n  
**Delivery:** Telegram / Slack

---

## Purpose

Generate a single daily operational briefing using:
- calendar events
- pending tasks
- flagged emails
- CRM reminders
- AI-generated summaries

The goal is to reduce context switching and create a clean operational overview each morning.

---

## Workflow Structure

1. Pull calendar events from Google Calendar
2. Fetch overdue tasks from Notion or Airtable
3. Collect flagged emails
4. Generate short AI summary
5. Deliver briefing to Telegram or Slack

---

## Example Output

- 3 meetings today
- 5 overdue tasks
- 2 high-priority emails
- 1 pending client deliverable

AI summary:
"Main focus today should be proposal completion and client follow-ups."

---

## Stack

- n8n
- OpenAI API
- Telegram Bot API
- Notion API
- Google Calendar API

---

## Notes

Useful for small async teams and solo operators managing multiple systems simultaneously.

Maintained by Aryan Srivastav / Arise AI.
