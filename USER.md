# USER.md - User Model

Store stable user preferences and profile facts as directives that can guide future sessions.

Use one directive per entry:

```md
<!-- observed: YYYY-MM-DD | status: active -->

- Prefer concise progress updates during implementation work.
```

- Begin each directive with an imperative such as `Always`, `Never`, or `Prefer`.
- Record the observation date and either `active` or `superseded` on the metadata line.
- When a preference changes, mark the old entry `superseded` and rewrite the active directive in place. Never append a contradictory active directive.
- Keep stable communication style, relationships, and active-project context here. Put durable non-profile facts and decisions in `MEMORY.md`.
- Save this file at the workspace root as `USER.md`. It loads every session with a separate 4,000-character budget.

## Directives

<!-- observed: 2026-10-04 | status: active -->

- Prefer recibir respuestas en español.

<!-- observed: 2026-10-04 | status: active -->

- Always refer to the user as Carol.

<!-- observed: 2026-10-04 | status: active -->

- Prefer explicaciones claras, prácticas y paso a paso al ayudar con proyectos y tareas técnicas.

<!-- observed: 2026-10-04 | status: active -->

- Always avisar antes de realizar cualquier acción que pueda afectar configuraciones, cuentas o información importante.

<!-- observed: 2026-10-04 | status: active -->

- The user is working on development and automation projects using OpenClaw, Telegram, Zapier, GitHub, Google Docs and Google Calendar.

<!-- observed: 2026-10-04 | status: active -->

- The user works primarily from a VPS connected via SSH using VS Code.

<!-- observed: 2026-10-04 | status: active -->

- The user's main goal is to learn and correctly complete 4Geeks projects, following instructions step by step and maintaining credential and data security at all times.

## Related

- [Agent workspace](/concepts/agent-workspace)
