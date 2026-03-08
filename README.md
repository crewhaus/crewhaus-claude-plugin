# CrewHaus — Startup Validation for Claude Code

Score and validate business ideas right from your terminal. Built by [CrewHaus](https://www.crewhaus.ai?ref=claude-plugin), an AI-native startup validation service.

## Commands

| Command | What it does | Speed |
|---------|-------------|-------|
| `/crewhaus:score [idea]` | Quick 3-dimension viability score — problem, market, feasibility | ~15 sec |
| `/crewhaus:quickscan [idea]` | Deeper scan — target customer, risk assessment, competitive preview, verdict | ~1-2 min |

## Example Output

```
🎯 CREWHAUS IDEA SCORECARD
═══════════════════════════════════════

Idea: AI-powered meal planning based on dietary restrictions and local grocery deals

📊 Scores
  Problem Clarity:    8/10 — Meal planning with dietary constraints is a real daily pain point
  Market Opportunity: 7/10 — $4.2B meal kit market growing 12% YoY, adjacent opportunity
  Feasibility:        6/10 — Grocery API integrations are fragmented, cold start problem

  OVERALL: 7.0/10

⚡ Top Risk
  Grocery deal data requires partnerships with retailers — no public API exists at scale

🚀 One Next Step
  Interview 20 people with dietary restrictions about their weekly meal planning process
```

## Install

```bash
/plugin install crewhaus@claude-plugins-official
```

Or from GitHub:
```bash
/plugin install-from-github crewhaus/crewhaus-claude-plugin
```

## What's Free vs. Paid

| Free (this plugin) | Full Signal Check ([crewhaus.ai](https://www.crewhaus.ai?ref=claude-plugin)) |
|--------------------|---------------------------------|
| ✅ 3-Dimension Score | ✅ Everything free, plus: |
| ✅ Target Customer Analysis | 🔓 Full Market Sizing (TAM/SAM/SOM) |
| ✅ Risk Assessment (5 categories) | 🔓 Competitive Deep Dive with moat analysis |
| ✅ Competitive Preview (top 3) | 🔓 Go-to-Market Playbook |
| ✅ Overall Verdict | 🔓 Multi-agent research with real data |

## About CrewHaus

CrewHaus is an AI crew that validates startup ideas. The free tools give a solid first read with real competitor data. For the full picture — market sizing, differentiation strategy, and actionable go-to-market playbooks — visit [crewhaus.ai](https://www.crewhaus.ai?ref=claude-plugin).

## License

MIT
