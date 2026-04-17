# BookSummaries — Data Sampler Dataset

> A curated collection of the world's most impactful books, summarized using the Representative Sampling Methodology. 3 samples. 3 patterns. Infinite insight.

---

## What Is This?

A dataset of **book summaries** generated using the **Data Sampler Methodology** — a systematic approach to distilling any book into its most representative insights.

Instead of exhaustive coverage, each summary contains:
- **3-5 representative samples** (scenarios, case studies, or examples)
- **Pattern extraction** (transferable principles per sample)
- **Key generalizations** (concepts that apply beyond the specific book)
- **Conclusion** (actionable application)

---

## The Methodology

### Why Sample?

Most book summaries suffer from one of two problems:
- **Too shallow**: 10 bullet points that capture nothing
- **Too deep**: Chapter-by-chapter recaps that overwhelm

The Data Sampler approach solves this by selecting the **highest-impact examples** that collectively illuminate the full concept. Readers can extrapolate patterns, not just collect facts.

### The Format

```
# [Book Title] — Data Sampler Summary

## Core Insight
> One-sentence thesis

---

## Representative Samples: [N]

### Sample 1: [Title]
**Scenario**: [Concrete example]
**Pattern**: [Transferable principle]

---

## Key Generalizations

| Concept | Core Truth |
|---------|-----------|
| ... | ... |

## Conclusion
[2-3 sentences]
```

---

## Dataset Structure

```
booksummary-dataset/
├── README.md
├── _posts/
│   ├── atomic-habits.md
│   ├── deep-work.md
│   ├── 8-rules-of-love.md
│   ├── psychology-of-money.md
│   ├── thinking-fast-slow.md
│   └── ... (ongoing additions)
├── CONTRIBUTING.md
└── LICENSE
```

### Frontmatter Schema

Each summary includes YAML frontmatter:

```yaml
---
title: "Book Title"
author: "Author Name"
summary_length: "~500 words"
samples_count: 3
categories: [Category1, Category2]
date_added: YYYY-MM-DD
source: "Original publication or reference"
---
```

---

## Categories

- **Self-Improvement**: Atomic Habits, Deep Work, The 7 Habits
- **Finance**: The Psychology of Money, Rich Dad Poor Dad, Thinking in Bets
- **Philosophy**: Meditations, The Obstacle Is the Way, Man's Search for Meaning
- **Relationships**: 8 Rules of Love, Attached, The 5 Love Languages
- **Thinking**: Thinking Fast and Slow, The Art of Thinking Clearly, A Mind for Numbers

---

## Quick Start

### Browse by Category

```bash
# View all summaries
ls _posts/

# Filter by category (via frontmatter)
grep -l "Self-Improvement" _posts/*.md
```

### Generate Your Own

Use the [Data Sampler Prompt](#) as a template to summarize any book:

```
ROLE: Data Sampler Summarizer

TASK: Transform [BOOK TITLE] into a representative sampling summary.

OUTPUT FORMAT:
1. Core Insight (one sentence)
2. 3-5 Representative Samples (scenario + pattern)
3. Key Generalizations table
4. Conclusion (application)

CONSTRAINTS:
- 400-600 words
- Never exceed 5 samples
- One concrete scenario per sample
- Favor insight over information density
```

---

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for:

- Submission guidelines
- Quality standards
- Sample evaluation criteria
- Format specifications

**Process:**
1. Fork the repository
2. Add your summary in `summaries/[book-title].md`
3. Ensure it follows the format template
4. Submit a pull request

---

## Philosophy

> *"Show enough representative examples that readers can extrapolate the pattern, then trust them to generalize."*

This dataset is for:
- **Learners** who want essence without exhaustive reading
- **AI trainers** building book summary datasets
- **Content creators** seeking structured, pattern-driven summaries
- **Researchers** studying knowledge compression techniques

---

## License

MIT License — Free for personal, educational, and commercial use.

---

## Related Projects

- [Data Sampler Prompt Template](link)
- [Awesome Book Summaries](link)
- [Mental Models Collection](link)
