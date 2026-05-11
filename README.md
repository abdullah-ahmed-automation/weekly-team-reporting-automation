# Weekly Team Reporting Automation

AI-powered weekly team reporting automation built for **Khaliji Rasheq** using **n8n, Google Forms, Google Sheets, JavaScript, OpenAI, and Gmail**.

---

## Project Overview

This project automates the weekly team reporting process for a health and nutrition center.

Instead of collecting reports manually, employees submit their weekly performance through a Google Form. The responses are stored automatically in Google Sheets. n8n then reads the data on a weekly schedule, calculates key performance numbers, sends the data to AI for analysis, and emails a formatted Arabic management report to the operations team.

---

## Problem

The management team needed a simple and organized way to:

- Collect weekly employee reports
- Track new leads, body scans, subscriptions, and missed visits
- Identify recurring operational problems
- Collect employee suggestions
- Receive a clear weekly summary without manual reporting work

Manual reporting was time-consuming and could easily become inconsistent.

---

## Solution

I built an automated workflow that:

1. Collects employee reports through Google Forms
2. Stores all responses in Google Sheets
3. Runs automatically every week using n8n Schedule Trigger
4. Reads the weekly report data from Google Sheets
5. Uses JavaScript to calculate weekly totals
6. Sends the summarized data to OpenAI for analysis
7. Generates a clean Arabic HTML management report
8. Sends the report automatically by Gmail to the management email

---

## Workflow

Google Form → Google Sheet Responses → n8n Schedule Trigger → Google Sheets Node → JavaScript Code Node → OpenAI AI Agent → Gmail Send Message

---

## Tools Used

- **n8n** — Workflow automation
- **Google Forms** — Employee report submission
- **Google Sheets** — Report database
- **JavaScript** — Data aggregation and calculations
- **OpenAI** — AI-powered report analysis and Arabic summary generation
- **Gmail** — Automated email delivery

---

## Google Form Fields

Employees submit the following weekly data:

- Date
- Employee Name
- New Leads
- Body Scans
- New Subscriptions
- Missed Visits
- Problems
- Suggestions

---

## Key Features

- Weekly scheduled automation
- Employee-friendly Google Form input
- Automatic Google Sheets data collection
- JavaScript-based KPI calculation
- AI-generated Arabic management report
- Clean HTML email formatting
- Automatic Gmail delivery
- Suitable for clinics, health centers, sales teams, and small businesses

---

## Example Weekly Metrics

The workflow can calculate and summarize:

- Total new leads
- Total body scans
- Total new subscriptions
- Total missed visits
- Best performing employee or area
- Main operational problems
- Practical recommendations for the next week
- Short WhatsApp-style message for the team

---

## Output Example

The final email report includes:

- Executive summary
- Key numbers
- Best performing area
- Main problems
- Recommendations for next week
- Team message
- Clean Arabic right-to-left HTML layout

---

## Business Value

This automation helps management save time, reduce manual reporting, and make faster decisions based on weekly operational data.

It can be adapted for:

- Health centers
- Clinics
- Gyms
- Nutrition centers
- Sales teams
- Customer support teams
- Small business operations

---

## Result

The workflow was successfully built, tested, and published.

It now runs automatically on a weekly schedule, reads employee submissions from Google Sheets, generates an AI-powered Arabic report, and sends it to management by email.

---

## Screenshots

Screenshots can be added here:

- Google Form
- Google Sheet Responses
- n8n Workflow
- Email Report

---

## Project Status

Completed and tested successfully.
