# Connectors

## How tool references work

Skill files use `~~category` placeholders for tools. At Soal Labs they map to the tools below. See [COMPANY.md](COMPANY.md) for how we use each one.

## Connectors for this plugin

| Category | Placeholder | Soal tool | Notes |
|----------|-------------|-----------|-------|
| Project tracker | `~~project tracker` | Linear | One workspace per client. Initiatives, projects, cycles, labels, priorities, docs. |
| Meeting transcription | `~~meeting transcription` | Fireflies | Most important context source. Client calls, standups, working sessions. |
| Chat | `~~chat` | Slack | Team and engagement channels. Decisions and shared docs. |
| Knowledge base | `~~knowledge base` | Linear docs, Claude artifacts, Slack | No separate wiki. |
| Calendar, email, product analytics, design, user feedback | `~~calendar`, `~~email`, `~~product analytics`, `~~design`, `~~user feedback` | Not connected | Ask the user, or work from what they paste or upload. |

Each client has its own Linear workspace. If the Linear connector only reaches one workspace at a time, confirm with the user which client workspace is connected before reading or writing anything.
