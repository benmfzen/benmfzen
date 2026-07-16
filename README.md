# Benjamin Zengler

**Berlin · ex-COO of Fyrfeed (acquired 2024) · founder at [ai1 Ventures](https://ai1ventures.com)**

Right now: a fully autonomous content pipeline shipping short-form video daily (research →
script → render → schedule, built on Claude Code), an installable MCP server for running AI
transformation programs, and the repos below — each one built to demonstrate the same thing a
different way.

The pattern across all of them: **agents that must cite their sources, pass tests in CI, and
refuse rather than guess when they can't back a claim.** That's not a slogan restated per repo —
it's what the numbers below are.

## The repos, and why they exist

| | |
|---|---|
| **[postpeer-pilot](https://github.com/benmfzen/postpeer-pilot)** | A performance-driven publishing autopilot for short-form video, as an MCP server. 16 reliability/invariant tests, a measured 18/18 agent-eval suite (incl. 9/9 unsafe-action refusals — the agent tried to schedule live, the tool layer refused), and a backtest that reports honestly where its own conservative design *costs* performance, not just where it wins. |
| **[meta-youtube-comment-mcp](https://github.com/benmfzen/meta-youtube-comment-mcp)** | Human-in-the-loop comment automation for Instagram, Facebook & YouTube. 47 deterministic tests, a written threat model, an eval harness that measures classifier + routing accuracy on labeled data — not just vibes. |
| **[ai-transformation-90](https://github.com/benmfzen/ai-transformation-90)** | A transformation copilot for the first 90 days of an AI program — playbook, costed business cases, working prototypes, and the method itself as an MCP server with evidence-gated scoring. Swap in your own org and it runs your program. |
| **[know-no-hearsay](https://github.com/benmfzen/know-no-hearsay)** | A reference architecture for evidence-bounded generative media: no pipeline step may increase the epistemic strength of a claim without evidence. **[snakeoil-radar](https://github.com/benmfzen/snakeoil-radar)** (finds viral health-misinformation claims on TikTok, checks them against PubMed) and **[cited-cuts](https://github.com/benmfzen/cited-cuts)** (turns a found claim into a quote-bounded rebuttal video) are two applications of it. |
| **[sorting-hat](https://github.com/benmfzen/sorting-hat)** | An LLM-classified document inbox: drop scans into one folder, get named, filed paperwork out. Boring, useful, runs daily on my machine. |
| **[inanimatus](https://github.com/benmfzen/inanimatus)** | LLM-driven CAD, done declaratively — geometry-tested CadQuery models from dimensioned specs, as a documented method + Claude Code skill. |

📫 [LinkedIn](https://www.linkedin.com/in/zengler) · 🎬 the daily-shipping pipeline in action: [@dabigredbutton](https://www.tiktok.com/@dabigredbutton)
