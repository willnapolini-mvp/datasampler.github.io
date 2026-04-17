# Contributing to BookSummaries

Thank you for your interest in contributing! This dataset grows through community effort.

---

## How to Contribute

### 1. Choose a Book

Pick a book that:
- Is widely recognized and impactful
- Has not already been summarized in the dataset
- Falls within an existing or new category

### 2. Read (or Remember) the Book

Focus on identifying:
- 3-5 moments, examples, or case studies that stood out
- The transferable patterns or principles they reveal
- One core insight that captures the book's essence

### 3. Write the Summary

Follow the strict template:

```markdown
# [Book Title] — Data Sampler Summary

## Core Insight
> One-sentence thesis (10-20 words max)

---

## Representative Samples: [N]

### Sample 1: [Descriptive Title]

**Scenario**: [1-3 sentences describing a specific example from the book]

**Pattern**: [Transferable principle in italics, 1 sentence]

---

### Sample 2: [Descriptive Title]

**Scenario**: [1-3 sentences]

**Pattern**: [Transferable principle]

---

### Sample 3: [Descriptive Title]

**Scenario**: [1-3 sentences]

**Pattern**: [Transferable principle]

---

## Key Generalizations

| Concept | Core Truth |
|---------|-----------|
| [Title] | [One sentence] |
| [Title] | [One sentence] |
| [Title] | [One sentence] |

---

## Conclusion

[2-3 sentences on application]
```

### 4. Add Frontmatter

```yaml
---
title: "Book Title"
author: "Author Name"
summary_length: "~500 words"
samples_count: 3
categories: [Category1, Category2]
date_added: 2026-04-18
source: "Publisher, Year"
---
```

---

## Quality Standards

### Must-Have

| Standard | Description |
|----------|-------------|
| **Concrete scenarios** | Each sample must have a specific, memorable example |
| **Transferable patterns** | Patterns must apply beyond this specific book |
| **Concise conclusion** | 2-3 sentences, actionable |
| **Strict format** | Follow the template exactly |

### Must-Avoid

| Issue | Why |
|-------|-----|
| Bullet-point lists | No depth, no pattern extraction |
| Chapter summaries | Exhausts rather than samples |
| Personal opinions | Must reflect book's core insights |
| Quotes without context | Each quote needs scenario + pattern |

---

## Evaluation Criteria

Each submission is scored on:

1. **Scenario Quality** (1-5): How concrete and memorable is the example?
2. **Pattern Transferability** (1-5): Could this pattern apply to other domains?
3. **Format Adherence** (1-5): Does it match the template exactly?
4. **Conciseness** (1-5): Is it 400-600 words without fluff?

**Minimum passing score**: 16/20

---

## Submission Process

1. **Fork** this repository
2. **Create** `_posts/[book-title].md`
3. **Verify** format compliance
4. **Submit** pull request with:
   - Book title and author
   - Brief (1 sentence) justification for inclusion
   - Self-assessed quality score

---

## Categories

If adding a new category, update the README.md categories list.

Current categories:
- Self-Improvement
- Finance
- Philosophy
- Relationships
- Thinking
- Science
- Biography

---

## Questions?

Open an issue for format questions or category suggestions.

---

*Thank you for helping build this knowledge resource.*
