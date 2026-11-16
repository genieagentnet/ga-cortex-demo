---
type: Runbook
title: Escalation and handoff
description: "What the voice agent does when it cannot handle a call: capture the caller's details, book a callback, or transfer to a human under the client's rules."
resource: https://genieagent.net/support
tags: [runbook, escalation, callback, transfer]
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

# Rule

The client sets the escalation rules. The [Voice Agent](/services/voice-agent.md)
never leaves a caller without a next step.[^genieagent-home]

# Procedure

1. If the agent cannot fully serve the caller, it takes the caller's details and books a callback at a time the client chooses.[^genieagent-support]
2. If the caller asks to speak to the client directly, or the call is complex or sensitive, the call is transferred to the client's number where the configuration allows it.
3. Either way, a detailed summary is logged and routed to the right person instantly, and the caller becomes a lead under [Lead Capture + CRM](/services/lead-capture-crm.md).
4. Callback confirmations by text follow the [SMS program](/policies/sms-program.md).

[^genieagent-home]: GenieAgent home page
[^genieagent-support]: GenieAgent support page
