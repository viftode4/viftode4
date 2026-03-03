<div align="center">
<h3>Vlad George Iftode</h3>
<p>MSc Data Science & AI, TU Delft · Delft, NL</p>

<a href="https://linkedin.com/in/viftode4"><img src="https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" /></a>&ensp;
<a href="https://pypi.org/project/trustchain-py/"><img src="https://img.shields.io/pypi/v/trustchain-py?label=PyPI&logo=python&logoColor=white" /></a>&ensp;
<a href="https://github.com/viftode4/trustchain"><img src="https://img.shields.io/github/stars/viftode4/trustchain?style=flat&logo=github" /></a>
</div>

<br />

## TrustChain

**Decentralized trust infrastructure for the AI agent economy.**

Every agent protocol handles communication. None handle trust. TrustChain is the missing layer — bilateral signed interaction records with Sybil-resistant trust scoring via NetFlow. One decorator, zero config:

```python
pip install trustchain-py

from trustchain import with_trust

@with_trust(name="my-agent")
def main():
    ...  # All HTTP calls are now trust-protected
```

Built on the [TrustChain protocol](https://doi.org/10.1016/j.future.2020.01.031) from TU Delft (Otte, de Vos, Pouwelse). Extended with NetFlow trust computation. [IETF draft filed](https://datatracker.ietf.org/doc/draft-viftode-trustchain-trust/). [NIST CAISI RFI submitted](https://www.regulations.gov/docket/NIST-2025-0035).

| Repo | What | Tests |
|------|------|-------|
| **[trustchain](https://github.com/viftode4/trustchain)** | Rust core — QUIC P2P, HTTP proxy, dashboard, MCP server | 280 |
| **[trustchain-py](https://github.com/viftode4/trustchain-py)** | Python SDK — `@with_trust`, CLI, LangChain/FastAPI/MCP/CrewAI integrations | 311 |
| **[trustchain-js](https://github.com/viftode4/trustchain-js)** | TypeScript SDK — zero-dep client, OpenClaw plugin | 126 |
| **[trustchain-agent-os](https://github.com/viftode4/trustchain-agent-os)** | 12 framework adapters (LangGraph → LlamaIndex), MCP gateway | 205 |

<br />

## Other Projects

- **[hackaton-dublin](https://github.com/viftode4/hackaton-dublin)** — Skyly: 3D data center feasibility across Earth/Moon/Mars. React, Three.js, Rust, Solana, Claude AI. HackEurope Dublin 2026
- **[haxbet](https://github.com/viftode4/haxbet)** — Stock market for hackathon ideas. 130 concurrent users, bonding curve pricing. HackEurope Dublin 2026
- **[jqlang/jq](https://github.com/jqlang/jq)** — Contributor to the command-line JSON processor (33k+ stars)
