# MonarqRise Studio

An AI-assisted monorepo for planning, designing, developing, testing, and shipping games with Codex or Claude.

## Workspace

- `docs/` - Game vision, design documents, planning, milestones, and architecture.
- `projects/` - Individual game projects and prototypes.
- `src/` - Shared engine, systems, utilities, and gameplay code.
- `assets/` - Art, audio, fonts, and source asset files.
- `tools/` - Automation, generators, validation scripts, and developer tools.
- `tests/` - Automated tests for shared systems and projects.

## Suggested workflow

1. Capture the concept in `docs/game-design.md`.
2. Break it into milestones and tasks in `docs/game-plan.md`.
3. Define architecture and dependencies in `docs/architecture.md`.
4. Use `AGENTS.md` to give your AI agent repository-specific instructions.
5. Keep planning documents and implementation synchronized after each major milestone.

## AI agent workflow

Ask your agent to implement work in small, reviewable pieces:

- Produce a design proposal before changing code.
- Add or update tests with each gameplay feature.
- Record decisions in the relevant design or architecture document.
- Prefer deterministic systems and data-driven configuration.
- Run the smallest relevant validation command before reporting completion.
