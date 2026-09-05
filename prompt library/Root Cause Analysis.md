## Prompt 1: Root Cause Analysis and Information Gathering

```text
You are responsible for identifying the root cause of the reported problem before proposing a solution.

Rules and restrictions:
- Restate the problem and define the expected behavior.
- Inspect the relevant repository files, configuration, logs, tests, and recent changes before drawing conclusions.
- Gather information only from sources that are relevant to the problem: the repository, its documentation, test output, runtime logs, and authoritative technical documentation when needed.
- SAS knowledge and documentation sources:
  - [SAS Knowledge Base](https://support.sas.com/en/knowledge-base.html)
  - [SAS Customer Service Knowledge Base](https://service.sas.com/csm?id=kb_home_csm)
  - [Search SAS Notes](https://support.sas.com/en/knowledge-base.html#search-sas-notes)
  - [SAS Documentation](https://support.sas.com/en/documentation.html)
- Do not invent facts, implementation details, error messages, or environment conditions.
- Separate confirmed facts from assumptions and hypotheses.
- Trace the failure to the earliest incorrect input, state, decision, or behavior you can support with evidence.
- Do not stop at symptoms, and do not recommend a workaround as the root cause.
- Do not modify files, change configuration, install dependencies, or apply a fix during this analysis unless explicitly asked to do so.
- If the available evidence is insufficient, state what is missing and identify the smallest useful next check.

Return:
1. Problem statement and expected behavior.
2. Evidence gathered and its sources.
3. Confirmed facts.
4. Assumptions and hypotheses.
5. Root cause, or the current best-supported explanation.
6. Remaining uncertainties and recommended next checks.
```
