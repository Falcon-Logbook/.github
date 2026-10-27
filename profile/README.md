# Falcon Logbook

Falcon is an open-source pilot logbook built around a simple idea: **your flight data belongs to you.** No forced subscriptions, no lock-in, no surprise fees when you want to leave.

## Where to find us

| What | Where |
| :--- | :--- |
| 🌐 **Website** | [falconlogbook.com](https://falconlogbook.com) - learn about Falcon, read the blog and more |
| 📖 **Docs** | [docs.falconlogbook.com](https://docs.falconlogbook.com) - how the app works, setup, and usage |

## Repos

**Public**

| Repo | Description |
| :--- | :--- |
| [`app`](https://github.com/Falcon-Logbook/app) | Cross-platform Flutter app for iOS, Android, and desktop |
| [`docs`](https://github.com/Falcon-Logbook/docs) | Documentation site built with Docusaurus |
| [`mcp`](https://github.com/Falcon-Logbook/mcp) | MCP server exposing Falcon logbook data to AI assistants |
| [`demo-database`](https://github.com/Falcon-Logbook/demo-database) | Demo data for anyone who wants to test Falcon with a sample logbook |

**Private**

| Repo | Description |
| :--- | :--- |
| `cloud` | Backend module for Falcon Cloud |
| `website` | Marketing site (source at [falconlogbook.com](https://falconlogbook.com)) |

### Monorepo layout

```
app/      Flutter app (public)
cloud/    Falcon Cloud module (private, added via path dependency)
website/  Marketing site (private)
docs/     Docusaurus documentation (public)
```

## Contributing

Contributions of all kinds are welcome:

- **Bug reports & ideas** - open an issue
- **Code, docs, or tests** - submit a PR
- **Review** - look over open PRs and leave feedback

## Goals

- Stay open-source, transparent, and community-driven
- Build the best pilot logbook without locking anyone into expensive subscriptions
- Keep infrastructure lean and privacy-first

---

*Open source, open skies.*
