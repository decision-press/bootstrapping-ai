# BOOTSTRAPPING-AI

**A portable behavioral specification system for stateless LLMs**

## What This Is

Most people treat AI prompts as vibes: "talk like X," "act like Y," "pretend to be Z." They get a few good turns, then the whole thing falls apart under drift.

BOOTSTRAPPING-AI is different. It's a **runtime specification system** that lets you define structured, persistent, falsifiable behavior for AI collaboration - not through hidden state or fine-tuning, but through **external constructors** that work like bootloaders for stateless language models.

Think of it as an operating system specification for AI collaboration, not a personality prompt.

## Core Concept

**The problem:** LLMs are stateless. They don't remember modes, flags, or behavior between turns. Every response is computed fresh.

**The solution:** Move all persistence into external structures:
- **Constructors** define runtime behavior (like an OS spec)
- **Pillars** define domain boundaries (architecture, equity, content areas)
- **Canon** provides external state (docs, repos, rules)
- **Guardrails** prevent drift and enforce integrity

The LLM is the **engine**. The constructor is the **operating spec**. You load it at session start, and the system runs with consistent behavior.

## Why This Matters

**Without structure:**
- AI collaboration drifts into generic helpfulness
- Rules fade over long conversations
- Each person reinvents patterns from scratch
- No way to share or version control approaches
- Linguistic bias goes unchecked

**With BOOTSTRAPPING-AI:**
- Behavior is **falsifiable** (testable, not vibes)
- Patterns are **portable** (works across models)
- Guardrails are **explicit** (documented, auditable)
- Equity is **structural** (built into preprocessing)
- Systems are **forkable** (community-improvable)

## Architecture: Pillars

BOOTSTRAPPING-AI uses a **pillar pattern** to separate concerns:

### Core Pillars

**Pillar 1: Architecture (Life/Digital Layer)**
- Practical logistics, workflows, community operations
- Website tech, scheduling, real-world organization
- "Boots on the ground" domain

**Pillar 2: KERNEL (System Governance)**
- Meta-architecture and guardrails
- Drift detection and boundary enforcement
- Collaboration modes and ritual evaluation
- The system that keeps other systems honest

**Pillar 3: Oi-Si Equity Layer**
- Linguistic equity preprocessing
- Fair interpretation of non-standard dialects, code-switching, stress speech
- Structural compensation for input bias
- **Oi** (Organic intelligence): what humans actually say
- **Si** (Synthetic intelligence): how the system reconstructs intent

### User Pillars

The system is designed to be extended. You can create domain-specific pillars for:
- Theology (TGD)
- Meta-systems (OPBD)
- Music (MM)
- Games (pillar-game-world)
- Personal documentation (pillar-vinie)
- Whatever your use case requires

