LIFE v34.4 — Clean Plans Fix
Built cleanly from stable v34.2, not from v34.3/v34.3.1.

- Plans redesigned in the actual HTML/render logic (no DOM layout hacks).
- Compact task-first Plans screen.
- Each task has its own reminder button.
- Task reminder reuses existing OneSignal/Cloudflare scheduling and links to the task.
- Separate reminders remain available through a compact service button.
- Home "Найближче" now filters the real reminder list to future sendAt values in the actual render logic.
- LIFE_V10 preserved.
- Cloudflare Worker unchanged.
