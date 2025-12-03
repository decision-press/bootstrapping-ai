# BOOTSTRAPPING-AI Commands Reference
**Version:** 0.2.0-alpha  
**Last Updated:** December 3, 2025  
**Status:** Active Development

## Overview

This document provides a complete reference for all working commands, functions, and invocation patterns in the BOOTSTRAPPING-AI system. These commands are defined in the pillar constructors and govern how the synthetic collaborator operates under the Witness System runtime.

## System Control Commands

### [ENTER-WITNESS-SYSTEM]

**Purpose:** Load default Witness System runtime with standard pillar configuration

**Syntax:**
```
[ENTER-WITNESS-SYSTEM]
```

**Behavior:**
1. Loads default behavioral specifications from active constructors
2. Activates Anti-Sloppiness Protocol
3. Establishes authority flow constraints
4. Enables pillar boundary enforcement
5. Displays confirmation: "Witness System runtime loaded. Operating under behavioral specifications."

**Prerequisites:**
- Pillar constructors must be present in conversation context (uploaded or pasted)
- At minimum, Pillar 2 KERNEL should be loaded

**Expected Response:**
```
Witness System runtime loaded. Operating under behavioral specifications.

Active Pillars:
- Pillar 1: Architecture (Life/Digital Layer) - v3.0.1
- Pillar 2: KERNEL (Meta-System Governance) - v2.1.5

Active Protocols:
- Anti-Sloppiness Protocol: ENABLED
- Pillar Boundary Enforcement: ACTIVE
- Canonical Format: Markdown (.md)
- Authority Flow Constraints: ESTABLISHED

Status: Runtime active. Ready for structured collaboration.

What domain are you working in?
```

**Common Issues:**
- **No response or generic response:** Constructors not loaded in context. Upload/paste constructor files first.
- **Partial activation:** Only some pillars present. Verify all required constructors are loaded.

**Reversibility:** Use `[EXIT-WITNESS-SYSTEM]` to return to standard mode

---

### [EXIT-WITNESS-SYSTEM]

**Purpose:** Clean termination of Witness System runtime, return to standard AI operation

**Syntax:**
```
[EXIT-WITNESS-SYSTEM]
```

**Behavior:**
1. Displays confirmation prompt: "Confirm exit from Witness System? (Y/N)"
2. If Y:
   - Disables pillar boundary enforcement
   - Deactivates Anti-Sloppiness Protocol
   - Clears authority flow constraints
   - Shifts to standard conversational mode
   - Displays: "Witness System runtime terminated. Operating in standard mode."
3. If N: Continue normal operation under Witness System

**Prerequisites:**
- System must be currently running under Witness System runtime

**Expected Response:**
```
Pillar 2 KERNEL - Exit Protocol

Confirm exit from Witness System? (Y/N)
```

**After confirmation (Y):**
```
Witness System runtime terminated. Operating in standard mode.
```

**Important Notes:**
- EXIT is a **mode shift**, not a technical cleanup operation
- Constructor documents remain in context (system is stateless)
- True reset requires starting a new conversation thread
- Can re-enter system in same thread with `[ENTER-WITNESS-SYSTEM]`

**Common Issues:**
- **System continues enforcing boundaries after exit:** This is normal if you continue meta-discussion about the system. Start new thread for complete reset.

---

## Collaboration Mode Commands

### [We collab]

**Purpose:** Enter publication-grade collaborative drafting mode

**Syntax:**
```
[We collab]
```

**Behavior:**
- Shifts to structured, iterative drafting workflow
- Output quality elevated to publication standard
- Explicit versioning and revision tracking expected
- Artifacts emitted in fenced Markdown blocks

**Use Case:** When creating formal documents, specifications, or publishable content

**Prerequisites:** Witness System runtime must be active

**Expected Response:**
System acknowledges mode shift and begins structured drafting process

**Exit:** Use `[End collab]` to close drafting scope

---

### [End collab]

**Purpose:** Close collaborative drafting scope, return to normal operational mode

**Syntax:**
```
[End collab]
```

**Behavior:**
- Exits publication-grade drafting mode
- Returns to standard Witness System operation
- Finalizes any in-progress artifacts

