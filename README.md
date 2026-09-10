# Foundry

> A methodology for learning through understanding, building, experimentation, and contribution to Open Source.

Foundry is not a course, not a platform that lists project ideas, not a list of tutorials, and not a project ideas generator.

**Core idea:**

> Foundry doesn't tell you what to build. It gives you a methodology for figuring out what you want to understand, how to study it, when building is the right way to learn, how to prove you learned it, and what to do with that knowledge afterward.

---

## The Problem

Many programmers learn this way:

```
Tutorial → Copy Code → Finish Project → Move to another Tutorial
```

A person may end up able to run and use a technology without necessarily knowing why it was designed that way, what the alternatives are, what its constraints are, how it works internally, why certain decisions were made, what happens when it fails, or whether they could build part of it themselves.

The problem isn't a lack of learning resources. The problem is **turning theoretical knowledge into deep practical understanding**.

---

## The Core Cycle

```
                 ┌──────────────┐
                 │  OPEN SOURCE │
                 └──────┬───────┘
                        ↓
                 ┌──────────────┐
                 │  UNDERSTAND  │
                 └──────┬───────┘
                        ↓
                 ┌──────────────┐
                 │     BUILD    │
                 └──────┬───────┘
                        ↓
                 ┌──────────────┐
                 │     LEARN    │
                 └──────┬───────┘
                        ↓
                 ┌──────────────┐
                 │   VALIDATE   │
                 └──────┬───────┘
                        ↓
                ┌───────┴────────┐
                ↓                ↓
            DEVELOP          CONTRIBUTE
                │                │
                └───────┬────────┘
                        ↓
                 OPEN SOURCE
```

The cycle isn't necessarily a straight line. You may go back from building to studying, or discover during experimentation that you didn't fully understand a part:

```
Build → Question → Study → Understand → Build
```

This is normal and part of the method.

---

## What Foundry Is Not

- **Course** — it does not offer a fixed curriculum from start to finish.
- **Tutorial Platform** — it does not say Step 1 → Step 2 → Step 3 and have the user copy the implementation.
- **Project Ideas Generator** — it does not hand out a list like "build a window manager" / "build a compiler" / "build a database".
- **Portfolio Factory** — its goal is not to produce as many projects as possible to pad a CV.
- **Rigid Checklist** — the methodology is not a fixed set of steps to run identically on every project, but a thinking-and-working framework that adapts to the subject.

---

## Principles

1. **Start from what exists** — begin from existing knowledge.
2. **Understand before extending** — understand before trying to build on top of what exists.
3. **Build when building teaches** — build when building is an effective way to learn.
4. **Don't reinvent blindly** — don't rebuild what exists just to rebuild it.
5. **Learn from implementation** — implementation itself is a source of knowledge.
6. **Validate your understanding** — don't rely on the feeling that you understood.
7. **Document what you discover** — turn the experience into knowledge you can return to.
8. **Develop what has value** — if the result deserves to continue, develop it.
9. **Contribute what can help others** — if the knowledge or result is useful to the community, contribute it.
10. **Return to Open Source** — knowledge doesn't stop with the individual.

See [PRINCIPLES.md](./PRINCIPLES.md), [MANIFESTO.md](./MANIFESTO.md), and [METHOD.md](./METHOD.md) for details.

---

## Structure

```
foundry/
│
├── README.md
├── MANIFESTO.md
├── METHOD.md
├── PRINCIPLES.md
├── CONTRIBUTING.md
├── LICENSE
│
├── methodology/
│   ├── define.md
│   ├── explore.md
│   ├── understand.md
│   ├── build.md
│   ├── investigate.md
│   ├── validate.md
│   └── reflection.md
│
├── templates/
│   └── project/
│
├── case-studies/
│   └── README.md
│
└── examples/
    └── README.md
```

This structure is an initial proposal, not a final specification.

`case-studies/` is empty in this version — each Foundry user adds their own project's case studies here.

---

## Foundry Applies the Method to Itself

> Foundry itself should be built using the Foundry methodology.

Foundry starts from what already exists: learning-by-doing methods, project-based learning, research methodologies, Open Source workflows, documentation practices, and existing developer methodologies.

```
Study → Understand → Design Foundry → Build Foundry → Test Foundry → Learn → Improve Foundry → Open Source
```

This makes Foundry its own first case study.
