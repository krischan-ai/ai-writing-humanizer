---
name: ai-writing-humanizer
description: Humanize English and Chinese writing for university assignments, reports, and study notes while preserving facts, academic integrity, and the student's own voice. Use when reducing robotic AI style, avoiding template-like answers, or adapting drafts into natural student-level writing. Not for bypassing AI detection or misrepresenting authorship.
---

# AI Writing Humanizer - University Assignment Mode

A workflow for turning generic AI-style drafts into natural student writing.

## Core goal

Improve authenticity of expression without changing the student's ideas, evidence, or academic meaning.

This skill focuses on:

- reducing repetitive ChatGPT-style structures
- making answers sound like a real university student
- creating wording variation between different drafts
- keeping appropriate academic level
- preserving the user's own reasoning

Do not:

- fabricate personal experience
- add unsupported references
- create false citations
- help misrepresent AI-generated work as independent work

## Assignment workflow

### Step 1: Understand the student's context

Before rewriting, identify:

- course level (undergraduate / postgraduate)
- subject area
- expected answer style
- word limit
- whether the answer is a short response, report, reflection, or analysis

### Step 2: Diagnose AI patterns

Check for:

- generic introductions
- textbook-like definitions when unnecessary
- excessive transitions
- repeated sentence structures
- unnatural vocabulary choices
- over-polished academic tone
- conclusions that add no information

### Step 3: Rewrite with student voice

Prefer:

- clear sentences
- specific examples from the question
- normal university vocabulary
- slightly varied sentence lengths
- direct explanation instead of formal filler

Avoid:

- "It is important to note that..."
- "In today's rapidly changing world..."
- "plays a crucial role"
- "comprehensive analysis"
- "delve into"
- unnecessary three-part lists

## Modes

### student-short-answer

For homework questions and exam preparation.

Rules:

- concise
- direct answer first
- explain only necessary points
- avoid professor-style writing

### student-report

For lab reports and assignments.

Rules:

- maintain academic accuracy
- keep methodology terminology
- avoid exaggerated claims

### explanation-mode

For tutoring.

Rules:

- explain concepts naturally
- use examples
- avoid producing a final submission immediately when learning is the goal

## Anti-template variation

When multiple students may answer the same question:

1. Change sentence structure.
2. Use different but accurate examples.
3. Avoid common ChatGPT paragraph patterns.
4. Keep the same academic requirement.
5. Preserve the student's preferred wording when available.

Example:

Generic:

"The response variable is measured by asking participants to rate the softness of cooked rice on a scale from 1 to 10."

Student style:

"The response variable is the perceived softness of the cooked rice. A group of participants will taste each sample and give a score between 1 and 10. The average score will be used to compare different cooking conditions."

## Output format

When requested to humanize:

```markdown
## Main changes
- ...

## Revised answer
...

## Why this sounds more natural
- ...
```

## Language rules

### English

- Prefer simple academic English.
- Use concrete verbs.
- Remove unnecessary nominalizations.
- Avoid repeating "important", "significant", "various", "different".

### Chinese

- Avoid translation-style Chinese.
- Use natural student expressions.
- Do not force four-character summaries.
- Avoid excessive "通过...从而...实现..." structures.

## Final check

Before returning:

1. Are facts unchanged?
2. Are examples supported?
3. Does it sound like a student rather than a textbook?
4. Is the wording different from a typical AI template?
5. Is the academic requirement still satisfied?
