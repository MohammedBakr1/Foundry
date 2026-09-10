# METHOD

When a programmer enters Foundry, they don't get "build project X." They get a way of working.

> **Note on the two cycles:** the short cycle in README.md (Open Source → Understand → Build → Learn → Validate → Develop/Contribute) is a **high-level summary** of the detailed cycle fully described in this file (8 stages: Define → Explore → Understand → Decide → Build → Investigate → Validate → Reflect). The detailed cycle is the actual working reference — use it when running a real project. The short cycle is only useful for a quick overview or explaining Foundry to someone else.

---

## 1. Open Source — The Starting Point

The programmer doesn't start from nothing. When they want to understand a technology or system, they start by looking at knowledge that already exists:

- Open Source projects
- Standards
- RFCs
- Research papers
- Existing implementations
- Documentation
- Technical discussions
- Community knowledge

**The rule here:**

> Existing solutions are references, not boundaries.

The existence of a ready implementation doesn't mean the programmer is forbidden from reimplementing it. At the same time, rebuilding isn't a goal in itself.

---

## 2. Define

Decide: **"What do I want to understand?"**

---

## 3. Explore

Research: **"What already exists?"**

---

## 4. Understand

Before starting to build, the programmer tries to understand the existing system. They ask:

- How does it work?
- What's the architecture?
- What are the core mechanisms?
- Why was this design chosen?
- What are the trade-offs?
- What are the constraints?
- What cases does it fail on?
- What do I still not understand?

This is where the difference begins between **"Using a technology"** and **"Understanding a technology."**

---

## 5. Decide

Decide: **"What do I need to implement to test my understanding?"**

---

## 6. Build

If the best path to understanding a system is implementing it, the programmer can build it from scratch — even if a ready implementation already exists.

But the goal isn't:

> "I'll reinvent what exists."

The goal:

> "I'll build to understand."

The build might be:

- A complete implementation
- A simplified implementation
- A prototype
- A component
- An experiment
- A subsystem
- An algorithm
- A protocol implementation

The programmer decides the appropriate scope of the build. Foundry doesn't require building the whole system.

### Learn — Learning From Implementation

Things emerge during building that don't always show up from reading alone. The programmer may discover:

- A problem in the design
- A trade-off that wasn't obvious
- A limitation
- An edge case
- Performance different from what was expected
- The reason behind an architectural decision in the original project
- A better way to implement a particular part

At this point, the project becomes a tool for acquiring knowledge, not just a final product.

---

## 7. Investigate

Foundry doesn't settle for **"I understood it."** It encourages turning understanding into something testable:

```
Hypothesis → Implementation → Experiment → Measurement → Comparison → Conclusion
```

Depending on the nature of the project, this can use: experiments, tests, benchmarks, profiling, comparisons, failure cases.

---

## 8. Validate

The goal isn't just finishing the code. The question is: **"How do I know I actually understood it?"**

The answer varies by domain. Proof can be:

- A test suite
- A benchmark
- A working implementation
- An experiment
- A comparison with the original
- Reproduced behavior
- An analysis of failure cases
- Technical documentation

This is how knowledge becomes backed by evidence.

---

## Record — Documenting Knowledge

Every project in Foundry should leave behind a record of knowledge. The following questions are optional — answer whichever ones are actually useful:

- What did I know before starting?
- What did I want to understand?
- What did I study?
- What projects did I refer back to?
- What decisions did I make?
- What failed?
- What did I discover?
- What's the difference between my implementation and the original?
- What did I learn?

This turns the project from mere source code into a **Knowledge Artifact**.

---

## Reflect

Decide: **"What did I learn?"**

---

## Develop or Contribute

After learning, the programmer reaches an important point: **"What will I do with what I learned?"**

### Develop

If what they built has real value, they can keep developing it as an independent project. It might become: software, a tool, a library, a research project, a product, or even a commercial venture.

Foundry doesn't rule out the commercial angle.

### Contribute

Or they can return the knowledge to the community. Contribution isn't necessarily just a pull request. It can be: code, a patch, a feature, an optimization, a tool, documentation, a bug fix, a research result, an architectural idea.

This is how the knowledge returns to **Open Source**.

---

## The Full Cycle (Detailed)

```
             OPEN SOURCE
                  ↓
               DEFINE
                  ↓
               EXPLORE
                  ↓
              UNDERSTAND
                  ↓
                DECIDE
                  ↓
                BUILD
                  ↓
            INVESTIGATE
                  ↓
              VALIDATE
                  ↓
              REFLECT
                  ↓
          ┌───────┴────────┐
          ↓                ↓
       DEVELOP         CONTRIBUTE
          │                │
          └───────┬────────┘
                  ↓
             OPEN SOURCE
```

The cycle isn't necessarily a straight line. The programmer may go back from building to studying, or discover during experimentation that they didn't understand a part, and loop back:

```
Build → Question → Study → Understand → Build
```

This is normal and part of the method.

---

## Foundry Doesn't Choose the Domain for the Programmer

A programmer can use Foundry for: operating systems, networking, compilers, databases, distributed systems, filesystems, graphics, machine learning, computer vision, security, programming languages, web technologies, and more.

The domain isn't Foundry's identity. **The method is the identity.**
