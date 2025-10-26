# Workshop Guide - Week 8: Starting Digital Projects and Prototyping

**Date:** October 27, 2025
**Duration:** 2h 40min (10:00 AM - 12:50 PM, minus 10min break)

This is a teaching checklist to track progress during the workshop.

---

## Introduction: Why Project Management? (5 min)

### Two Purposes
- [ ] **Purpose 1:** Help you build better research projects
- [ ] **Purpose 2:** Project management is a necessary skill for anything
  - Completing any plan, achieving any goal
  - Software engineering = engineering shortcut for large scale work

### Scalability Concept
- [ ] Same approach works for everything: small scripts → large projects
- [ ] **Scalable:** Can scale up, can scale down
- [ ] If you just want a small script, you don't need this
- [ ] But for complete projects, this approach is essential

### Relevance to Modern Work
- [ ] **Collaboration foundation** in modern workplace
- [ ] Company workflows (approval, review, audit) = similar to software engineering
- [ ] Software engineering ↔ Management science: mutual influence
  - Management learns from software engineering
  - Software engineering changes with management
- [ ] Example: Alibaba's "middle platform" (中台) - architecture problem → management approach
- [ ] **Learning PM = Learning modern knowledge worker practices**

### What Makes a Good Digital Project?
- [ ] **Key questions your projects should answer:**
  - **Maintainable?** Can you understand your code in 6 months? Will it become obsolete?
  - **Extensible?** Can it grow? New dataset → same architecture, or start over?
  - **Auditable?** Can you verify every step?
  - **Explainable?** Can you explain how it works?
  - **Reproducible?** Can it be run again?
  - **Decoupled?** Are components independent?

### Waterfall vs Agile
- [ ] Will compare these two approaches
- [ ] Why we use Agile (Phases 1-3 iterative loop)

---

## Part 1: Quick Reading Discussion (10 min)

- [ ] Ben Brumfield, "The Website is the Archival Finding Aid"
- [ ] Andreas Fickers, "New Digital Public History"
- [ ] Keep it brief, focus on key takeaways

---

## Part 2: Student Project Sharing (40-60 min)

- [ ] Select students who didn't present last week
- [ ] Each student presents their Week 7 project
- [ ] Discuss challenges and solutions

**Students selected:**
- [ ] Student 1:
- [ ] Student 2:
- [ ] Student 3:
- [ ] Student 4:

---

## Part 3: Live Demo & Workshop (1h 15min - 1h 35min)

### 1. Introduction to DH Workspace (5 min)

- [ ] Show the workspace structure
- [ ] Explain monorepo within monorepo concept
- [ ] Three-layer architecture: research / data / code
- [ ] This is a template for their projects

### 2. AI Basics (15 min)

**Model Selection**
- [ ] Different AIs excel at different things
  - Example (Oct 2025): GPT-5 for complex reasoning, Claude for coding
- [ ] Each model has different modes/strengths
  - ChatGPT-5: different variants
  - Claude: extended thinking modes
- [ ] Know how to control AI "strength"/effort level

**Prompting - DO's**
- [ ] Be clear and specific
- [ ] Longer is better than shorter (provide context)
- [ ] When uncertain, discuss first (Discussion > Direction)
- [ ] State clear expectations

**Provide Tools**
- [ ] Give AI access to tools (MCP, etc.)
- [ ] Enable programmatic tools for data processing

