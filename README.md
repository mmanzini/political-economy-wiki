# Political Economy

Macro-level commentary, analysis, and reporting on the political and economic forces shaping the world in 2026 — geopolitics (Middle East, Trump doctrine, Pakistan, China, Europe), energy and commodity markets, financial systems (US equities, global crypto, underground banking), the AI industry as a *market and political force* (not as a building practice), and the social/historical/religious threads woven through them (US religion-and-politics, colonial history and memory, refugee crises, digital privacy as a regulatory question). Belongs here: anything where the unit of analysis is a country, a market, an industry, a political movement, or a historical force. Does **not** belong here: how-to material on *building with* AI (that goes to `ai-engineering`) or repo-level writeups of trending AI tooling (that goes to `github-trends`). The AI-industry topic here covers the macro/geopolitical view; the agent-tooling view lives elsewhere.

This repository is a public mirror of one bucket from a personal Obsidian RAG vault (Atlas). Articles are distilled from primary sources — talks, papers, reporting, essays, podcasts, original analysis — into concise, cross-linked notes with inline source citations. It currently holds **71 articles across 18 topics**.

## Topics

- [Middle East Conflict 2026](middle-east-conflict-2026/) — Ongoing war; Trump ultimatum/ceasefire drama; Islamabad talks; Iran nuclear standoff; Israel-Lebanon front
- [Hormuz Strait Crisis](hormuz-strait-crisis/) — Iran's blockade of the strait, toll system, shipping collapse
- [Energy Markets 2026](energy-markets-2026/) — Oil prices, LNG crisis, global supply disruption; $95 futures vs $130 physical
- [Asian Economic Crisis](asian-economic-crisis/) — Energy rationing, food/fertiliser crisis, country-by-country impacts across Asia
- [US Markets and Economy](us-markets-and-economy/) — Equities, macro data, inflation, Fed expectations; Q1 earnings; tech rally; natality crisis
- [AI Industry](ai-industry/) — Anthropic Mitos, Economic Index, Meta/OpenAI investments, DeepSeek; Silicon Valley split over military AI
- [AI Geopolitics and Risks](ai-geopolitics-and-risks/) — Transformative potential, civilisational risks, export controls, AI-enabled authoritarianism; nuclear wargaming study
- [European Economy](european-economy/) — Stagflation risk, Italy; Magyar cabinet + €90B Ukraine loan; Bulgaria Radev elected; EU military Hormuz mission; demographics 2100; Sánchez progressive summit; Nazi database
- [Global Finance and Crypto](global-finance-and-crypto/) — Underground banking (Hawala, Fei Qian), cryptocurrency critique, cyber-libertarianism; Polymarket hyperreality and insider trading
- [Bhutan Refugee Crisis](bhutan-refugee-crisis/) — Ethnic cleansing of the Lhotshampa, statelessness, US deportation loop, state Bitcoin mining
- [China Domestic Economy](china-domestic-economy/) — Rural pensions crisis, urban-rural inequality, "Common Prosperity" rhetoric vs. reality, medical tourism as global hospital
- [China Political System](china-political-system/) — Socialist consultative democracy, the eight minor parties, United Front, hierarchical electoral system, whole-process democracy doctrine
- [Digital Privacy and Cybersecurity](digital-privacy-and-cybersecurity/) — Vastaamo data breach, uberisation of healthcare, EU AI Act enforcement, data sovereignty gap, Trump offensive cyber strategy
- [Trump Doctrine and Geopolitics](trump-doctrine-and-geopolitics/) — Predatory world order, Venezuela blitz, Machiavelli vs Sun Tzu, Xi Jinping's strategic patience; Trump-China trade war and rare earth retaliation; NATO 5% demand and European strategic autonomy
- [US Religion and Politics](us-religion-and-politics/) — MAGA as new religious movement, Commission on Religious Freedom, Charlie Kirk funeral (grace vs sword), Castellio vs Calvin; USCIRF 2026 and Trump policy tensions; Meloni/Salvini European Christian nationalism
- [Pakistan Security State](pakistan-security-state/) — Kamran's framework; military-rule history (Ayub → Zia → Musharraf → Imran Khan); Munir-Trump axis and Pakistan's 2026 mediator role
- [Colonial History and Memory](colonial-history-and-memory/) — Africa's central role in the global anti-fascist war; Thiaroye massacre; Ethiopian Arbegnoch resistance and women's shadow networks; Congolese uranium; survival of colonial logic past 1945; decolonising historical memory
- [Asia-Pacific Geopolitics](asia-pacific-geopolitics/) — Japan, Taiwan, Korean Peninsula, ASEAN-region security dynamics; Japan's 2026 intelligence reform (National Intelligence Bureau + NIC), Tokkō historical stigma, rearmament trajectory, and China's Taiwan calculus

## How this repository is structured (Open Knowledge Format)

This repository is a conformant [**Open Knowledge Format (OKF) v0.1**](https://github.com/GoogleCloudPlatform/knowledge-catalog/blob/main/okf/SPEC.md) bundle. OKF is Google Cloud's vendor-neutral standard for agent-readable knowledge: a directory of markdown files, one concept per file, with YAML frontmatter and cross-links. No SDK, no database, no proprietary account — if you can `cat` a file you can read it; if you can `git clone` the repo you can ship it.

A bucket of the parent vault *is* an OKF bundle in place — there is no separate export step. What that means here:

- **`index.md` routers** — `index.md` at the bundle root and in every topic folder is a directory listing for progressive disclosure: scan it to see what exists before opening articles.
- **`<concept>.md` articles** — every other `.md` file is a concept document. Each opens with YAML frontmatter whose only required field is `type` (Atlas uses a small vocabulary: `synthesis`, `reference`, `analysis`, `digest`, …), followed by `title`, `description`, `tags`, `source`, `timestamp`, and a `related:` cross-link graph.
- **`log.md`** — a derived, date-grouped changelog of what changed at this level.
- **Conformance** — every non-reserved `.md` file carries parseable frontmatter with a non-empty `type`; `index.md` / `log.md` are the only reserved filenames. Consumers tolerate unknown types and broken links by design, so the bundle stays useful as it grows.

Because the format is just files, this repo is readable in any editor, renderable on GitHub, parseable by any agent, and portable across tools with no translation layer.

## Method

Sources pass through a structured `consolidate` pass — each article cites its source files inline, and contradictions between sources are surfaced rather than smoothed over. A separate `refine` pass audits the bundle for orphans, broken links, and OKF/schema violations. The full method lives in the parent vault and is not published here.

## Updates

This repository syncs from the parent vault on a schedule; content is added or revised whenever the upstream notes change. The change history is visible in the commit log and in any `log.md` files.

---

<sub>README generated from Atlas (`okf_tools.py --readme political-economy`) — do not edit by hand; edit the bucket's `index.md` or the shared OKF section in the generator.</sub>
