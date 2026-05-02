## Main Objective

Build a video rental system across 8 sequential stages, evolving across technologies and paradigms:

- Procedural → Structured → Event-driven → Separation of concerns → Explicit control → Layered architecture → Web monolith → Distributed system → Mobile/reutilization
- Physical rental → Digital access with capacity constraints

# Goals This project has two equally important goals:

* Dev Skills — Rebuild and deepen fluency across stacks, architectures, and paradigms. From DOS-era procedural to modern distributed systems. Special focus on Python, JavaScript/frontend concepts, and Ruby on Rails (production stacks used by the learner's teams).
* AI Skills — Learn to work with Claude Code in a spec-driven workflow. Use AI as a controlled accelerator, not a replacement for thinking. Practice prompt discipline, context management, and AI-assisted code review and testing.
Execution Model

# Work one stage at a time
* Fully complete a stage before starting the next
* Each stage has its own spec set, its own repo, its own Jira space
* Specs must be rewritten per stage — not copied
* No future-stage concepts allowed in any stage


## Stage Repositories

| Stage | Repo | Stack |
|-------|------|-------|
| 1 | [vc-stage1-clipper](https://github.com/scaledVideoClub/vc-stage1-clipper) | Clipper 5.2 |
| 2 | [vc-stage2-vb6](https://github.com/scaledVideoClub/vc-stage2-vb6) | Visual Basic 6 |
| 3 | [vc-stage3-delphi](https://github.com/scaledVideoClub/vc-stage3-delphi) | Delphi |
| 4 | [vc-stage4-cppbuilder](https://github.com/scaledVideoClub/vc-stage4-cppbuilder) | C++Builder |
| 5 | [vc-stage5-csharp](https://github.com/scaledVideoClub/vc-stage5-csharp) | C# WPF |
| 6 | [vc-stage6-rails](https://github.com/scaledVideoClub/vc-stage6-rails) | Ruby on Rails |
| 7 | [vc-stage7-python](https://github.com/scaledVideoClub/vc-stage7-python) | Python + React |


## Development Practice Progression

Each stage deliberately mirrors the development culture of its era.
This is intentional — do not apply modern practices to early stages.

The four key disciplines evolve incrementally across stages:

| Stage | Spec-Driven | Testing | Code Review | Docs & Jira |
|-------|------------|---------|-------------|-------------|
| 1 — Clipper | Prose notes before coding | Manual, after implementation | None | Physical notebook equivalent |
| 2 — VB6 | Written functional spec | Manual test plan, post-impl | Self-review checklist | Loose Jira, basic PRs |
| 3 — Delphi | Full spec, section sign-off | Manual, edge cases pre-defined | Claude CR skill (informal) | Jira linked to PRs |
| 4 — C++Builder | Spec + acceptance criteria | Unit tests alongside code | Claude CR, findings must be resolved | Full Jira hierarchy |
| 5 — C# WPF | Interface contracts in spec | TDD starts here | Claude CR blocking | PR template enforced |
| 6 — Rails | BDD acceptance scenarios | Full TDD, CI-gated | Claude Code CLI | Commit IDs in Jira |
| 7 — Python+React | API-first, OpenAPI spec | TDD + E2E, CI blocking | Automated linting + CR | Full story mapping |

### Why this matters

If you are reviewing code or specs for a given stage, apply only the practices
defined for that stage. Suggesting TDD for Stage 1 or skipping a test plan for
Stage 6 are both errors — one anachronistic, one regressive.

When in doubt: check this table, then read the `## Development Strategy` section
in the stage's own README.