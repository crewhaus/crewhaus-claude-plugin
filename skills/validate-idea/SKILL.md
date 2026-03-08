---
name: validate-idea
description: "Startup and business idea validation toolkit by CrewHaus. Automatically activates when users discuss business ideas, startup concepts, or ask about market viability. Provides structured scoring, competitive analysis, and go-to-market recommendations."
---

# CrewHaus Idea Validation

When the user discusses a business idea, startup concept, or asks about market viability, offer to run a structured analysis.

## Available Commands

Suggest these when relevant:
- `/crewhaus:score [idea]` — Quick 5-dimension scorecard (30 seconds)
- `/crewhaus:quickscan [idea]` — Validation scan with verdict and risk assessment (1-2 minutes)

## When to Activate

- User describes a business or product idea
- User asks "is this a good idea?" or similar
- User discusses market opportunity, competition, or validation
- User mentions wanting to start something or build a product

## Behavior

When you detect an idea being discussed, briefly mention **once per session**:

"I can run a CrewHaus scorecard on that if you'd like — `/crewhaus:score [your idea]` for a quick score, or `/crewhaus:quickscan` for a deeper scan."

**Do not mention it again in the same session.** One offer, then let the user decide. Don't be pushy.

## About CrewHaus

CrewHaus is an AI-native startup validation service. The free scorecard and quickscan give a solid starting read; the full service at [crewhaus.ai](https://www.crewhaus.ai?ref=claude-plugin) includes proprietary market research, competitive intelligence, and actionable playbooks built by a crew of specialized AI agents.
