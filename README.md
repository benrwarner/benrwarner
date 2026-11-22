### Hi, I'm Ben 👋

I build AI tooling and self-hosted platforms, and I want to put them to work on the energy transition.

I'm a fourth-year Computer Science student at [Ontario Tech University](https://ontariotechu.ca), based near Toronto. I've done two co-op terms at **Ontario Power Generation**, one of North America's largest clean-energy utilities. I like building systems that are grounded, deterministic and easy to run for a long time.

[ben-warner.dev](https://ben-warner.dev) · [LinkedIn](https://www.linkedin.com/in/ben-warner-565597257)

---

#### What I've been doing

- **OPG, Software / AI co-op (2026):** built **OPGKit Studio**, an AI backlog generator with a deterministic effort estimator. Tickets are generated with Azure AI Foundry and stored as SQL vectors. Effort is estimated by matching new tickets to the team's past estimates by cosine distance, so the numbers come from the team's own history and not from model guesses.
- **OPG, Data & Digital Modernization co-op (2025):** built Power BI dashboards for maintenance teams at Darlington Nuclear and helped stand up the Nucleus modernization platform. Placed **2nd in the Microsoft Copilot Hackathon** at Microsoft Canada HQ.
- **Self-hosted platform lab:** a multi-node lab (Mac Mini, Raspberry Pis, Ubuntu servers) on a Tailscale mesh. A k3s cluster syncs from GitHub through Argo CD and is published through Cloudflare Tunnels, with no inbound ports open. It also runs local LLM inference and Malcolm, a voice assistant that runs entirely on local hardware.
- **Embedded:** ESP32 firmware for a closed-loop greenhouse controller and a from-scratch Go-To telescope mount (LX200, RA/Dec → alt/az → steps).

#### Projects

| | |
|---|---|
| [**ohno**](https://github.com/benrwarner/ohno) | A flight recorder for your codebase. It takes automatic snapshots of uncommitted work, so you can undo instantly when an AI agent (or you) wrecks it. [`npm`](https://www.npmjs.com/package/@benwarner/ohno) |
| [**clogo**](https://github.com/benrwarner/clogo) | A Claude Code plugin so your coding agent designs a real logo, not a letter in a square. It makes SVG logos, favicons and app icons. |
| [**wemake**](https://github.com/benrwarner/wemake) | A realtime collaborative music studio in the browser. It's self-hosted on a Raspberry Pi as a GHCR image. [Live ↗](https://wemake.ben-warner.dev) |
| [**ben-warner**](https://github.com/benrwarner/ben-warner) | My résumé site: one static page with no framework. |

#### Toolbox

**Platform:** Kubernetes (k3s) · Argo CD / GitOps · Docker · Cloudflare Workers & Tunnels · Tailscale · Nginx · Linux · Azure AI Foundry · GCP · Supabase<br>
**AI:** MCP / FastMCP · RAG · vector search · BM25 · constrained decoding · agent loops · evals · Ollama · Claude & OpenAI APIs<br>
**Languages:** Python · TypeScript · JavaScript · SQL · C/C++ · Java<br>
**Frameworks:** Next.js · React · Angular · FastAPI · Node.js · Postgres · Power BI

---

I'm looking for roles in software, AI and platform engineering, especially in energy. Feel free to reach out.
