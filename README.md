# Benjamin Zengler

**Berlin · ex-COO of Fyrfeed (acquired 2024) · founder at [ai1 Ventures](https://ai1ventures.com)**

I build **evidence-bounded AI systems**: agents that must cite their sources, pass eval gates in CI, and escalate to a human when they can't back a claim. Policy lives in code, not in prompts — a model can argue, but it can't talk its way past a verifier.

Right now that means a fully autonomous content pipeline shipping short-form video daily (research → script → render → schedule, built on Claude Code), an installable MCP server for running AI transformation programs, and the repos below.

## The repos, and why they exist

| | |
|---|---|
| **[ai-transformation-90](https://github.com/benmfzen/ai-transformation-90)** | A transformation copilot for the first 90 days of an AI program — playbook, costed business cases, working prototypes, and the method itself as an MCP server with evidence-gated scoring. Swap in your own org and it runs your program. |
| **[snakeoil-radar](https://github.com/benmfzen/snakeoil-radar)** | A reaction radar for viral health misinformation, as a Claude Code skill — finds high-reach claims, checks them against PubMed **fail-closed**, never asserts what it can't cite. |
| **[know-no-hearsay](https://github.com/benmfzen/know-no-hearsay)** | A reference architecture for evidence-bounded generative media — no pipeline step may increase the epistemic strength of a claim without evidence. |
| **[sorting-hat](https://github.com/benmfzen/sorting-hat)** | An LLM-classified document inbox: drop scans into one folder, get named, filed paperwork out. Boring, useful, runs daily on my machine. |
| **[inanimatus](https://github.com/benmfzen/inanimatus)** | LLM-driven CAD, done declaratively — geometry-tested CadQuery models from dimensioned specs, as a documented method + Claude Code skill. |

**The common thread: grounded beats plausible.** Every one of these rejects output it cannot back — with tests in CI to prove it.

📫 [LinkedIn](https://www.linkedin.com/in/zengler) · 🎬 the daily-shipping pipeline in action: [@dabigredbutton](https://www.tiktok.com/@dabigredbutton)
