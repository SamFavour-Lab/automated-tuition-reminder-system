# Automated Tuition Reminder System

## Overview

The Automated Tuition Reminder System is an n8n workflow designed to help educational institutions automate tuition payment reminders. The workflow checks student payment records stored in Airtable on a scheduled basis, identifies students with outstanding tuition balances, and automatically sends personalized reminder emails using Gmail.

This automation reduces repetitive administrative tasks, improves communication with students, and supports more consistent tuition collection.

---

## Business Problem

Many schools and training organizations manually track overdue tuition payments and send reminder emails individually. This process is time-consuming, prone to human error, and can lead to delayed payments.

---

## Solution

This workflow automatically:

- Runs on a scheduled basis.
- Searches Airtable for students with outstanding tuition payments.
- Filters only unpaid records.
- Sends personalized reminder emails through Gmail.

This enables staff to focus on higher-value administrative work while ensuring payment reminders are sent consistently.

---

## Technologies Used

- n8n
- Airtable
- Gmail

---

## Workflow

```text
Schedule Trigger
        │
        ▼
Search Airtable Records
        │
        ▼
Filter Outstanding Payments
        │
        ▼
Send Reminder Email (Gmail)
```

---

## Business Value

- Automated payment reminders
- Improved cash flow
- Reduced manual administrative work
- Consistent student communication
- Faster payment follow-up

---

## Key Features

- Scheduled workflow execution
- Airtable integration
- Automatic filtering
- Personalized Gmail notifications
- Low-maintenance automation

---

## Future Improvements

- SMS reminders
- WhatsApp notifications
- Payment dashboard
- Parent notifications
- Payment status reporting

---

## Author

**Samuel Favour**

AI Automation Specialist

GitHub: https://github.com/SamFavour-Lab
