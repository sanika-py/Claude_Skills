# Claude Skills

A curated collection of custom **Claude Skills** designed to improve Claude's performance for specific workflows, writing styles, research tasks, presentations, development, and professional use cases.

These skills provide Claude with reusable instructions, behavioral guidelines, workflows, and domain-specific context so that it can produce more consistent and useful results.

---

## ✨ What Are Claude Skills?

Claude Skills are reusable instruction sets that teach Claude **how to approach a specific type of task**.

Instead of repeatedly explaining:

* how you want something written
* what tone should be used
* how research should be structured
* how presentations should be created
* what standards should be followed

you can create a Skill once and reuse it whenever that workflow is needed.

### Example

Instead of prompting:

> "Write this like a CEO, make it sound natural, use storytelling, don't make it robotic, and keep the audience engaged."

A dedicated **Storytelling Skill** can automatically apply those principles whenever Claude is asked to create a story.

---

## 📁 Repository Structure

```text
claude-skills/
│
├── README.md
│
├── skills/
│   │
│   ├── storytelling/
│   │   ├── SKILL.md
│   │   └── README.md
│   │
│   ├── presentation/
│   │   ├── SKILL.md
│   │   └── README.md
│   │
│   ├── research/
│   │   ├── SKILL.md
│   │   └── README.md
│   │
│   └── ...
│
├── examples/
│   ├── storytelling/
│   ├── presentation/
│   └── research/
│
├── templates/
│   └── SKILL_TEMPLATE.md
│
└── LICENSE
```

---

## 🧩 Available Skills

| Skill                | Purpose                                                           |
| -------------------- | ----------------------------------------------------------------- |
| 🎭 Storytelling      | Creates natural, engaging stories with strong narrative structure |
| 📊 Presentation      | Helps create structured and audience-focused presentations        |
| 🔎 Research          | Produces organized, evidence-based research                       |
| ✍️ Writing           | Improves clarity, tone, structure, and readability                |
| 💼 CEO Communication | Helps create concise executive-level communication                |
| 🎤 Speaker Content   | Structures content for speakers, panels, and events               |

> More skills will be added over time.

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/<your-username>/claude-skills.git
```

### 2. Open the repository

```bash
cd claude-skills
```

### 3. Choose a Skill

Navigate to:

```text
skills/<skill-name>/
```

Each skill contains its own `SKILL.md` file with the instructions required by Claude.

### 4. Use the Skill

Copy the skill instructions into your Claude workflow or use them according to your Claude Skills setup.

---

## 🛠️ Creating a New Skill

Use the provided template:

```text
templates/SKILL_TEMPLATE.md
```

A good skill should clearly define:

### 1. Purpose

Explain what the skill is designed to accomplish.

### 2. Role

Define how Claude should behave when using the skill.

### 3. Instructions

Provide clear rules Claude should follow.

### 4. Workflow

Describe how Claude should approach the task step-by-step.

### 5. Tone & Style

Specify the desired communication style.

### 6. Constraints

Define what Claude should avoid.

### 7. Output Format

Describe the expected structure of the final response.

---

## 📄 Skill Structure

A typical `SKILL.md` follows this structure:

```markdown
# Skill Name

## Description

A short explanation of what this skill does.

## Purpose

What problem does this skill solve?

## Role

Define Claude's role when using this skill.

## Core Instructions

- Instruction 1
- Instruction 2
- Instruction 3

## Workflow

1. Understand the request.
2. Identify the objective.
3. Apply the relevant framework.
4. Produce the final output.

## Tone

- Natural
- Clear
- Human
- Context-aware

## Avoid

- Generic responses
- Repetitive language
- Unnecessary filler

## Output

Define the expected response format.
```

---

## 🎯 Design Principles

These skills are built around a few principles:

### Context over Templates

Skills should help Claude understand **why** something should be written or created instead of simply forcing a fixed template.

### Natural Output

The goal is to produce content that feels:

* human
* contextual
* intentional
* audience-aware

rather than obviously AI-generated.

### Reusable Workflows

A skill should solve a recurring problem and be reusable across multiple projects.

### Clear Instructions

Skills should use precise instructions instead of vague requests such as:

> "Make it better."

Instead:

> "Prioritize clarity, remove unnecessary filler, preserve the original meaning, and adapt the tone to the intended audience."

---

## 🧪 Examples

Example skills can be found inside:

```text
examples/
```

These demonstrate how each skill changes Claude's approach to a task.

---

## 🤝 Contributing

Contributions are welcome.

To contribute:

1. Fork the repository.
2. Create a new branch.

```bash
git checkout -b feature/new-skill
```

3. Add or improve a skill.
4. Test the skill with multiple prompts.
5. Update the relevant documentation.
6. Commit your changes.

```bash
git commit -m "Add <skill-name> skill"
```

7. Push your branch.

```bash
git push origin feature/new-skill
```

8. Open a Pull Request.

### Contribution Guidelines

A new skill should:

* solve a clear problem
* have a specific purpose
* contain reusable instructions
* avoid unnecessary complexity
* include examples where useful
* follow the repository's structure

---

## 📌 Skill Quality Checklist

Before submitting a Skill, verify:

* [ ] The purpose is clearly defined
* [ ] Instructions are unambiguous
* [ ] The intended behavior is explained
* [ ] Tone and style are specified
* [ ] Unwanted behavior is documented
* [ ] Expected output is defined
* [ ] The skill works across multiple prompts
* [ ] Examples are provided where appropriate
* [ ] Documentation is included

---

## 🗺️ Roadmap

Planned improvements include:

* [ ] More writing skills
* [ ] Research and analysis skills
* [ ] Developer-focused skills
* [ ] Presentation and pitch skills
* [ ] Business communication skills
* [ ] Industry-specific skills
* [ ] Skill testing framework
* [ ] Skill quality benchmarks
* [ ] Community-contributed skills

---

## 📜 License

This repository is licensed under the **MIT License** unless otherwise specified.

See [`LICENSE`](LICENSE) for details.

---

## ⭐ Support

If you find these skills useful:

* ⭐ Star the repository
* 🐛 Report issues
* 💡 Suggest new skills
* 🤝 Contribute improvements

---

## 👤 Author

**Sanika Chougule**

AI & Data Science Student
Interested in AI, developer tools, automation, and practical applications of generative AI.

---

> **Build once. Instruct clearly. Reuse everywhere.**
