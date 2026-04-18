# Twilio-Powered AI Customer Support & Order Resolution System

A client-style customer support automation system built with **n8n, Twilio WhatsApp, Google Gemini, Airtable, and Airtable Interfaces**.

## Project Overview

This system receives customer support messages from WhatsApp through Twilio, classifies customer intent with AI, checks order records in Airtable, routes requests by category, sends automated WhatsApp replies, logs support tickets, generates daily support analytics, and captures workflow failures in a system error log.

## Features

- WhatsApp message intake via Twilio
- AI intent classification
- Airtable order lookup
- Automated support routing
- Order status handling
- Refund request handling
- Wrong item escalation
- Delayed package handling
- Return request handling
- General inquiry handling
- Human escalation handling
- No-order-found fallback
- Daily support analytics
- Automatic system error logging

## Workflows

### WF1 - Customer Support Engine
Handles:
- Order Status
- Refund Request
- Wrong Item
- Delayed Package
- Return Request
- General Inquiry
- Human Escalation
- No Order Found

### WF2 - Daily Support Analytics
Calculates:
- Tickets Today
- Auto-resolved %
- Refunds Issued
- Escalations

### WF3 - System Error Logger
Logs:
- Workflow Name
- Node Name
- Error Message
- Severity
- Status

## Tools Used

- n8n
- Twilio WhatsApp Sandbox / API
- Google Gemini
- Airtable
- Airtable Interfaces
- HTTP Request nodes
- Code nodes

## Folder Structure

```text
workflows/
screenshots/
demo-video/
docs/

Built by Ifeanyi Nwadike
assets/
README.md
