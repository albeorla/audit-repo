
🔥 Roasting KeygraphHQ/shannon

╭──────────────────────────────────────── Metrics ────────────────────────────────────────╮
│          Stars  8145                         Forks  1104                                │
│       Watchers  65                    Contributors  4                                   │
│    Open issues  14                         Commits  ~116 in past year                   │
│        Created  2025-09-27               Last push  2026-01-28                          │
│           Size  60235 KB                   License  AGPL-3.0                            │
│       Releases  0                         Archived  False                               │
│         Health  37%                                                                     │
│                                                                                         │
│ Languages: TypeScript 89.2%, JavaScript 5.7%, Shell 3.5%, Dockerfile 1.6%               │
│ Topics: penetration-testing, pentesting, security-audit, security-automation,           │
│ security-tools                                                                          │
╰─────────────────────────────────────────────────────────────────────────────────────────╯

╭─────────────────────────────────── The Roast (opus) ────────────────────────────────────╮
│ The Numbers                                                                             │
│                                                                                         │
│ 8K stars in 133 days with only 4 contributors and 116 commits is a classic "launch on   │
│ Hacker News, ride the wave" trajectory. The 37% community health score and zero         │
│ releases tell you this is a marketing-first project — the star count is doing the heavy │
│ lifting while the engineering fundamentals lag behind. One person (ajmallesh) authored  │
│ 17 of the recent 49 commits, so this is effectively a solo project wearing a team       │
│ jersey.                                                                                 │
│                                                                                         │
│ Red Flags                                                                               │
│                                                                                         │
│ The README is a masterclass in startup copy disguised as documentation — "the Red Team  │
│ to your vibe-coding Blue team" and "every Claude deserves their Shannon" are marketing  │
│ slogans, not technical descriptions. The 96.15% benchmark claim is plastered everywhere │
│ but runs against their own benchmark results stored in the repo, which is like grading  │
│ your own homework. The AGPL-3.0 license with a commercial "Pro" upsell, the "Rippling   │
│ for Cybersecurity" positioning, and the compliance platform pitch buried in the README  │
│ confirm this is a lead-gen funnel with an open-source wrapper. Also: 14 open issues, no │
│ releases, no tags — users are running raw main for a security tool.                     │
│                                                                                         │
│ What It Actually Is                                                                     │
│                                                                                         │
│ A TypeScript CLI that points Claude (via API) at a running web app's source code,       │
│ generates attack strategies from prompt templates, then uses a browser automation layer │
│ to attempt common OWASP exploits (SQLi, XSS, SSRF, auth bypass). It shells out to real  │
│ recon tools like Nmap and Subfinder for discovery, parallelizes the exploitation phase, │
│ and produces a markdown report. It's essentially an LLM-orchestrated wrapper around     │
│ established security tooling with a Playwright browser — clever glue code, not a novel  │
│ security engine.                                                                        │
│                                                                                         │
│ Verdict                                                                                 │
│                                                                                         │
│ A polished marketing funnel for a compliance startup that happens to ship a             │
│ useful-if-unversioned Claude-powered pentesting script — treat the benchmark claims     │
│ like you'd treat any vendor scoring themselves.                                         │
╰─────────────────────────────────────────────────────────────────────────────────────────╯
🔥 Roasted.

