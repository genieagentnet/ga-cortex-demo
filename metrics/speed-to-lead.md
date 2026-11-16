---
type: Metric
title: Speed to lead
description: "The response-time measures the service is designed to hit: calls answered in under a second, follow-up within seconds, first human response to support requests within one business day."
resource: https://genieagent.net/
tags: [metric, response-time, conversion]
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

# Measures

1. Call answer time: under 1 second, 24 hours a day, by the [Voice Agent](/services/voice-agent.md).[^genieagent-home]
2. Lead follow-up: instant SMS and email follow-up within seconds of capture, by [Lead Capture + CRM](/services/lead-capture-crm.md).
3. Support first response: within one business day for standard requests, during support hours of Monday to Friday, 9:00 a.m. to 6:00 p.m. Eastern.[^genieagent-support]

These measures are the operating expression of the
[Answer every call](/decisions/answer-every-call.md) decision, and they are
reviewed monthly in the Optimize step of
[How it works](/process/how-it-works.md).

[^genieagent-home]: GenieAgent home page
[^genieagent-support]: GenieAgent support page
