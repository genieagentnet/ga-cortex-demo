---
type: Service
title: Voice Agent
description: An AI receptionist that answers every call in under a second, sounds human, books appointments, answers FAQs, and never takes a day off.
resource: https://genieagent.net/#services
tags: [voice, receptionist, booking, 24-7]
status: stable
generated: { by: assal/1.0, at: "2026-11-15T15:05:00-05:00" }
verified: { by: human:victor, at: "2026-11-15T20:41:00-05:00" }
sources:
  - id: genieagent-home
    resource: https://genieagent.net/
    title: GenieAgent home page
    author: team:genie-agent
    last_modified: 2026-11-15
  - id: genieagent-support
    resource: https://genieagent.net/support
    title: GenieAgent support page
    author: team:genie-agent
    last_modified: 2026-11-15
---

# Overview

The Voice Agent is the flagship service of [Genie Agent](/company/overview.md):
an AI receptionist that answers every call in under a second, 24 hours a day,
7 days a week. The design decision behind it is recorded in
[Answer every call](/decisions/answer-every-call.md), and the times it is
built to hit are in [Speed to lead](/metrics/speed-to-lead.md).[^genieagent-home]

# What it does

1. Answers every call, including after-hours and overflow calls.
2. Greets the caller and states that it is an AI assistant on a recorded line.[^genieagent-support]
3. Answers questions from the information the client approved.
4. Books appointments directly into the client's calendar, with reminders.
5. Captures the caller's name, number, and request as a lead, which flows into [Lead Capture + CRM](/services/lead-capture-crm.md).
6. Records and transcribes every call, with live transcripts and summaries for the client.

When a call is beyond the agent, [Escalation and handoff](/runbooks/escalation-and-handoff.md)
applies. Booking confirmations and reminders by text follow the
[SMS program](/policies/sms-program.md). Clients choose how transparent the
agent is about being an AI; many have it introduce itself as a virtual
assistant.

# Terms

The Voice Agent plan is $999 a month with setup and onboarding included; see
[Plans and pricing](/services/plans-and-pricing.md). Most voice agents go
live in 2 to 4 weeks under [How it works](/process/how-it-works.md).

[^genieagent-home]: GenieAgent home page
[^genieagent-support]: GenieAgent support page
