# Claude Prompt Engineering
## Full TOC Draft - Tik TOC Architecture

**Working title:** Claude Prompt Engineering: Specifications for Better Human-AI Work  
**Author:** Humanitarians AI Incorporated  
**Publisher:** Humanitarians AI Incorporated  
**Document:** Full TOC Draft  
**Version:** 1.0  
**Status:** Architecture draft - ready for outline expansion and chapter drafting  

---

## Document Structure

1. Book Concept and Thesis
2. Learner Profile
3. Book Type and Deployment Specification
4. Field Positioning
5. Three-Act Learning Arc
6. Prerequisite Map
7. Chapter-by-Chapter TOC
8. Chapter Anatomy Template
9. Case Study Strategy
10. Hard Topics, Contested Claims, Aging Risk
11. Adoption Risk Register
12. Open Questions

---

# Part 1 - Book Concept and Thesis

## Book Concept Summary

This book teaches Claude users how to turn vague requests into inspectable specifications: task, context, constraints, examples, output format, evaluation criteria, and revision loop. It fills the gap between prompt-tip lists and full AI engineering texts. It succeeds when the reader can design prompts that make the work clear enough to supervise, test, revise, and reuse.

## One-Sentence Logline

Prompt engineering is not trick wording; it is the discipline of specifying work so Claude can do the right part and the human can judge the result.

## Central Thesis

This book argues that good Claude prompting is specification design. The point is not to coax the model with clever phrasing but to define the job, provide the right context, constrain the output, expose assumptions, require reasoning artifacts when useful, and build a review loop. A good prompt makes both the AI's task and the human's review easier.

## Thesis Test

- Act One replaces prompt tricks with specification thinking.
- Act Two teaches reusable prompt components and workflows.
- Act Three applies the discipline to writing, research, analysis, education, coding-adjacent work, and agentic tools.

**Thesis test:** Pass.

---

# Part 2 - Learner Profile

## Primary Reader

A student, educator, researcher, analyst, writer, or professional who uses Claude but gets inconsistent results. They know how to ask questions, but they do not yet know how to structure context, constraints, examples, and evaluation criteria so the work can be repeated and improved.

## Prior Knowledge Assumed

- Basic Claude chat use
- Ability to describe a desired output
- Domain knowledge in the reader's own work

## Prior Knowledge Not Assumed

- Prompt engineering jargon
- Programming
- Agentic workflows
- Model evaluation theory
- Claude Code

## Prior Misconceptions

1. "Prompt engineering is about secret phrases" - it is about work specification.
2. "Longer prompts are better" - relevant structure beats bulk.
3. "Claude should infer what I mean" - inference is where many failures enter.
4. "A good prompt removes the need to review" - a good prompt makes review possible.

## Motivation Type

**Primary:** Professional and academic productivity.  
**Secondary:** Better AI literacy.  
**Not primary:** Building production AI systems.

---

# Part 3 - Book Type and Deployment Specification

## Book Type

**Primary type:** Practitioner handbook.  
**Secondary type:** Short course text for AI literacy, writing, research, or professional communication.  
**Not:** A list of hacks, a model internals book, or a developer-only guide.

## Primary Adoption Context

AI literacy courses, faculty/student workshops, workplace training, research methods support, and self-directed Claude users.

## Secondary Adoption Context

Writing courses, HCI/project studios, education courses, data-analysis support labs, and professional development.

## What This Book Is Not Designed For

- Readers seeking jailbreaks or manipulation
- Readers building production LLM applications
- Fully automated workflows with no human review
- Vendor-neutral model-comparison research

---

# Part 4 - Field Positioning

## Comparable Texts and Gaps

**Prompt-tip lists** give examples but not transferable principles.  
**General prompt engineering books** often treat all models and contexts alike.  
**Claude Code books** focus on agentic coding. This book focuses on Claude conversation and specification patterns that transfer into Code and Cowork.

## Positioning Statement

Unlike prompt collections that give readers phrases to copy, this book teaches prompt engineering as a reusable specification discipline for Claude users who need reliable drafts, analysis, critique, research support, and revision workflows.

---

# Part 5 - Three-Act Learning Arc

## Act One - From Request to Specification

The reader learns why vague prompting fails and how to define work in terms of task, context, constraints, and success criteria.

## Act Two - Reusable Prompt Patterns

The reader learns patterns for critique, rewriting, research, extraction, analysis, tutoring, planning, and decision support.

## Act Three - Workflow Integration

The reader builds reusable prompt systems, review loops, and handoff patterns for Claude AI, Claude Code, and Claude Cowork.

## Arc Statement

This book takes the reader from casual prompting to repeatable Claude workflow design by first teaching specification, then prompt patterns, then supervised reuse across real work.

---

# Part 6 - Prerequisite Map

| Prerequisite | Safe to Assume? | Where Introduced |
|---|---|---|
| Basic Claude chat use | Probably | Introduction |
| Task/context distinction | No | Chapter 1 |
| Output format control | No | Chapter 2 |
| Examples as guidance | No | Chapter 4 |
| Evaluation criteria | No | Chapter 5 |
| Revision loops | No | Chapter 6 |
| Agentic tools | No | Chapter 11 |

**Front-loading decision:** Chapter 1 teaches the prompt as a work order, not a magic sentence.

