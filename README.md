### Hi, I'm Volker.

I build tooling that lets coding agents work like a small team: issues in, reviewed PRs out, nothing merges until the tests pass on the merged code.

**[rota](https://github.com/l4ci/rota)** is the current project. One orchestrator agent hands GitHub or GitLab issues to worker agents on Claude Code and Codex, each in its own worktree, and a merge gate re-runs your suite on `main` after every merge. It keeps what it learns in the repo, so the next session starts where the last one stopped. rota built most of itself this way.

It is the third pass at the idea:

- [maestro](https://github.com/l4ci/maestro) (2026) ran issues through a human-in-the-loop lifecycle as a stateless daemon
- [hv-skills](https://github.com/l4ci/hv-skills) moved the workflow into agent skills so it could run inside the agent instead of beside it
- rota merged both and added parallel workers, account balancing and the gate

Also here: [skills](https://github.com/l4ci/skills), sixty thinking and analysis frameworks packaged as model-agnostic agent skills, and [MocoCompanion](https://github.com/l4ci/MocoCompanion), a keyboard-driven macOS menu bar app for MOCO time tracking.

Eighteen years of building web platforms and e-commerce systems, now CTO at Digital Masters. Notes at [volkerotto.net](https://volkerotto.net).