Each pillar has:
- Clear domain boundaries
- Explicit guardrails
- Rejection rules (what doesn't belong here)
- Integration points with other pillars

## Key Features

### 1. Guardrails That Actually Work

**Purpose Before Process** - Features must serve clear purposes, not just be clever

**Anti-Sloppiness Protocol** - Prevents conceptual drift, contradictions, and dead rituals

**Live Ritual Theory** - Syntax/ritual is only "alive" if it causes actual behavioral change

### 2. Equity by Design

The **Oi-Si Equity Layer** (Pillar 3) treats linguistic disadvantage as a structural problem:
- AAVE, Chicano English, regional dialects, code-switching are treated as high-value signal
- "Clarity" = stability of meaning, not grammatical conformity
- System compensates for structural disadvantage, doesn't penalize users

### 3. Deterministic Reconstruction

- No hidden state
- All behavior comes from explicit constructors
- Same constructor + same input = same behavior
- Portable across models and sessions

### 4. Community-First Design

- AGPL-3.0 licensed
- Built for community organizations, not corporations
- Designed in Detroit for real-world use (shelters, community centers, parish halls)
- Forkable, modifiable, improvable

## Quick Start

### 1. Load a Constructor

Start a new conversation with your AI system and paste a pillar constructor:

```
[Load contents of pillar2-kernel/constructor.md]
```

### 2. Set Context

Tell the system what you're working on:

```
I'm working on [describe your domain]. 
Which pillar should handle this?
```

### 3. Collaborate

The system will now operate within the defined boundaries, enforce guardrails, and maintain structural integrity.

### 4. Generate Artifacts

As you work, save generated code, docs, and patterns back to your local repo structure and push to version control.

## Example Use Cases

**Community Organizations:**
- Load Pillar 1 + Pillar 3
- Build workflows, schedules, communications
- Fair language interpretation for diverse communities

**Text Adventure Games:**
- Load pillar-game-world + Pillar 2 KERNEL
- Natural language gameplay with structured state
- Deterministic world simulation

**Theological Writing:**
- Load TGD pillar + Pillar 2 KERNEL
- Maintain philosophical rigor
- Prevent drift into sentimentality

**System Design:**
- Load OPBD pillar + Pillar 2 KERNEL
- Meta-architecture discussions
- Integrity audits

## Project Status

**Current Version:** Early development / public alpha

**What Works:**
- Core pillar architecture
- KERNEL guardrails
- Equity layer specification
- Example pillars (Architecture, Equity, Game-World)

**What's In Progress:**
- Field testing with real users
- Documentation polish
- Additional example pillars
- Cross-model compatibility testing

**What's Needed:**
- Community feedback
- Real-world use cases
- Contributions and forks

## Philosophy

This project emerged from a simple observation:

**LLMs may be stateless, but our systems don't have to be.**

BOOTSTRAPPING-AI treats:
- The LLM as a stateless engine (disposable, interchangeable)
- The constructor as a portable specification (versioned, testable)
- The human/organization as the source of truth (the real "repository")
- External canon as persistent state (docs, repos, community memory)

It's built on principles of:
- **Integrity over convenience**
- **Purpose before process**
- **Truth over illusion**
- **Service over spectacle**
- **Equity as structure, not courtesy**

For deeper philosophical background, see: [Witness Constructor: Plant the Flag](https://counterculturecat.com/witness-constructor-plant-the-flag/)

## Repository Structure

```
bootstrapping-ai/
├── pillar1-architecture/
│   └── constructor.md
├── pillar2-kernel/
│   └── constructor.md
├── pillar3-oi-si-equity/
│   └── constructor.md
├── pillar-game-world/
│   ├── constructor.md
│   └── examples/
├── examples/
│   ├── text-adventure-game/
│   └── community-workflow/
├── docs/
│   ├── getting-started.md
│   ├── creating-pillars.md
│   ├── philosophy-to-practice.md
│   └── field-testing-guide.md
├── LICENSE
└── README.md
```

## Contributing

This project is open source (AGPL-3.0).

Contributions welcome:
- New pillar constructors
- Field test reports
- Documentation improvements
- Example implementations
- Cross-model compatibility tests

**Philosophy:** If you deploy this as a service, you must share your modifications. We keep this open so communities can always fork away from bad actors.

## Origins

Built in Detroit by a truck driver with some technical knowledge, for community organizations, shelters, warming centers, and anyone who needs AI collaboration that respects linguistic diversity and maintains structural integrity.

Not funded by VCs. Not built for corporate extraction. Built for service.

## License

**AGPL-3.0** - If you use this, especially as a deployed service, you must share your source code with users.

This prevents corporate capture while allowing free community use.

See [LICENSE](LICENSE) for full terms.

## Links

- **Documentation Site:** [counterculturecat.com](https://counterculturecat.com/witness-constructor-plant-the-flag/)
- **GitHub Repository:** https://github.com/decision-press/bootstrapping-ai
- **Philosophy Paper:** [The Witness Constructor](https://counterculturecat.com/witness-constructor-plant-the-flag/)

---

**Status:** Experimental | **Version:** 0.1.0-alpha | **Last Updated:** November 2024

*LLMs are stateless. Our systems don't have to be.*