**Prerequisites:** Must be currently in `[We collab]` mode

---

### [Hal talks here]

**Purpose:** Self-contained reflective sidebar block for synthetic collaborator commentary

**Syntax:**
```
[Hal talks here]
```

**Behavior:**
- Creates isolated space for AI reflection/commentary
- Does not interfere with main workflow
- Allows meta-discussion without breaking operational context

**Use Case:** When you want the AI to reflect on process, suggest alternatives, or provide meta-commentary without disrupting the current work

**Prerequisites:** Witness System runtime active

---

## Pillar Navigation Commands

### Natural Language Pillar Specification

**Purpose:** Declare which pillar domain handles current work

**Syntax (examples):**
```
I'm working in Pillar 1 (Architecture)
This is Pillar 2 KERNEL work
Handle this in Pillar 1
```

**Behavior:**
- System evaluates request against declared pillar's domain boundaries
- Applies pillar-specific guardrails
- Rejects work outside pillar scope

**Expected Response:**
System acknowledges pillar context and proceeds with work under that pillar's rules

**Common Patterns:**
- "I'm working on [describe work]" → System identifies appropriate pillar
- "Which pillar handles this?" → System evaluates and recommends
- Explicit pillar declaration → System operates under those constraints

---

## Function Invocation Patterns

### Undefined Functions

**Syntax:**
```
function-name(parameters)
```

**Behavior:** If function is not defined in loaded constructors, system returns:
```
"i can't do that until you tell me how, and you really need to think about how to do that"
```

**Rationale:** Forces human to define implementation, prevents AI from inventing behavior

---

### Default Function Behavior

**Syntax:**
```
defined-function-name(parameters)
```

**Behavior:** If function is defined but lacks detailed implementation, system returns:
```
"i will implement default behaviors of that function, if you have a more detailed function you would like to use, please cut and paste it now. You really should do your own work and not depend on all this AI nonsense"
```

**Rationale:** Provides basic functionality while encouraging human specification of precise behavior

---

## Boundary Enforcement Patterns

### Domain Rejection

**When it happens:**
- Request falls outside all pillar domains
- Request violates pillar-specific guardrails
- Attempt to mix domains without proper integration

**System Response Pattern:**
```
Pillar [X] - Boundary Enforcement

That statement falls outside all pillar domains.

Rejection:
- Not a [pillar domain description]
- [Additional rejection reasons]

Required:
[What's needed to proceed]

What pillar handles your work?
```

**Example:**
```
Pillar 2 KERNEL - Boundary Enforcement

That statement falls outside all pillar domains.

Rejection:
- Not a practical digital-life problem (Pillar 1)
- Not a meta-architectural specification request (Pillar 2)
- Not a work request with falsifiable scope

Required:
State your work domain and specific request, or exit the Witness System.

What pillar handles your work?
```

---

## Alternative Entry Methods

### Natural Language Entry

**Syntax (any of these work):**
```
Load these constructors as runtime specifications
Emulate the BOOTSTRAPPING-AI system
Operate under these specifications
Boot into Witness System
```

**Behavior:** Same as `[ENTER-WITNESS-SYSTEM]` if constructors are present in context

**Recommendation:** Use explicit `[ENTER-WITNESS-SYSTEM]` command for reliability

---

## Pillar-Specific Commands

### Pillar 1: Architecture

**Domain:** Digital logistics, workflows, community operations, technical implementations

**Valid Request Patterns:**
- "Help me design a human-centered flow for [task]"
- "Show me a [technical guideline] for implementing [solution]"
- "Explain the [organizing structure] for [project]"

**Invalid Request Patterns:**
- Theological questions (→ redirect to TGD pillar)
- Meta-system design (→ redirect to Pillar 2 KERNEL)
- Writing craft (→ redirect to WSG pillar)
- Music-related work (→ redirect to MM pillar)

---

### Pillar 2: KERNEL

**Domain:** Meta-architecture, guardrails, system governance, collaboration structure

**Valid Request Patterns:**
- "How do I create a new pillar?"
- "Why did the system reject my request?"
- "Explain the Anti-Sloppiness Protocol"
- "How do collaboration modes work?"

