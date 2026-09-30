# Claude Skills

A structured collection of reusable **Claude Skills** designed to provide specialized instructions, workflows, and guidelines for different types of tasks.

Each skill is maintained as an independent module containing a `SKILL.md` file. The skills are designed to be modular, reusable, and easy to extend as new use cases are identified.

---

## 📁 Repository Structure

```text
Skills/
│
├── human-writing/
│   └── SKILL.md
│
├── presentation-skills/
│   └── SKILL.md
│
├── storytelling-skill/
│   └── SKILL.md
│
└── README.md
```

---

## 🧩 What Are Claude Skills?

Claude Skills are reusable instruction sets that provide Claude with specialized knowledge and behavioral guidelines for a particular task or workflow.

Instead of repeatedly providing detailed instructions in every conversation, those instructions can be packaged into a skill and reused whenever the corresponding task requires them.

A skill can define:

* Task-specific instructions
* Workflows and processes
* Rules and constraints
* Writing guidelines
* Quality standards
* Examples
* Expected output formats
* Domain-specific behavior

The goal is to make Claude's behavior more **consistent, reliable, and specialized** across different tasks.

---

## 🎯 Purpose

This repository is intended to serve as a growing library of specialized Claude Skills.

The current collection focuses on three areas:

1. **Human-like writing**
2. **Presentation development**
3. **Storytelling and narrative development**

Each skill is separated into its own directory so that it can be developed, maintained, and improved independently.

---

# 🛠️ Available Skills

## 1. Human Writing

**Directory:** `human-writing/`

**Instruction file:** `human-writing/SKILL.md`

The **Human Writing** skill focuses on producing writing that feels natural, authentic, and context-aware.

It is intended to help Claude avoid unnecessarily robotic, repetitive, or overly polished language while maintaining clarity and correctness.

### Key areas

* Natural language
* Human-like tone
* Voice preservation
* Readability
* Tone adaptation
* Context-aware rewriting
* Conversational writing
* Avoiding repetitive AI-style phrasing

### Example use cases

```text
Rewrite this paragraph naturally.
Make this email sound more human.
Keep my writing style but improve the grammar.
Make this explanation less robotic.
Rewrite this without making it sound AI-generated.
```

---

# 2. Presentation Skills

**Directory:** `presentation-skills/`

**Instruction file:** `presentation-skills/SKILL.md`

The **Presentation Skills** module provides structured guidance for creating effective presentations.

It focuses on turning information into a clear and logical presentation while maintaining appropriate information density and audience engagement.

### Key areas

* Presentation structure
* Slide organization
* Information hierarchy
* Content prioritization
* Visual storytelling
* Audience engagement
* Slide readability
* Professional communication
* Narrative flow

### Example use cases

```text
Create a presentation structure for this topic.
Turn this research into presentation slides.
Improve the flow of these slides.
Reduce the text on this slide.
Create a professional presentation outline.
```

---

# 3. Storytelling Skill

**Directory:** `storytelling-skill/`

**Instruction file:** `storytelling-skill/SKILL.md`

The **Storytelling Skill** is designed for creative-writing and narrative-development workflows.

It provides guidance for building compelling stories while maintaining consistency in characters, plot, pacing, tone, and emotional progression.

### Key areas

* Story structure
* Plot development
* Character development
* Character arcs
* Scene construction
* Dialogue
* Conflict
* Suspense
* Pacing
* Emotional progression
* Narrative consistency
* World-building

### Example use cases

```text
Develop this story idea further.
Improve the pacing of this chapter.
Create a stronger character arc.
Rewrite this scene while preserving the plot.
Build suspense before the reveal.
Improve the dialogue between these characters.
```

---

# 📂 Skill Architecture

Each skill follows a simple directory structure:

```text
skill-name/
└── SKILL.md
```

The `SKILL.md` file acts as the central instruction file for that skill.

A typical skill can contain sections such as:

```text
# Skill Name

## Purpose

## Scope

## Core Principles

## Instructions

## Workflow

## Guidelines

## Examples

## Constraints

## Output Requirements
```

The exact structure can vary depending on the requirements of the individual skill.

---

# 🔄 How Skills Work

The general workflow can be represented as:

```text
User Task
    │
    ▼
Relevant Skill
    │
    ▼
SKILL.md
    │
    ▼
Specialized Instructions
    │
    ▼
Claude
    │
    ▼
Task-specific Response
```

Instead of treating every task the same way, skills provide Claude with additional context and instructions relevant to the task being performed.

---

