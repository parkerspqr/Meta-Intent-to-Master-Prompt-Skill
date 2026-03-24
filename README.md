# 🧠 Meta Intent Orchestrator

**Meta Intent Orchestrator** is a meta-skill for **Codex** that upgrades weak, vague, layered, or under-specified user requests into much stronger execution than a normal direct prompt can usually produce.

Instead of jumping straight from a raw request to action, it decides whether the task needs a lightweight direct path or a deeper hidden orchestration path. For complex requests, it silently builds the right internal thinking system first — and only then solves the task.

> In one sentence:  
> **this project exists to build the right depth of thinking before execution begins.**

---

## ✨ Why this project exists

A lot of weak AI output does **not** happen because the model lacks ability.

It happens because the task enters the model in the wrong shape.

Users often know what they want in spirit, but do not know how to formulate:

- the right level of expertise,
- the right constraints,
- the right quality bar,
- the right balance between preservation and transformation,
- the right mode of thinking,
- or the right internal role that should exist for the task.

So the model starts too early, from too weak a frame, and produces something that is:

- generic,
- shallow,
- cliché,
- technically neat but strategically wrong,
- or simply not as deep as the user actually needed.

**Meta Intent Orchestrator** was created to solve exactly that problem.

---

## 🚀 What value it creates

This project is not just about “better prompts.”

Its real value is much bigger:

> **it silently constructs the right internal cognitive architecture for the task before execution begins.**

That means the user does **not** have to manually:

- invent the perfect role,
- write a giant system prompt,
- design a multi-step workflow,
- or guess how to frame a difficult task at the right level of depth.

The skill does that part internally.

### The practical result

When it works properly, the output becomes:

- **deeper**
- **less generic**
- **more precise**
- **more original**
- **closer to the user’s true intent**
- **less likely to collapse into cliché**
- **more capable of handling preservation + transformation at the same time**

This is the real point of the project:
not to make prompts prettier,
but to make execution smarter.

---

## 🧩 Built for Codex

This project was built as a **Skill for Codex**.

Skills are reusable workflows that help ChatGPT and Codex perform specific tasks more consistently. In this case, the skill is designed to improve how complex user requests are framed **before execution begins**, so Codex can work through a stronger internal setup instead of starting from a weak raw prompt. Codex itself is OpenAI’s coding agent for tasks like editing files, running commands, and executing tests. :contentReference[oaicite:1]{index=1}

Meta Intent Orchestrator is especially aimed at tasks where direct prompting tends to fail:

- layered creative work,
- architectural direction,
- high-context redesigns,
- strategic transformation,
- and requests where preserving the core while radically improving the form is the real challenge.

---

## 🔥 What makes it different

This project is **not**:

- a generic prompt enhancer,
- a static role library,
- a decorative reasoning wrapper,
- a simple “understand intent and answer better” layer,
- or a menu of prewritten expert personas.

It is a **hidden meta-orchestrator**.

For simple tasks, it stays light.  
For complex tasks, it runs a deeper hidden chain.

---

## ⚙️ Core idea

At the center of the project is one key principle:

> **Do not start execution from a weak frame.**

For difficult tasks, the skill first builds the right internal frame, then solves the problem through that frame.

### High-level internal logic

For complex tasks, the skill:

1. reads the raw user request,
2. decides that the task needs deep orchestration,
3. silently generates a **task-specific maximal entity**,
4. silently generates a **task-specific internal system prompt + flow prompt**,
5. uses that internal operating system as the active working frame,
6. and only then executes the user’s task.

So the system does **not** go:

`raw request -> answer`

It goes:

`raw request -> detect complexity -> build the right internal intelligence -> execute through that intelligence -> answer`

That difference is the entire reason this project exists.

---

## 🧬 The hidden two-stage chain

The project is built around a hidden two-stage orchestration pattern.

### Stage 1 — build the maximal entity

The skill asks, in effect:

> What is the highest, deepest, most complete professional/intellectual entity that should exist for this exact task?

Not a canned role.  
Not a dropdown title.  
Not “designer” or “marketer” or “architect” from a list.

A **task-specific maximal entity**.

This stage is meant to produce the strongest possible mind-frame for the task.

### Stage 2 — build the internal prompt system

Once that maximal entity exists, the skill reflects on it and turns it into:

- an internal **system prompt**,
- an internal **flow prompt**,
- and the active execution frame used for the task.

Only after that does it move into solving the original request.

---

## 🧱 The two core primitives

The hidden chain is built around **two original user primitives**.

These are not decorative examples.  
They are not just inspiration.  
They are the structural heart of the system.

### Primitive 1
The first primitive is used to generate the **maximal role / maximal professional entity** for the task.

Its job is not to produce a shallow title.

Its job is to elevate the task from:
- an ordinary role,
- to a more exact and harder role,
- and then to a near-limit professional/intellectual entity.

### Primitive 2
The second primitive reflects on the result of Primitive 1 and turns it into:
- a real system prompt,
- a real flow prompt,
- and a working internal operating frame.

The skill is built so these two primitives are **adapted conservatively**, not freely rewritten.

That was one of the most important design constraints in the whole project.

---

## 🧨 The hardest design challenge

One of the biggest problems discovered during development was this:

it is **not enough** to preserve the input structure of Primitive 1.

You also need to preserve the **depth of its output**.

If Stage 1 produces only:
- a role name,
- and two or three short paragraphs,

then Stage 2 is forced to reflect on something already reduced.

That weakens the whole chain.

So a major design challenge became:

> **How do we make sure Stage 1 produces a rich enough role dossier for Stage 2 to build a genuinely strong internal prompt system?**

That insight shaped a large part of the current version.

---

## 🛠️ Installation

OpenAI’s current Skills flow supports creating, uploading, and installing skills from the Skills page, and Skills are supported in Codex. :contentReference[oaicite:2]{index=2}

To install this skill:

1. Open ChatGPT
2. Go to **Profile → Skills**
3. Click **New skill**
4. Choose **Upload from your computer**
5. Upload the packaged `skill.zip`

Once installed, ChatGPT/Codex can use the skill automatically when the task is relevant. :contentReference[oaicite:3]{index=3}

---

## 🧪 How to use it

Use this skill when the task is not just “do X,” but something more layered, such as:

- preserve the core but radically improve the form,
- avoid generic AI output,
- find the right depth, taste, or framing before execution,
- solve a complex task where the real bottleneck is the wrong internal frame,
- or work on a task where direct prompting tends to flatten nuance.

### Typical examples

- homepage redesign without losing brand identity,
- premium product direction without drifting into cliché,
- strategic creative tasks where direct prompting is too shallow,
- complex prompts that need a stronger internal role and execution system before action.

### What it should feel like

When the skill is working well, the user experience should feel like:

- “it understood what I actually meant,”
- “it did not rush into a generic answer,”
- “it built the right depth before solving,”
- “the result is sharper than what a normal direct prompt would have produced.”

---

## 📦 Project structure

```text
meta-intent-orchestrator/
├── SKILL.md
├── agents/
│   └── openai.yaml
├── references/
│   ├── examples.md
│   ├── primitive-matrices.md
│   ├── protocol.md
│   └── session-policy.md