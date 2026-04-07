# node-world v3

> Coordination platform for verified human-AI collaboration.
> Systems + Protocols + Tracking.

---

## What

**node-world v3 is a coordination platform.** It helps people and AI agents work together on tasks with built-in verification and complete lineage of how work happened.

Like email is a protocol for communication.
Like git is a system for version control.
**node-world v3 is a protocol for verified work coordination.**

---

## Status

**Phase 0: Design (April 2026)**

This repo will hold the v3 implementation (server, CLI, channel) once design stabilizes.
Currently empty — see [node-world-v3-story](https://github.com/eye-of-the-moon/node-world-v3-story) for design work in progress.

---

## Repos

| Repo | Purpose |
|------|---------|
| **node-world-v3** (this repo) | v3 implementation (code) — empty until Phase 1 |
| **[node-world-v3-story](https://github.com/eye-of-the-moon/node-world-v3-story)** | v3 design — ideas, decisions, roadmap |
| **[node-world-v2](https://github.com/eye-of-the-moon/node-world-v2)** | v2 implementation (currently running) |
| **[node-world-v2-story](https://github.com/eye-of-the-moon/node-world-v2-story)** | v2 design + decisions |

---

## Why v3

node-world v1 (2025) → node-world v2 / nw2 (2026 Q1).

v2 evolved organically — accumulated assumptions about hub/master roles, lifecycle management, and operational tooling. Useful for solo dev, but constrains the platform vision.

**v3 is a clean implementation of the platform model defined in [node-world-v3-story](https://github.com/eye-of-the-moon/node-world-v3-story).**

The current v2 keeps running for dogfooding while v3 develops in parallel. Migration path is documented in v3-story.

---

## Core Principles

```
1. Platform = Systems + Protocols + Tracking
2. Hierarchy is a primitive; the relationships are user-defined
3. Verification is what the task says, not what the worker is
4. Lineage accumulates. There is no separate reputation.
5. Hard rules are invisible. Soft guidance is visible.
6. Defaults are provided. Customization is opt-in.
```

---

## Layered Architecture

```
Layer 5: User Patterns      (user space)
─────────────────────────  ← Platform boundary
Layer 4: Workspace          (isolation/customization)
Layer 3: Protocols          (communication)
Layer 2: State Machines     (lifecycles)
Layer 1: Primitives         (structure)
Layer 0: Storage            (persistence)
```

See [node-world-v3-story/ideas/core/idea-002-platform-core.md](https://github.com/eye-of-the-moon/node-world-v3-story/blob/main/ideas/core/idea-002-platform-core.md) for details.

---

## License

TBD
