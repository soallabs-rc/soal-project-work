# Product Management Plugin (Soal Labs)

Soal Labs' PM toolkit for client engagements. We build bespoke data and software for private equity and private credit firms in one-week sprints. This plugin helps the engagement lead write specs, brainstorm, plan and close sprints, keep the roadmap current, review metrics, and update client stakeholders.

It is built around **Linear** (one workspace per client), **Fireflies** (meeting transcripts, the main source of context), and **Slack**. Everything follows the Soal house style.

Company-wide context lives in [COMPANY.md](COMPANY.md). Every skill reads it first, so update it there.

## Installation

```
claude plugin marketplace add soallabs-rc/knowledge-work-plugins
claude plugin install product-management@knowledge-work-plugins
```

To pick up changes after editing this repo:

```
claude plugin marketplace update knowledge-work-plugins
```

## Commands

Type these in Claude Code, prefixed with `/product-management:`.

| Command | What it does |
|---|---|
| `write-spec` | Write a feature spec from a problem statement, client ask, or Fireflies call |
| `brainstorm` | Think through a product idea, problem, or approach with a sharp sparring partner |
| `sprint-planning` | Plan the coming one-week sprint for a client engagement |
| `sprint-closing` | Close the sprint: what shipped, what carried over, retro, and a client-ready summary |
| `stakeholder-update` | Write an update for client stakeholders or the internal team |
| `roadmap-update` | Update or reprioritize a client roadmap across Linear initiatives and projects |
| `metrics-review` | Review delivery and product metrics and turn them into actions |

## Files

```
product-management/
├── COMPANY.md        # Soal context, engagement rules, sources, house style (read first)
├── CONNECTORS.md     # Which tools map to which placeholders
├── .mcp.json         # Slack, Linear, Fireflies
├── commands/         # brainstorm
└── skills/           # write-spec, product-brainstorming, sprint-planning, sprint-closing,
                      # stakeholder-update, roadmap-update, metrics-review
```
