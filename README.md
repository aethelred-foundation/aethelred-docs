<h1 align="center">Aethelred Documentation</h1>

<p align="center">
  <strong>Official documentation for the Aethelred sovereign L1 blockchain</strong>
</p>

<p align="center">
  <a href="https://docs.aethelred.io"><img src="https://img.shields.io/badge/live_docs-docs.aethelred.io-orange?style=flat-square" alt="Live Docs"></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-Apache--2.0-blue?style=flat-square" alt="License"></a>
</p>

---

## Documentation Index

| Document | Description |
|---|---|
| [Developer Quickstart](DEVELOPER_QUICKSTART.md) | Get a local node running in 10 minutes |
| [Architecture](architecture.md) | System architecture deep-dive |
| [API Reference](API_REFERENCE.md) | Full REST + gRPC + WebSocket API |
| [SDK Guide](SDK_GUIDE.md) | Using the TypeScript, Python, Go, and Rust SDKs |
| [Validator Runbook](VALIDATOR_RUNBOOK.md) | Running a production validator node |
| [Cosmos Node](cosmos-node.md) | Cosmos SDK specifics |

---

## Sections

```
docs/
├── architecture.md          # System architecture
├── API_REFERENCE.md         # REST / gRPC / WS API reference
├── DEVELOPER_QUICKSTART.md  # Get started in 10 minutes
├── SDK_GUIDE.md             # SDK usage guide
├── VALIDATOR_RUNBOOK.md     # Validator operations
├── AIPs/                    # Aethelred Improvement Proposals (mirrored)
├── api/                     # Detailed API schemas
├── architecture/            # Architecture diagrams
├── cryptography/            # Cryptography specifications
├── governance/              # Governance process
├── guides/                  # Step-by-step guides
├── operations/              # Node operations
├── audits/                  # Security audit reports
└── appendices/              # Reference material
```

---

## Contributing to Docs

Found an error or want to improve the docs?

1. Fork this repo
2. Edit the relevant `.md` file
3. Open a PR — docs PRs are reviewed within 48 hours

For major doc changes or new sections, please open an [issue](https://github.com/AethelredFoundation/aethelred-docs/issues) first.

---

## Live Site

Docs are deployed automatically on every push to `main` via GitHub Pages / Vercel.

Live: **[docs.aethelred.io](https://docs.aethelred.io)**