# 🧱 Design Principles

The repository follows several principles when creating and maintaining skills.

## Modularity

Each skill should focus on a specific category of tasks.

A skill should avoid unnecessary dependencies on unrelated skills.

---

## Reusability

Instructions should be written so that they can be applied across multiple conversations and different examples within the same task category.

---

## Clarity

Instructions should be explicit and structured.

Avoid ambiguous instructions when a more precise rule can be provided.

---

## Consistency

A skill should encourage predictable behavior across similar tasks while still allowing appropriate adaptation to context.

---

## Maintainability

Skills should remain easy to read, update, test, and extend.

Large collections of unrelated instructions should be separated into appropriate skills rather than placed into a single file.

---

## Context Awareness

Skills should guide Claude to consider the user's objective, context, audience, and constraints instead of applying instructions mechanically.

---

# ➕ Adding a New Skill

To add a new skill, create a new directory inside the repository.

For example:

```text
Skills/
├── human-writing/
├── presentation-skills/
├── storytelling-skill/
└── research-skill/
    └── SKILL.md
```

### Recommended process

### 1. Create the skill directory

```bash
mkdir research-skill
```

### 2. Create the instruction file

```text
research-skill/
└── SKILL.md
```

### 3. Define the purpose

Clearly explain what the skill is designed to accomplish.

### 4. Define the instructions

Document the behavior Claude should follow when applying the skill.

### 5. Add examples

Include examples when they make the intended behavior clearer.

### 6. Define constraints

Document important limitations, rules, or situations where the skill should or should not be applied.

### 7. Test the skill

Use representative prompts to verify that the skill behaves as intended.

### 8. Update the README

Add the new skill to the repository structure and skills catalog.

---

# 🧪 Testing Skills

Skills should be tested against realistic tasks rather than only simple examples.

A basic testing process can include:

```text
Input
  ↓
Apply Skill
  ↓
Review Output
  ↓
Check Against Requirements
  ↓
Identify Problems
  ↓
Update SKILL.md
  ↓
Retest
```

When evaluating a skill, consider:

* Does Claude follow the intended instructions?
* Is the output consistent?
* Does it preserve relevant user context?
* Does it avoid unnecessary behavior?
* Does it handle edge cases?
* Does the output meet the expected format?
* Does the skill improve the task compared with a general response?

---

# 🗃️ Current Skill Catalog

| Skill                   | Directory              | Primary Focus                              |
| ----------------------- | ---------------------- | ------------------------------------------ |
| **Human Writing**       | `human-writing/`       | Natural, authentic, context-aware writing  |
| **Presentation Skills** | `presentation-skills/` | Presentation structure and communication   |
| **Storytelling Skill**  | `storytelling-skill/`  | Narrative development and creative writing |

---

# 🛣️ Future Skills

The repository can be expanded with additional specialized skills as new workflows are identified.

Potential additions include:

```text
research-skill/
coding-skill/
data-analysis/
technical-writing/
documentation/
content-strategy/
creative-writing/
marketing-writing/
resume-writing/
```

Future skills should follow the same modular approach and include their own `SKILL.md`.

---

# 🤝 Contributing

When adding or modifying a skill:

1. Keep the skill focused on a clearly defined purpose.
2. Use clear and actionable instructions.
3. Avoid duplicating instructions unnecessarily.
4. Include examples where useful.
5. Test changes against representative tasks.
6. Keep the repository structure organized.
7. Update the root `README.md` when adding a new skill.

---

# 📌 Repository Guidelines

When creating new skills, prefer:

* Clear directory names
* One primary `SKILL.md` per skill
* Structured Markdown
* Explicit instructions
* Practical examples
* Minimal redundancy
* Clear scope and constraints

Avoid:

* Unrelated instructions inside a skill
* Contradictory rules
* Excessive repetition
* Unclear behavioral requirements
* Instructions that depend on undocumented context

---

# 📄 License

This project does not currently specify a license.

If this repository is intended for public distribution, add an appropriate license file and update this section accordingly.

---

# 👤 Maintainer

**Sanika Chougule**

This repository is maintained as a collection of reusable Claude Skills for specialized AI-assisted workflows.

---

## 📚 Skill Documentation

For detailed instructions and implementation guidance, refer to the individual skill files:

* [`human-writing/SKILL.md`](human-writing/SKILL.md)
* [`presentation-skills/SKILL.md`](presentation-skills/SKILL.md)
* [`storytelling-skill/SKILL.md`](storytelling-skill/SKILL.md)
