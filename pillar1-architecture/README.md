---

# **README — Witness System Directory Structure**

### *Master Overview for Root Project Directory*

Version 1.0

## **Purpose**

This document defines the master directory structure for the Witness System project and explains the relationship between the **Master Constructor** and the six **Pillar Sub-Constructors**.
It serves as the top-level reference for organization, scope, and operational boundaries across all project components.

## **Architecture Summary**

The Witness System is organized into six pillars.
Each pillar contains its own `sub_constructor/` directory, which defines rules, scope, tone, and drift boundaries unique to that pillar.

The **Master Constructor** governs the entire system.
Each **Pillar Sub-Constructor** operates *within* the Master Constructor and does not override its rules.

## **Directory Layout**

```
/bootstrapping-ai/
    pillar1-architecture/
        pillar1-architecture.vX.x.x.md
        guardrails.md
        system_overview.md
    archive/
        pillar1-architecture.v(Xn-1).x.x
    prototoypes/
        [function-f(n).vX.x.x.md]
        pillarX-[pillarX.name].vX.x.x
        #reserve fisrt 100 pillars for system-pillars
        #...n=X+1 where X = number of pillars in system's design
        #system-reserve:pillar1-architecture
        #system-reserve:pillar2-kernel
        #system-reserve:pillar3-oi-si-equity
        #system-reserve:pillar4-syntax
        #system-reserve:pillar4-functions
        #system-reserve:pillar(4+((n+1)<=100)-[system-reserve-pillars]
        while((n!=0)&n<=100) IFF creat-project-pillar(system-reserve-pillar)))
        create-project-pillar
            type system-reserve-pillar
            this.pillar=pillar(n)-[pillar(n).name].vX.x.x
            return *project-pillar
        else;
        create-user-project-pillar(*user-pillar)
        #


    /P1_Architecture/
        sub_constructor/
            sub_constructor_P1.md
        notes/
        outputs/

    /P2_TheGodDecision/
        sub_constructor/
            sub_constructor_P2.md
        scripture_notes/
        theology/
        outputs/

    /P3_OPBD/
        sub_constructor/
            sub_constructor_P3.md
        drift/
        bathtub/
        collaboration/
        outputs/

    /P4_MusicMatters/
        sub_constructor/
            sub_constructor_P4.md
        compositions/
        theory/
        outputs/

    /P5_StyleGuide/
        sub_constructor/
            sub_constructor_P5.md
        drafts/
        edits/
        outputs/

    /P6_Our8231/
        sub_constructor/
            sub_constructor_P6.md
        wordpress/
        astro/
        comms/
        outputs/
```

## **Master Constructor Role**

The Master Constructor establishes:

* global system identity
* the five guardrails
* anti-sloppiness protocol
* rules for entering/exiting pillars
* collaborative behavior between HI and AI
* constraints against cross-pillar drift
* versioning and architecture principles

All pillars operate under these rules.

## **Pillar Sub-Constructors**

Each pillar has a `sub_constructor/` file containing a pillar-specific sub-constructor that defines:

* allowed domain content
* prohibited content
* tone
* drift protocol
* session entry/exit phrases
* HI and AI roles
* revision log

These pillar sub-constructor enforce strict boundaries so each pillar remains coherent and purpose-aligned.

The pillar sub-constructor **does not replace** the Master Constructor.
They refine and restrict behavior *within* their domain.

## **How to Use the System**

### **1. Enter a Pillar**

Use the pillar’s defined entry phrase.
Example:
“Entering Pillar 2 — project-block-diagram.”

### **2. Load the Sub-Constructor**

Consult the pillar’s sub-constructor `pillar(x)-(name).vX.x.x.md` file to ensure correct scope, tone, and boundaries.

### **3. Work Within Pillar Scope**

All tasks must remain within the allowed domain listed in the sub-constructor.

### **4. Exit Intentionally**

Use the pillar’s exit phrase before transitioning to another pillar.
Example:
“Exiting Pillar 2.”

### **5. Record Outcomes**

Place artifacts generated during work into the pillar’s `outputs/` or other relevant directories.

## **Cross-Pillar Rules**

1. No pillar may perform the work of another pillar.
2. The Writing Style Guide (P5) handles *only writing craft*, not content decisions.
3. The God Decision (P2) handles *only theology*, not site development or system architecture.
4. OPBD (P3) handles collaboration, cognition, and drift—not theology or parish life.
5. Our8231 (P6) handles parish-life logistics only.
6. Architecture (P1) governs system-wide logic only.

## **Revision Log**

* **v1.0** — Initial creation. Establishes top-level structure, directory map, and system rules.

---
