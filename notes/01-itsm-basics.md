# 01 — ITSM Basics

## Core record types

| Type | What it is | Typical first-line action |
|------|------------|---------------------------|
| **Incident** | Unplanned interruption or reduction in quality of a service | Restore service as quickly as possible |
| **Service request** | Formal request for something standard (access, info, equipment) | Fulfil via defined process / catalogue |
| **Problem** | Underlying cause of one or more incidents | Log and link; usually not solved at L1 |
| **Change** | Addition, modification or removal of something that could affect services | Raise / route; do not implement ad-hoc |

## Why the distinction matters

- Wrong type → wrong workflow, wrong SLA, wrong owner
- Treating a request as an incident inflates incident metrics
- Treating a major incident as a normal ticket delays escalation

## Quick test

- "Something is broken or degraded" → Incident
- "I need something that is offered as standard" → Service request
- "We keep seeing the same incident" → Problem (link incidents)
- "We need to change a system in a controlled way" → Change
