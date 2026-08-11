## Dennis Rowe

Data and platform engineering at Omega Point. Austin, TX.

I spend my days in the unglamorous layer between a data platform and the people
using it — Databricks jobs, Airflow DAGs, risk-model pipelines — and most of what
I publish is tooling to make that layer legible from a terminal.

### What I build

Nearly everything here follows the same shape: **one CLI an agent can drive, and
one TUI a human can read.** The CLI is scriptable and composable so a coding
agent can call it without a browser; the TUI is for the five minutes when you
actually want to look at something.

- **[databricks-tools](https://github.com/shr3kst3r/databricks-tools)** — `dbtools` for jobs, runs, notebooks and Unity Catalog; `dbtui` to browse them read-only
- **[dev-tools](https://github.com/shr3kst3r/dev-tools)** — live terminal dashboards for GitHub PRs, Airflow, and Azure DevOps pipelines
- **[goblin-watcher](https://github.com/shr3kst3r/goblin-watcher)** — parallel coding agents in git worktrees: ticket → branch → worktree → session
- **[hc-cli](https://github.com/shr3kst3r/hc-cli)** — `hc` for Healthchecks.io: the full v3 management API, plus outgoing pings for whatever cron job you're babysitting
- **[spg](https://github.com/shr3kst3r/spg)** — per-project commands published to `~/bin`, with zsh completion from the same declarations

### How

Python on [uv](https://docs.astral.sh/uv/), [just](https://github.com/casey/just)
for tasks, [ty](https://github.com/astral-sh/ty) and
[ruff](https://docs.astral.sh/ruff/) keeping me honest, `asdf` pinning the
bootstrap CLIs. Heavy Claude Code user — the tools above mostly exist because
agents need a good CLI even more than humans do.

### Elsewhere

[LinkedIn](https://www.linkedin.com/in/dennisrowe/)
