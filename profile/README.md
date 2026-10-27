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
| [`demo-database`](https://github.com/Falcon-Logbook/demo-database) | Five years of sample flights for screenshots, docs and testing |

**Private**

| Repo | Description |
| :--- | :--- |
| `cloud` | Backend module for Falcon Cloud |
| `website` | Marketing site (source at [falconlogbook.com](https://falconlogbook.com)) |

### Demo data

`demo-database` is a complete Falcon logbook you can open in the app or point the MCP server
at. Five years of flying across nine aircraft types, with real airports, routes and aircraft
registrations, a fictional pilot and crew, and full expiries, currencies and dashboard settings.
It is there so screenshots, documentation and testing have real-looking data to work with.

### Repository map

```
app/            Flutter app (public)
docs/           Docusaurus documentation (public)
mcp/            MCP server (public)
demo-database/  Sample logbook data (public)
cloud/          Falcon Cloud module (private, added via path dependency)
website/        Marketing site (private)
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
