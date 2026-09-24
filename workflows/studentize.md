# Studentize Workflow

## Purpose

Convert a generic draft into a natural university student's explanation style.

`studentize` is different from `humanize`:

- humanize: remove mechanical AI patterns
- studentize: adapt the answer to a realistic student writing level

## Command

```text
/studentize <answer> [--level average|good|concise] [--subject subject]
```

## Workflow

### 1. Identify the answer purpose

Determine:

- homework answer
- exam preparation
- lab report section
- case analysis
- reflection

The writing style should match the purpose.

### 2. Keep the student's knowledge level

Do not make every answer sound like a researcher.

Average student:

- clear explanation
- correct terminology
- simple structure

Good student:

- stronger connection between concepts
- more specific examples
- better reasoning

Concise:

- answer the question directly
- remove unnecessary explanation

### 3. Reduce AI fingerprints

Check for:

- perfect paragraph balance
- repeated transition words
- unnecessary definitions
- overuse of academic vocabulary
- generic conclusion sentences

### 4. Add natural variation

When the same question is common among students:

- change opening sentence
- change explanation order
- use different examples
- avoid standard ChatGPT templates

Do not change the actual answer.

## Subject profiles

### Statistics

Prefer:

- identify variable
- explain measurement
- interpret result

Avoid:

long theoretical explanations when not required.

### Experimental design

Prefer:

"The factor being changed is..."

instead of:

"The independent variable represents the manipulated experimental condition."

### Business

Prefer:

problem → evidence → implication

Avoid:

empty statements about innovation or transformation.

### Reflection

Use:

- specific learning points
- realistic personal perspective

Avoid:

invented experiences.

## Output

```markdown
## Student level
Average / Good / Concise

## Changes made
- ...

## Revised answer
...

## Self-check
- Meaning preserved
- No unsupported facts added
- Natural student style
```
