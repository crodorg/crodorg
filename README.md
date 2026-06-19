# Chris

I build terminal-native, self-hostable tools — mostly Rust, OpenBSD-first, no
cloud and no phone-home.

Everything here is personal work shared in the open — opinionated,
single-operator, built to run for years on hardware I control.

### Knowledge stack — three tools, one `~/wiki`

- **[plainbrain](https://github.com/crodorg/plainbrain)** — a memory and
  knowledge system for AI coding agents: markdown, git, three shell hooks. No
  database, no daemons, no vector store. Dumb substrate, smart runtime.
- **[recon](https://github.com/crodorg/recon)** — terminal deep-research engine.
  A dependency-light Rust binary owns retrieval, dedup, credibility scoring, and
  citation-verification; the reading and the cited write-up happen locally. Buy
  breadth, own synthesis.
- **[falsify](https://github.com/crodorg/falsify)** — theory-falsification
  engine. Decompose a source into falsifiable claims, audit them against the
  trust-tiered wiki, adversarially review, and persist source-pinned verdicts.
  The LLM proposes; Rust verifies and pins.

### Terminal tools

- **[arca](https://github.com/crodorg/arca)** — self-hosted personal-finance
  daemon for OpenBSD. One sandboxed Rust binary tracks debt, investments,
  recurring bills, API spend, and per-business P&L — read it from a vim-style TUI
  over a Unix socket, or message it over XMPP.
- **[fuga](https://github.com/crodorg/fuga)** — terminal-native music library
  aggregator. One TUI, one queue, many sources — local (MPD), radio, SomaFM,
  Spotify, YouTube — with inline album-art thumbnails in Kitty-graphics
  terminals.
- **[helm](https://github.com/crodorg/helm)** — let an AI agent and a human
  drive the same tmux session, local or ssh-remote, with the etiquette baked in
  so neither breaks the other. Plus read-only verbs for inspecting the fleet.

---

Mostly Rust · OpenBSD by default · suckless-minded · [crod.me](https://crod.me)
