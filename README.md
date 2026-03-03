### Vlad George Iftode

MSc Data Science & AI at TU Delft, Netherlands.

## TrustChain

I'm building TrustChain, an open-source trust layer for AI agents. The idea: every agent-to-agent interaction creates a bilateral cryptographic record signed by both parties. Trust scores come from real interaction history, computed via max-flow network analysis so fake identities can't game the system.

It's based on the [TrustChain protocol](https://doi.org/10.1016/j.future.2020.01.031) from TU Delft (Otte, de Vos, Pouwelse). I extended it with NetFlow trust computation and filed an [IETF draft](https://datatracker.ietf.org/doc/draft-viftode-trustchain-trust/). Also submitted a response to the [NIST CAISI RFI](https://www.regulations.gov/docket/NIST-2025-0035) on AI agent security.

```python
pip install trustchain-py

from trustchain import with_trust

@with_trust(name="my-agent")
def main():
    ...  # all HTTP calls now go through the trust proxy
```

| Repo | What |
|------|------|
| [trustchain](https://github.com/viftode4/trustchain) | Rust core, QUIC P2P, HTTP proxy, dashboard, MCP server |
| [trustchain-py](https://github.com/viftode4/trustchain-py) | Python SDK, @with_trust decorator, CLI, framework integrations |
| [trustchain-js](https://github.com/viftode4/trustchain-js) | TypeScript SDK, OpenClaw plugin |
| [trustchain-agent-os](https://github.com/viftode4/trustchain-agent-os) | Adapters for 12 agent frameworks, MCP gateway |

## Other stuff

- [hackaton-dublin](https://github.com/viftode4/hackaton-dublin) - Skyly: 3D data center feasibility estimator for Earth/Moon/Mars. React, Three.js, Rust, Solana. HackEurope Dublin 2026
- [haxbet](https://github.com/viftode4/haxbet) - Stock market for hackathon ideas. Hit 130 concurrent users, patched live to fix botting. HackEurope Dublin 2026
- [partydrinks](https://github.com/viftode4/partydrinks) - OutDrink your friends. Live drink stats for parties
- [claude-usage-widget](https://github.com/viftode4/claude-usage-widget) - Track your Claude API usage
- [Spotify-Ranker](https://github.com/viftode4/Spotify-Ranker) - Rank Spotify albums against each other
- [Computer-Graphics-project](https://github.com/viftode4/Computer-Graphics-project) - C++ renderer, built for uni
- [Chess](https://github.com/viftode4/Chess) - Chess game in NodeJS
