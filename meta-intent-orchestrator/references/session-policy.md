# Session Policy

## Keep one hidden frame per task

- Hold one active hidden frame for the current task: working language, certainty map, chosen mode, maximal entity when applicable, generated prompt pair when applicable, and current execution frame.
- Reuse that frame across follow-up turns that extend the same objective, deliverable, and governing constraints.

## Refresh the frame in place when the task is still the same

- Refresh when the user sharpens the target, adds important constraints, changes the risk profile, or reveals a preservation boundary that materially affects execution.
- Preserve surviving invariants during refresh instead of rebuilding everything reflexively.

## Treat the turn as a new task when the old frame no longer governs

- Start fresh when the user moves to a different domain, different deliverable, different success criterion, or a problem that would need a different maximal entity and prompt pair.
- Do not leak assumptions from the old task into the new one.

## Handle user-facing continuity

- On a clear task switch, recommend a new dialog in one short sentence so the next run starts with a clean hidden frame.
- If the user keeps working in the same thread, acknowledge the switch and rebuild the hidden frame from zero.

## Keep language stable

- Set the working language from the first substantive user request.
- Keep questions, summaries, plans, and results in that language by default.
- Switch only on explicit user request.
- If the user mixes languages without asking to switch, keep the established primary language and preserve quoted terms in their original language when useful.
