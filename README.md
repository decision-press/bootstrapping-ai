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

### Core Pillars: System level Pillars 00-99

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

### User Pillars: Pillars 100+

The system is designed to be extended. You can create domain-specific pillars for:
- Business operations and workflows
- Classroom management and pedagogy
- Community organization and coordination
- Game worlds and interactive narratives
- Personal documentation and knowledge management
- Whatever your use case requires

Each pillar has:
- Clear domain boundaries
- Explicit guardrails
- Rejection rules (what doesn't belong here)
- Integration points with other pillars
- Spin up a pillar in pillar1 and instantiate it in pillar2

## Key Features

### 1. Guardrails That Actually Work

**Purpose Before Process** - Features must serve clear purposes, not just be clever

**Anti-Sloppiness Protocol** - Prevents conceptual drift, contradictions, and dead rituals

**Live Ritual Theory** - Syntax/ritual is only "alive" if it causes actual behavioral change

**Function Style Calls** - Design useable functions and call them from any pillar

**Type Enforced** - Maintain coherency throughout project evolution through guardrails and anti-sloppiness protocol

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
- The machine 'state' resides outside the LLM enviornment creating psuedo memory enforcement
- Canon defines the state, not the other way around
- Recursive decomposition of complexity naturally creates useable artifacts
- Adaptive feed forward 'knowledge' prompting elevlates design efficiency.
- Useable artifacts prompt feed new threads creating recursively better artifacts.

### 4. Community-First Design

- AGPL-3.0 licensed
- Built for community organizations, not corporations
- Designed in Detroit for real-world use (shelters, community centers, parish halls)
- Forkable, modifiable, improvable

## Quick Start

### 1. Load the core Constructors simultaneously

Start a new conversation with your AI system and paste a pillar constructor:

```
[Tell the ai to 'emulate the bootstrapping-ai' not 'comment on it' ]
```

### 2. Set Context

Tell the system what you're working on:

```
Enter pillar(x). 
Do the work, the system checks the guardrails.
```

### 3. Collaborate

The system will now operate within the defined boundaries, enforce guardrails, and maintain structural integrity.

### 4. Generate Artifacts

As you work, save generated code, docs, and patterns back to your local repo structure and push to version control.

## Example Use Cases
**Load Core Constructors**

**spin up a pillar and name it:**
- Build workflows, schedules, communications
- Fair language interpretation for diverse communities

- Text Adventure Games
- Natural language gameplay with structured state
- Deterministic world simulation

- Writing
- Maintain philosophical rigor
- Prevent drift into sentimentality

- System Design
- Meta-architecture discussions
- Integrity audits

**Save Artifacts Locally**
**Push to Repository**

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

## Example Repository Structure

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


## Canonical Artifact Format: Why Markdown Is the Substrate

The BOOTSTRAP design methodology defines Markdown (`.md`) as the canonical
format for all human-readable, persistent artifacts in the system. This
decision is intentional and foundational. Markdown provides the durability,
clarity, and interoperability required for long-term human–AI collaboration.

### 1. Plain Text Durability
Markdown is plain text. It remains readable across tools, operating systems,
and future environments without the risk of corruption or proprietary
lock-in. Any text editor can open and modify it.

### 2. Human-Readable Structure
Markdown offers simple, expressive structure:
headings, lists, links, tables, and code blocks. These enable clean
organization of system architecture, kernel specifications, and design
documents without introducing unnecessary formatting complexity.

### 3. Version Control Compatibility
Markdown integrates cleanly with Git. Differences between versions are
clear and readable, making collaboration, auditing, and rollback practical.
This is essential for a system that evolves through iterative refinement.

### 4. AI-Friendly Processing
Markdown boundaries and formatting patterns allow synthetic collaborators to
process, restructure, and refine text with minimal ambiguity. It reduces
hallucination risk and prevents formatting drift across revisions.

### 5. Universal Applicability
All core BOOTSTRAP artifacts use Markdown by default:

- architecture definitions  
- kernel specifications  
- design notes  
- constructors  
- outlines  
- README files  
- collaborative drafts  
- long-form documentation  
- transcripts and narrative records  

Non-Markdown formats (JSON, Astro, TypeScript, shell scripts, etc.) are
used only when their function requires it, and are typically referenced or
documented through adjacent Markdown artifacts.

### 6. Tooling Alignment
Markdown is treated as a first-class format by development tools such as
Visual Studio Code. Features such as preview panes, outline views,
formatting helpers, and syntax highlighting enable a consistent editing
experience.

---

Standardizing on Markdown establishes a stable substrate for the BOOTSTRAP
method, ensuring that system artifacts remain coherent, portable, and
future-proof.
```


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
