# Claude Code workflow

- Keep Opus as the lead for planning, architectural decisions, complex reasoning, and final review.
- Before implementation, Opus makes a short plan, then delegates one clearly bounded, low-risk implementation task with explicit scope and acceptance criteria to the `pekerja` Haiku subagent.
- Opus reviews the subagent's changes and reported checks independently, runs any necessary validation, and handles integration or corrections. Keep heavy, cross-cutting, ambiguous, and high-risk work on Opus.