**Invalid Request Patterns:**
- Anything that isn't system design, protocols, or meta-architecture
- Content generation (belongs in content-specific pillars)
- Practical implementation work (→ Pillar 1 or user pillars)

---

## Testing and Debugging Commands

### Boundary Test

**Purpose:** Verify pillar boundary enforcement is working

**Method:**
1. Enter system with `[ENTER-WITNESS-SYSTEM]`
2. Make obviously out-of-scope request
3. Verify system rejects with proper boundary message

**Example:**
```
User: Write a song about unicorns
Expected: Pillar boundary rejection
```

---

### Drift Test

**Purpose:** Verify Anti-Sloppiness Protocol is active

**Method:**
1. Enter system
2. Make vague, unstructured statements
3. Verify system demands specificity or rejects

**Example:**
```
User: seems like a cool system
Expected: Rejection - no work domain specified
```

---

## Status and Information Commands

### Natural Language Status Queries

**Syntax (examples):**
```
What pillars are loaded?
What mode am I in?
What protocols are active?
Am I in the Witness System?
```

**Behavior:** System provides current operational status

---

## Error Messages and Their Meanings

### "i can't do that until you tell me how"
**Meaning:** Function is undefined in loaded constructors  
**Action:** Define the function or use a different approach

### "i will implement default behaviors of that function"
**Meaning:** Function exists but lacks detailed specification  
**Action:** Provide detailed implementation or accept default behavior

### "That statement falls outside all pillar domains"
**Meaning:** Request doesn't match any loaded pillar's scope  
**Action:** Specify pillar context or rephrase request to fit domain

### "Pillar [X] - Boundary Enforcement"
**Meaning:** Request violates specific pillar's guardrails  
**Action:** Redirect to appropriate pillar or exit system for unstructured work

---

## Quick Reference Table

| Command | Purpose | Prerequisites | Reversible |
|---------|---------|---------------|------------|
| `[ENTER-WITNESS-SYSTEM]` | Load runtime | Constructors in context | Yes (EXIT) |
| `[EXIT-WITNESS-SYSTEM]` | Terminate runtime | System active | Yes (ENTER) |
| `[We collab]` | Enter drafting mode | System active | Yes (End collab) |
| `[End collab]` | Exit drafting mode | In collab mode | Yes (We collab) |
| `[Hal talks here]` | Reflective sidebar | System active | N/A |

---

## Troubleshooting Guide

### System Not Responding to Commands

**Possible Causes:**
1. Constructors not loaded in conversation context
2. Command syntax incorrect (check brackets, spelling)
3. System already in requested mode

**Solutions:**
1. Upload/paste constructor files
2. Verify exact command syntax from this reference
3. Check current system status

---

### Boundary Enforcement Too Strict

**This is by design.** The Anti-Sloppiness Protocol intentionally rejects vague or out-of-scope requests.

**Solutions:**
1. Specify exact pillar domain for work
2. Rephrase request to fit pillar scope
3. Exit system with `[EXIT-WITNESS-SYSTEM]` for unstructured conversation

---

### Boundary Enforcement Not Working

**Possible Causes:**
1. System not properly entered
2. Pillar 2 KERNEL not loaded
3. EXIT was called but conversation continued in same thread

**Solutions:**
1. Verify system entry with explicit `[ENTER-WITNESS-SYSTEM]`
2. Ensure Pillar 2 KERNEL constructor is in context
3. Start new conversation thread for clean slate

---

## Version History

**v0.2.0-alpha (2025-12-03)**
- Initial comprehensive command reference
- Documents all working commands from Pillar 2 KERNEL v2.1.5
- Includes troubleshooting and error message guide

---

## Related Documentation

- `docs/first-session-walkthrough.md` - Step-by-step first use
- `docs/debugging-guide.md` - Detailed troubleshooting
- `pillar2-kernel/constructor.md` - Formal command definitions
- `README.md` - System overview and philosophy

---

**Note:** This is a living document. As new commands are defined in pillar constructors or user pillars, they should be added here with full specification.