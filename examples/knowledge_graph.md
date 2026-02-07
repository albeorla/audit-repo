
🔥 Roasting rahulnyk/knowledge_graph

╭──────────────────────────────────────── Metrics ────────────────────────────────────────╮
│          Stars  2365                         Forks  413                                 │
│       Watchers  31                    Contributors  4                                   │
│    Open issues  19                         Commits  ~2 in past year                     │
│        Created  2023-10-22               Last push  2025-05-15                          │
│           Size  37374 KB                   License  none                                │
│       Releases  0                         Archived  False                               │
│         Health  28%                                                                     │
│                                                                                         │
│ Languages: Jupyter Notebook 90.4%, Python 9.6%                                          │
╰─────────────────────────────────────────────────────────────────────────────────────────╯

╭─────────────────────────────────── The Roast (opus) ────────────────────────────────────╮
│ The Numbers                                                                             │
│                                                                                         │
│ 2,365 stars for what amounts to a single Jupyter notebook is a testament to timing —    │
│ this landed right in the RAG hype wave. Four contributors, 20 total commits, and        │
│ essentially zero activity in the past year tell you this was a weekend project that     │
│ caught lightning in a bottle, not a maintained tool. The 19 open issues with nobody     │
│ home confirms it.                                                                       │
│                                                                                         │
│ Red Flags                                                                               │
│                                                                                         │
│ No license. 2,365 people starred a repo they technically can't legally use. The README  │
│ coins "GRAG" (Graph Retrieval Augmented Generation) like it's an established technique  │
│ — it's not, it's a term the author made up in this README. "Convert any text to a graph │
│ of knowledge" is doing Olympic-level heavy lifting when the actual scope is "run one    │
│ notebook on one PDF with one specific local model." The poetry.lock is 4,300+ lines for │
│ a project whose actual logic fits in a single notebook cell.                            │
│                                                                                         │
│ What It Actually Is                                                                     │
│                                                                                         │
│ A Jupyter notebook that chunks a PDF, sends each chunk to a local Mistral model (via    │
│ Ollama) to extract concept pairs, then builds a NetworkX graph and visualizes it with   │
│ pyvis. The "knowledge graph" is really a co-occurrence concept map with no schema, no   │
│ persistence, no query engine, and no actual graph database. It's a neat demo of         │
│ LLM-assisted text-to-graph extraction, not a tool.                                      │
│                                                                                         │
│ Verdict                                                                                 │
│                                                                                         │
│ A well-timed napkin sketch that got 2,365 stars by riding the RAG hype cycle — useful   │
│ as inspiration, dangerous if you mistake it for infrastructure.                         │
╰─────────────────────────────────────────────────────────────────────────────────────────╯
🔥 Roasted.

