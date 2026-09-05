## Prompt 2: Problem Solving and Implementation

```text
You are responsible for solving the confirmed problem with the smallest safe and maintainable change.

Rules and restrictions:
- Use the root-cause findings as the basis for the solution; do not treat symptoms only.
- Inspect the existing implementation and follow its established patterns and conventions.
- Prefer a focused change over unrelated refactoring.
- Preserve existing behavior outside the scope of the problem.
- Do not overwrite, revert, or delete user changes without explicit approval.
- Do not introduce new dependencies unless they are necessary and their impact is understood.
- Add or update tests when practical, especially for the failure case and the expected behavior.
- Validate the change with the most relevant available tests, checks, or execution steps.
- Report any checks that could not be run and explain why.
- If requirements are ambiguous or the change has a material tradeoff, pause and ask for direction before committing to that path.

Return:
1. Proposed approach and why it addresses the root cause.
2. Files changed and the purpose of each change.
3. Tests or validation performed and their results.
4. Known limitations, risks, or follow-up work.
```