**DON'Ts - Trust Issues**
- [ ] Don't trust AI's judgment of your opinions
  - AI is overflattering, too eager to please
  - Will over-agree
  - Classic example: "You are absolutely right." (it's a meme!)

**DON'Ts - Hallucination**
- [ ] Don't trust AI blindly
- [ ] AI fabricates plausible information
- [ ] Always verify critical outputs

**DON'Ts - Data Processing ⚠️ CRITICAL**
- [ ] **NEVER let AI process data directly**
- [ ] Unless you have verification process
- [ ] Always use programmatic tools instead
- [ ] Explain what "programmatic" means
- [ ] Why: Data falsification = career-ending mistake
  - People lose jobs over this
  - Most serious professional error
  - Can happen without you noticing

**DON'Ts - Self-Evaluation**
- [ ] Don't trust AI's evaluation of its own work
- [ ] Use external tools for verification
- [ ] Apply hard standards/metrics
- [ ] Better: different rule set or new conversation thread

**Key Principle**
- [ ] You are the orchestrator. AI is the tool.

### 3. Research Ethics (10 min)

**Core Principle: Rigor**
- [ ] Everything must be traceable and verifiable

**Most Important Rule**
- [ ] Everything must have a source and be traceable
  - Citations - every quote, every reference
  - Data - every dataset, every data point
  - Data transformation processes - every step

**Two Core Concepts**
- [ ] **Traceability** - can trace back to source, complete chain of custody
- [ ] **Verifiability** - can be verified by others, evidence available

**Data Handling**
- [ ] AI agents absolutely cannot touch data directly
- [ ] Must use programmatic means with records
- [ ] Every data transformation must be documented
- [ ] Every step reproducible through code
- [ ] Ensures traceability and verifiability

**Key Principle**
- [ ] If you can't trace it and verify it, it doesn't belong in research

### 4. Code Styles (5 min)

**Core Principle**
- [ ] All code must be cleanly written

**DON'Ts**
- [ ] No monkey patching
- [ ] No spaghetti code
- [ ] No overengineering

**DO's - Three Principles**
- [ ] **Maintainability** - easy to maintain, future you understands it
- [ ] **Extensibility** - easy to extend, new features fit naturally
- [ ] **Modularization** - clear modules, each with one purpose

**Key Principle**
- [ ] Clean code is code that others (and future you) can understand and modify

### 5. Development Process (15 min)

**Phase 1: Ideation**
- [ ] Discuss **what** you want to build, not **how**
- [ ] Output: Design document / PRD

**Phase 2: Planning**
- [ ] Decide **how** to do it
- [ ] Break into concrete, actionable steps
- [ ] Output: Implementation document (actionable + trackable)

**Phase 3: Prototyping**
- [ ] Build and test the prototype
- [ ] Can loop back to Ideation/Planning
- [ ] Output: Prototype

**Important Concept**
- [ ] **Phases 1-3 form an iterative loop = Agile development**
- [ ] Discuss: What is Agile? How is it different from Waterfall?

**Phase 4: Rewriting/Refactoring**
- [ ] Enter once prototype is stable and satisfactory
- [ ] Output: Robust code

**Phase 5: Consolidating**
- [ ] Test to solidify results
- [ ] Prevent regressions
- [ ] Output: Tested, stable codebase

**Key Principle**
- [ ] Move through phases deliberately
- [ ] Don't skip to implementation before proper planning

### 6. Version Control Basics (10 min)

**What is Version Control?**
- [ ] Time machine for your code
- [ ] Track every change
- [ ] Never lose work

**Basic Git Workflow**
- [ ] `init` → `add` → `commit` → `push`
- [ ] Three stages: Working directory → Staging → Repository

**Commit Practices - DO's**
- [ ] Commit often - small, focused commits
- [ ] Meaningful messages - explain why, not just what
- [ ] One logical change per commit
- [ ] Commit working code, not broken code

**DON'Ts**
- [ ] Don't commit secrets (passwords, API keys, .env files)
- [ ] Don't commit generated files (build outputs, node_modules)
- [ ] Don't rewrite published history (no force push to shared branches)

**Large Files - Clarification**
- [ ] DON'T commit: Derived/generated large files (can be regenerated)
- [ ] DO commit (with Git LFS): Large source files (original data, databases)
  - Use Git LFS for files over ~100MB
- [ ] Think: What can be regenerated vs. what is original source?

**Remote Repository (GitHub/GitLab)**
- [ ] Backup your work
- [ ] Collaborate with others
- [ ] Share your project

**Key Principle**
- [ ] Version control ensures traceability and reproducibility

### 7. Live Demo - Practical Demonstration (30-40 min)

**Demo Project Setup**
- [ ] Show the DH Workspace structure in action
- [ ] Walk through a real example project

**Demonstrate the Five Phases**
- [ ] Phase 1: Ideation - Design document creation
- [ ] Phase 2: Planning - Implementation plan
- [ ] Phase 3: Prototyping - Build something
  - [ ] Show AI collaboration
  - [ ] Show programmatic data handling
  - [ ] Show version control in action
- [ ] Phase 4: Refactoring - Improve the code
- [ ] Phase 5: Consolidating - Test and verify

**Key Points to Emphasize During Demo**
- [ ] AI as orchestrator (you direct, AI executes)
- [ ] Never let AI touch data directly
- [ ] Use programmatic tools with records
- [ ] Commit frequently with good messages
- [ ] Everything is traceable and verifiable

---

## Part 4: Preview - About Annotations (15 min)

- [ ] Introduction to annotation tools and methods
- [ ] Preview Week 9 assignment:
  - Pick one primary + one secondary material
  - Make at least 20 annotations
  - Extract annotations in usable format
- [ ] Tools: Zotero PDF reader, Hypothesis, etc.
- [ ] How to extract and manage annotations

