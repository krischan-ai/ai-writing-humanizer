# Answer Diversity Workflow

Generate multiple academically correct answer styles while keeping the same underlying knowledge.

## Purpose

Different students may answer the same question with similar AI-generated wording. This workflow creates natural variation in explanation style while preserving accuracy.

Do not use this workflow to fabricate knowledge or change the required answer.

## Invocation

```text
/diversify <answer-or-question> [--subject statistics|lab|business|general] [--versions 3]
```

## Generation rules

Create different versions by changing:

- sentence structure
- explanation order
- example choice
- level of detail
- wording preference

Do not change:

- facts
- formulas
- definitions
- required conclusions

## Default profiles

### Version A: Normal student

Style:

- clear
- simple
- natural
- suitable for average university submission

### Version B: Analytical student

Style:

- stronger reasoning
- clearer connections between concepts
- slightly more technical vocabulary

### Version C: Concise student

Style:

- short
- direct
- suitable for quizzes or exam answers

## Subject adjustments

### Statistics

Keep:

- variable names
- statistical interpretation
- calculation logic

Vary:

- explanation order
- wording of conclusions

### Experimental design

Possible structures:

1. Factor → treatment → response variable
2. Research goal → measurement → comparison
3. Practical example → experimental setup

### Business case

Possible structures:

1. Problem → evidence → impact
2. Situation → analysis → recommendation
3. Concept → application → result

## Similarity review

Before returning versions, check:

- Are introductions different?
- Are sentence patterns different?
- Are examples not copied?
- Are all versions still correct?

## Output

```markdown
## Version A
...

## Version B
...

## Version C
...

## Difference summary
- Structure:
- Tone:
- Detail level:
```
