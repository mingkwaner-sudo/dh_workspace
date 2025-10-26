# DH Workspace

A scalable monorepo template for digital history research projects.

## Workshop Information

**Course:** DHG 501 - Introduction to Digital History in Global Asia
**Week:** 8 - Starting Digital Projects and Prototyping
**Date:** October 27, 2025
**Instructor:** Professor Bo An

---

## What is This Workspace?

This workspace demonstrates how to structure digital history projects using modern project management practices. It combines:

- **Research materials** (documents, notes, outputs)
- **Data** (raw and processed)
- **Code** (applications and libraries)

All organized in a way that is:
- Reproducible
- Maintainable
- Scalable
- AI-friendly

---

## Workspace Structure

```
dh_workspace/
├── .git/                       # Git version control
├── .gitignore                  # Files to ignore in git
├── README.md                   # This file - workspace documentation
│
├── agent_docs/                 # Documentation for AI agents working in this workspace
│   └── rules/                  # Rules that AI agents must follow
│       └── general.md          # General workspace rules (orchestration, data integrity, etc.)
│
├── docs/                       # Human-readable documentation
│   └── best_practices/         # Workshop content and best practices
│       └── workshop_content.md # AI basics, project management, five stages
│
└── projects/                   # Container for all research projects (scalable to multiple projects)
    │
    └── first_project/          # Example project (replace with your project name)
        │
        ├── research/           # Research layer - all research-related documents
        │   ├── design/         # Project design and planning
        │   │   └── design_doc.md       # Research questions, methodology, timeline
        │   ├── journal/        # Research journal - track daily progress
        │   │   └── journal_template.md # Template for journal entries
        │   ├── drafts/         # Working drafts of papers and analyses
        │   ├── outputs/        # Final outputs (papers, visualizations, reports)
        │   └── references/     # Bibliography, literature, reference materials
        │
        ├── data/               # Data layer - all project data
        │   ├── raw/            # Original, unmodified data (NEVER edit these!)
        │   └── processed/      # Cleaned and processed data ready for analysis
        │
        └── code/               # Code layer - all technical implementation
            ├── README.md       # Code-specific documentation
            ├── apps/           # Standalone applications (web apps, tools, pipelines)
            └── libs/           # Reusable libraries and utility functions
```

---

## Key Concepts

### Monorepo Within Monorepo

This workspace uses a **monorepo within monorepo** structure:

1. **Outer monorepo** (this workspace): Contains multiple research projects
2. **Inner monorepo** (each project's `code/` folder): Contains apps and libraries for that project

### Three-Layer Architecture

Each project has three interconnected layers:

1. **Research Layer** (`research/`): Design documents, journals, drafts, outputs, references
2. **Data Layer** (`data/`): Raw data and processed data
3. **Code Layer** (`code/`): Applications and libraries

---

## Getting Started

### For Students

1. Navigate to `projects/first_project/`
2. Read `research/design/design_doc.md` to understand project planning
3. Start your research journal in `research/journal/`
4. Follow the best practices in `docs/best_practices/`

### For AI Collaboration

1. Check `agent_docs/rules/` for workspace rules
2. Understand the project structure before making changes
3. Always maintain the three-layer architecture

---

## Quick Start Guide

### 1. Set Up Your Project

```bash
cd projects/first_project
```

### 2. Fill Out Your Design Document

Edit `research/design/design_doc.md` with your research plan.

### 3. Start Your Research Journal

Use `research/journal/journal_template.md` as a template.

### 4. Organize Your Data

- Put original data in `data/raw/`
- Put processed data in `data/processed/`

### 5. Develop Your Code

- Put applications in `code/apps/`
- Put reusable libraries in `code/libs/`

---

## Best Practices

See `docs/best_practices/workshop_content.md` for detailed guidance on:

- AI Basics: How to use AI effectively
- Basic Project Management
- Workspace Design
- The Five Stages of Digital Project Development

---

## Project Guidelines

### Research Layer

- **design/**: Project design and planning documents
- **journal/**: Daily research journal entries
- **drafts/**: Working drafts of papers and analyses
- **outputs/**: Final outputs (papers, visualizations, etc.)
- **references/**: Bibliography and reference materials

### Data Layer

- **raw/**: Original, unmodified data
- **processed/**: Cleaned and processed data ready for analysis

### Code Layer

- **apps/**: Standalone applications
- **libs/**: Reusable libraries and modules

---

## Adding New Projects

To add a new project:

```bash
cd projects
cp -r first_project my_new_project
cd my_new_project
# Update design_doc.md with your project details
```

---

## Version Control

This workspace uses Git for version control. Key practices:

- Commit regularly with meaningful messages
- Keep data files in `.gitignore` if they're too large
- Document your workflow in your research journal

---

## Resources

- **Workshop Content:** `docs/best_practices/workshop_content.md`
- **Agent Rules:** `agent_docs/rules/general.md`
- **Course Materials:** [Link to course page]

---

## Contact

**Instructor:** Professor Bo An
**Email:** [to be announced]
**Office:** HSH322, Ho Sin Hang Building, Lingnan University (Tuen Mun)
**Office Hours:** [to be announced]

---

**Last Updated:** October 26, 2025
