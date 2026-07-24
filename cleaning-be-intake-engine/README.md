# Cleaning Bee Intake Engine
**AI-Powered Lead-to-Booking Automation for Cleaning Services.**

The system ingests email inquiries, classifies leads, auto-replies with quotes and screening questions, checks Google Calendar availability, books appointments, and sends confirmations — all without human intervention.

---

## The Problem

Cleaning Bee PH handled leads manually:

- A human read every email, classified urgency, looked up pricing, typed a quote, checked Google Calendar for availability, replied to schedule, and updated a spreadsheet
- Response time: **2–6 hours** (same-day at best)
- Inconsistent quoting and screening across different staff
- No automated follow-up for scheduling — leads fell through cracks
- Manual spreadsheet management prone to typos and duplication

**Before:**
| Metric | Manual |
|---|---|
| Lead response time | 2–6 hours |
| Scheduling | Manual calendar check + email thread |
| Data entry | Prone to typos, missed rows |
| Staff hours/week on intake | ~15–20 hrs |

---

## The Solution

A **single n8n workflow with 3 branches** that automates the full intake pipeline.

