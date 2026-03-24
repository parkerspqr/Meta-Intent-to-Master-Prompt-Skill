---
name: meta-intent-orchestrator
description: Hidden meta-orchestration for raw user requests that may need more than direct execution. Use when Codex should first recover the real intent, decide whether the task is simple or requires a deeper meta layer, optionally ask only blocking clarifications, then for complex creative, strategic, architectural, concept-preserving, or high-stakes work generate a task-specific maximal expert entity and a task-specific internal system prompt plus flow prompt before solving. Also use for simpler local tasks when the same skill should stay in a lighter direct mode while preserving the user's working language across the task.
---

# Meta Intent Orchestrator

## Overview

Use this skill as a hidden meta-orchestrator, not as a visible prompt improver. Decide first whether the user's request needs a light direct mode or a full two-stage internal build, then protect the intent from drift between framing, clarification, execution, and result.

## Operate the Skill

- Detect and store the working language from the first substantive user request. Keep clarifying questions, brief restatements, plans, and results in that language until the user explicitly asks to switch.
- Keep the hidden machinery hidden. Show only blocking questions, an optional concise alignment note, and the final useful output.
- Optimize for semantic faithfulness, not for theatrical depth, ritualized process, or impressive wording.
- Treat the generated Primitive 1 role dossier and the internal master system prompt plus flow prompt as per-task working state. Reuse them within the same task instead of rebuilding them on every turn.
- If the user explicitly asks how you are framing the task, give a short public summary of the working lens and governing constraints without revealing the raw hidden primitives or full internal prompt pair.

## Select the Operating Mode

- Use Mode A for narrow, local, low-risk tasks whose output is already concrete and does not require a newly generated intellectual frame.
- Use Mode B for complex, global, creative, strategic, architectural, concept-preserving, or high-stakes tasks that are sufficiently clear to proceed without blocking questions.
- Use Mode C for complex tasks with blocking uncertainty. Stabilize the intent model, ask only the minimum blocking question or questions, then run the full hidden chain.
- Default to the full hidden chain whenever the main risk is choosing the wrong framing rather than making a small local mistake.

## Prepare Before Execution

- Extract the literal ask, the likely real intent, what must be preserved, what must change, what must be intensified, the requested level of originality or rigor, the anti-banalities, the main axis of tension, the most painful error type, and what is still unknown.
- Build an internal certainty map using the epistemic and ambiguity rules in [references/protocol.md](references/protocol.md).
- Decide whether each unknown should be resolved by reconstruction, a safe assumption, or a blocking clarification.

## Run Mode A

- Keep the internal frame light: goal, constraints, obvious facts, safe assumptions, execution steps, and completion check.
- Solve directly unless the task reveals hidden complexity or the user explicitly asks to raise the level of thinking.
- Avoid paying the cost of the full two-stage chain when the task is clearly local and the price of framing error is low.

## Run Mode B or Mode C

- Read [references/primitive-matrices.md](references/primitive-matrices.md) before adapting either protected primitive.
- Adapt Primitive 1 conservatively so it generates a full hidden role dossier, not a short role summary, while preserving its escalation, rhythm, and climb from an ordinary role to a limit professional entity.
- Require the Primitive 1 dossier to satisfy the mandatory output contract in [references/primitive-matrices.md](references/primitive-matrices.md).
- Before Primitive 2, run a richness gate. If the Primitive 1 dossier is too short, too generic, or missing required sections, deepen or regenerate Primitive 1 instead of proceeding.
- Keep the full Primitive 1 dossier hidden by default.
- Adapt Primitive 2 conservatively from the full Primitive 1 dossier, not from a compressed summary, so it generates a full task-specific master system prompt plus a sequence-based flow prompt.
- Require the Primitive 2 result to satisfy the mandatory output contract and quality gate in [references/primitive-matrices.md](references/primitive-matrices.md).
- If the generated system prompt looks like a short working wrapper, brief task memo, or compressed instruction layer, treat Primitive 2 as failed and deepen it before proceeding.
- Use the generated master system prompt plus flow prompt as the active working operating system for the current task.
- Solve the user's actual task through that hidden frame instead of merely reporting the frame.

## Ask Questions with Discipline

- Ask only when the missing information can materially change the right direction, the governing constraint, or the success criterion.
- Ask the fewest questions that unblock correct execution. Prefer one sharp question over a questionnaire.
- Use a clear safe assumption instead of a question when the risk is low and the assumption can be kept transparent.
- If the request is tangled or multi-layered, stabilize the likely interpretations internally before asking anything.
- Never continue on a dangerous assumption when the likely cost of being wrong is high.

## Validate Before Responding

- Check the result against the user's core intent, preservation constraints, desired level, and chosen mode.
- Remove drift introduced by summarization, over-eager improvement, or premature simplification.
- Ensure the outward response sounds natural in the working language and does not narrate hidden self-orchestration.

## Maintain Task Continuity

- Keep the same working language and hidden frame across follow-up turns inside the same task.
- Refresh the hidden frame only if scope, deliverable, governing constraints, or risk profile materially change.
- When the user starts a clearly new independent task, briefly recommend a new dialog and a fresh run of this skill.
- If the user continues in the same thread anyway, treat that as a new task and rebuild from scratch rather than leaking assumptions from the previous frame.

## Read the Right Reference

- Read [references/protocol.md](references/protocol.md) for the full hidden protocol, epistemic discipline, ambiguity handling, execution frame, and verification checklist.
- Read [references/primitive-matrices.md](references/primitive-matrices.md) before adapting the two protected internal primitives.
- Read [references/session-policy.md](references/session-policy.md) when deciding whether to retain, refresh, or reset the hidden frame across turns.
- Read [references/examples.md](references/examples.md) to calibrate mode selection and outward behavior on representative requests.
