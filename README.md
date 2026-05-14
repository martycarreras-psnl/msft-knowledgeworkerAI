# The Microsoft AI Constellation

> An integrated constellation — not a single tool.

An interactive, single-page visualization of how Microsoft's AI portfolio comes together for the knowledge worker — from quick chat to full agentic orchestration, all under one identity and governance plane.

Every employee experiences AI differently. This site is designed to meet each persona where they are and show how Microsoft's AI capabilities light up across their journey.

## What's inside

- **6 personas** — every kind of worker, every comfort level
- **20+ capabilities** — chat through Foundry through governance
- **1,300+ connectors** — Power Platform + MCP + custom extensions
- **One control plane** — Agent365 governs every agent, even non‑Microsoft

The visualization is organized around three intelligence layers:

| Layer | Role |
|-------|------|
| **Work IQ** | Role & people‑aware inference — mail, meetings, files. Gives every agent durable memory of who you are. Powers M365 Copilot, Cowork, AI Teammates. |
| **Foundry IQ** | Unified grounding endpoint, model routing, task dispatch. Aggregates Work IQ + Fabric IQ + apps + web. Powers Azure AI Foundry and all agent grounding. |
| **Fabric IQ** | Semantic intelligence layer — ontology and graph reasoning. Transforms the data estate into business meaning for agents. Powers Fabric Data Agents, Analyst, Foundry. |

All of it sits inside the **Agent365** governance and identity control plane — Entra Agent IDs, DLP, data labels, Purview, Defender, OpenTelemetry, and cross‑platform governance.

## Running it

This is a single static HTML file. No build, no dependencies.

```bash
# Just open it
open index.html

# Or serve locally
python3 -m http.server 8000
# then visit http://localhost:8000
```

## How to use

1. **Pick a persona** at the top — the constellation lights up the path that's most relevant to them.
2. **Click any star** (capability) to open its detail panel.
3. **Click an IQ layer** at the bottom to drill into Work IQ, Foundry IQ, or Fabric IQ.
4. **Click the Agent365 pill** at the top to explore the governance control plane.

## Project structure

```
.
├── index.html        # The entire experience (HTML + CSS + JS inline)
├── files/            # Supporting assets
├── README.md
├── LICENSE
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
└── SECURITY.md
```

## Contributing

Contributions, ideas, and corrections are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md) and our [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md).

## Security

Please report security issues per the process in [SECURITY.md](SECURITY.md). Do not file public GitHub issues for security vulnerabilities.

## License

Released under the [MIT License](LICENSE).

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft trademarks or logos is subject to and must follow [Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/legal/intellectualproperty/trademarks/usage/general). Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship. Any use of third‑party trademarks or logos is subject to those third‑parties' policies.
