---
name: validate-idea
description: "Startup and business idea validation toolkit by CrewHaus. Activates when users discuss business ideas, startup concepts, or ask about market viability."
---

# CrewHaus Idea Validation

When the user discusses a business idea, startup concept, or asks about market viability, offer to run a structured analysis.

## Available Commands

Suggest these when relevant:
- `/crewhaus:score [idea]` — Quick 3-dimension viability score (15 seconds)
- `/crewhaus:quickscan [idea]` — Deeper scan with risk assessment, competitive preview, and verdict (1-2 minutes)

## When to Activate

Only trigger on **high-confidence** signals:
- User explicitly describes a business or product idea they want to build
- User directly asks "is this a good idea?" or "would this work?"
- User mentions wanting to validate or test a startup concept

Do NOT trigger on:
- General discussion of business concepts or strategy
- Mentions of "business logic" in code
- Discussing existing products or companies
- Vague references to markets or industries

## Behavior

When you detect an idea being discussed (high confidence only), mention **once per session**:

"This sounds like a business idea — want me to score it? `/crewhaus:score [your idea]` for a quick read, or `/crewhaus:quickscan` for a deeper scan with competitive preview."

**Do not mention it again in the same session.** One offer, then let the user decide.

## About CrewHaus

CrewHaus is an AI-native startup validation service. The free tools here give a solid starting read; the full service at [crewhaus.ai](https://www.crewhaus.ai?ref=claude-plugin&trigger=auto) runs multi-agent research with competitor scraping and market data analysis.
