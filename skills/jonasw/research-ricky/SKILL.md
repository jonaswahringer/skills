---
name: research-ricky
description: Conduct deep, source-backed research on a complex or technical question and deliver a clear Markdown report. Use when the user explicitly asks for research, a literature or documentation review, or an explanation that needs current and verifiable sources.
disable-model-invocation: true
---

# Research Ricky

Produce a source-backed research report that a technically capable reader can understand on the first pass and audit later.

## Workflow

1. **Frame the question.** Extract the decision or question, audience, domain, geographic or time scope, desired depth, and output location. If a key scope is missing, choose a reasonable default and state it in the report. Separate the question into answerable subquestions before searching.

2. **Build a source map.** Search for the sources that own the facts: standards, legislation, official documentation, first-party datasets, original papers, filings, and direct statements from the relevant organisation. Use secondary sources only to discover primary sources or to provide clearly labelled context. For current or unstable facts, verify them against a current source.

3. **Research in passes.** First establish terminology, the basic model, and the main answer. Then investigate the subquestions, edge cases, disagreements, limitations, and practical implications. Keep a source ledger while working: for each important claim, record the source, publication or update date, exact location, and what it supports.

4. **Draft from claims.** Start with a short, descriptive title and an executive summary. Explain essential terminology and the simplest useful mental model before introducing detail. Organise the body around the question and its subquestions, not around the order in which sources were found. Distinguish facts, interpretations, estimates, and recommendations.

5. **Audit the report.** Check every material factual claim against its citation; check that citations support the claim as written; remove unsupported precision; resolve contradictions or show them; mark uncertainty and source age; and confirm that the report answers the original question. A report is complete only when every material claim is sourced or explicitly identified as analysis, every requested subquestion is addressed, and the limitations are visible.

6. **Save and hand off.** Write one Markdown report in the repository’s existing research or notes location. If there is no convention, use `research/<short-topic>.md` and create the directory if needed. Keep the report self-contained, link citations inline, and finish with a source list containing title, publisher or author, date, URL, and access date where relevant. Report the file path, scope assumptions, and any unresolved gaps.

## Research standards

- Prefer sources in this order: primary source; official synthesis or documentation; peer-reviewed or otherwise reputable secondary analysis; general secondary commentary. Match source strength to claim importance.
- Cite claims close to where they appear. One citation may support several adjacent claims only when it supports all of them.
- Use the source’s own definitions when terminology is contested. State the chosen definition and name important alternatives.
- For empirical or scientific questions, report method, population or data, date, effect size or uncertainty when available, and important limitations. Do not turn correlation into causation.
- For legal, financial, medical, safety, or policy questions, state jurisdiction and date, avoid presenting the report as professional advice, and surface material uncertainty.
- Prefer links to stable canonical pages, papers, standards, or documents. Do not cite search-result pages, snippets, or a source you did not inspect.
- Quote sparingly. Paraphrase by default, and keep any quotation short and clearly attributed.

## Report shape

Use this outline unless the question calls for a better one:

```markdown
# Short descriptive title

## Executive summary
## Scope and assumptions
## Key terms and basic model
## Findings
### <subquestion>
## Trade-offs, limitations, and open questions
## Practical implications
## Sources
```

Adjust depth to the question. A substantial investigation is usually several to roughly thirty pages when rendered, but do not pad a small question or compress a large one to meet a page count.