---

# Part 7 - Chapter-by-Chapter TOC

## Introduction - The Prompt Is the Work Order

**Capability built:** Understand prompting as specification rather than phrasing.

The introduction reframes prompt engineering around the human responsibility to define the work.

## Chapter 1 - Anatomy of a Claude Prompt

**Capability built:** Build prompts with task, context, constraints, output, and evaluation criteria.

The chapter introduces the core template and shows how each component prevents a common failure.

## Chapter 2 - Context: What Claude Needs and What It Does Not

**Capability built:** Provide enough context without dumping irrelevant material.

Topics include source excerpts, background, audience, assumptions, exclusions, and context hygiene.

## Chapter 3 - Constraints and Boundaries

**Capability built:** Use constraints to protect accuracy, tone, scope, and ethics.

Examples include word count, evidence rules, citation limits, "do not invent," privacy boundaries, and uncertainty disclosure.

## Chapter 4 - Examples, Counterexamples, and Style

**Capability built:** Use examples to shape output without overfitting the task.

The reader learns few-shot examples, anti-examples, voice samples, and style boundaries.

## Chapter 5 - Evaluation Criteria Before Output

**Capability built:** Tell Claude how the work will be judged before it produces the work.

The chapter teaches rubrics, acceptance tests, source checks, calculation checks, and "what would make this wrong?"

## Chapter 6 - Iteration and Revision Loops

**Capability built:** Improve outputs through structured critique rather than vague follow-up.

Patterns include diagnose, revise, compare, explain changes, preserve constraints, and stop when the evidence is insufficient.

## Chapter 7 - Prompts for Research and Literature Work

**Capability built:** Use Claude for research leads, summaries, matrices, and gap analysis without treating it as a citation authority.

The chapter emphasizes verification, source tracing, and distinguishing leads from evidence.

## Chapter 8 - Prompts for Writing and Editing

**Capability built:** Use Claude for drafting, restructuring, line editing, and audience adaptation while preserving authorial claim ownership.

Examples include abstracts, introductions, methods clarity, discussion calibration, and reviewer-response drafts.

## Chapter 9 - Prompts for Data and Analysis Support

**Capability built:** Ask Claude to help plan and interpret analysis without surrendering statistical judgment.

Topics include variable definitions, test selection, assumption checks, code explanation, table interpretation, and limitations.

## Chapter 10 - Prompts for Teaching and Learning

**Capability built:** Design prompts that preserve cognitive labor.

The reader learns tutoring prompts, Socratic prompts, misconception checks, feedback prompts, and self-assessment loops.

## Chapter 11 - Prompts as Handoffs to Claude Code and Cowork

**Capability built:** Convert conversational prompts into action-ready specifications.

The chapter covers file boundaries, terminal/code tasks, folder workflows, approval gates, and verification instructions.

## Chapter 12 - Building a Reusable Prompt Library

**Capability built:** Turn successful prompts into maintained workflow assets.

The reader creates prompt cards with purpose, inputs, constraints, output format, review criteria, and revision history.

## Chapter 13 - Capstone: One Workflow, Three Prompt Passes

**Capability built:** Design, test, revise, and document a prompt workflow.

The reader chooses a real recurring task, writes the first prompt, evaluates output, revises the specification, and saves the reusable version.

---

# Part 8 - Chapter Anatomy Template

Each chapter should include:

1. Prompt failure example
2. Capability statement
3. Specification principle
4. Before/after prompt
5. Claude output audit
6. Revision pattern
7. Reusable template
8. Transfer exercise

---

# Part 9 - Case Study Strategy

| Case Type | Chapters | Purpose |
|---|---|---|
| Research summary | 2, 7 | Context and verification |
| Manuscript revision | 5, 8 | Evaluation criteria and author ownership |
| Data-analysis planning | 9 | Statistical support boundaries |
| Tutoring prompt | 10 | Cognitive labor protection |
| Cowork/Code handoff | 11 | Action-ready specification |

---

# Part 10 - Hard Topics and Aging Risk

## Hard Chapters

- **Chapter 7:** Must avoid presenting Claude as a source authority.
- **Chapter 9:** Must distinguish analysis support from statistical decision-making.
- **Chapter 11:** Must bridge to agentic tools without becoming a coding book.

## Aging Risk

High-aging-risk content includes model names, product-specific interfaces, and current Claude features. Stable content includes task specification, context discipline, constraints, evaluation criteria, examples, and revision loops.

---

# Part 11 - Adoption Risk Register

| Risk | Likelihood | Impact | Mitigation |
|---|---|---|---|
| Readers expect prompt hacks | High | Medium | Reframe as specification in the introduction |
| Examples become stale | Medium | Medium | Keep patterns domain-transferable |
| Overtrust of outputs | High | High | Put evaluation criteria before output |
| Too much abstraction | Medium | Medium | Use before/after prompts in every chapter |
| Too Claude-specific for some courses | Medium | Low | Emphasize transferable principles |

---

# Part 12 - Open Questions

1. Should this book include a downloadable prompt-card library?
2. Should each chapter include Claude AI, Code, and Cowork variants?
3. Should research prompting and writing prompting be combined or separate?
4. Should the capstone be academic, workplace, or learner-selected?
