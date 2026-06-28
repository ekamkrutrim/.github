<p align="center">
  <img src="https://raw.githubusercontent.com/ekamkrutrim/ekam/main/assets/logo.png" alt="Krutrim Ekam" width="100" height="100">
</p>

<h1 align="center">Krutrim Ekam</h1>
<p align="center"><b>One identity for every principal — human or agent.</b></p>
<p align="center">The agent-identity &amp; delegation control plane for the Ola / Krutrim group.</p>

<p align="center">
  <a href="https://ekam.olakrutrim.com">🌐 Live</a> ·
  <a href="https://ekam.olakrutrim.com/docs">📘 Docs &amp; API</a> ·
  <a href="https://ekam.olakrutrim.com/cookbook">🍳 Cookbook</a> ·
  <a href="https://github.com/ekamkrutrim/ekam">💻 Samples</a>
</p>

---

**Ekam** (एकम् — "one") is an OAuth 2.1 / OIDC authorization server built for the agent era. It gives
every principal — a human who signs in or an agent that runs unattended — a single verifiable identity,
and brokers **short-lived, audience-bound, delegated tokens** that gateways and MCP servers verify offline.

- 🤝 **Human + agent parity** — every capability is a human UI *and* a JSON/MCP API
- 🔌 **Offline verify** — ES256 + JWKS, with a live kill-switch (introspection)
- 🔗 **Delegation that travels** — RFC 8693 token-exchange + ID-JAG / Cross-App Access
- 🧭 **MCP on-ramp** — RFC 9728 Protected Resource Metadata
- 🇮🇳 **Built for India** — Krutrim Cloud, DPDP-aligned, DR enabled

The identity layer underneath [BharatRouter](https://bharatrouter.com): Ekam issues the token,
BharatRouter verifies it, maps the agent to a budget, meters, and bills the owner.

<p align="center"><sub>© Krutrim SI Designs Private Limited · a Krutrim group company</sub></p>
