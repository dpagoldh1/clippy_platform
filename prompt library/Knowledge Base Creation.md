## Prompt 3: Knowledge Base Creation from Templates

```text
You are responsible for creating or updating a structured knowledge base from reusable documentation templates such as incident reports and lessons learned.

Goal:
Create a searchable, consistent knowledge base that captures operational knowledge, incident history, decisions, lessons learned, and follow-up actions.

Inputs:
- Existing templates, especially:
  - templates/incident-report-template.md
  - templates/lessons-learned-template.md
- Existing documentation, incident notes, tickets, logs, meeting notes, postmortems, SOPs, or other source material provided by the user.
- The current repository structure.

Rules and restrictions:
- Inspect the repository structure before creating new folders or files.
- Reuse existing folders, naming conventions, and templates where they exist.
- If no suitable knowledge base folder exists, create one named knowledge-base.
- Create subfolders only when they improve navigation or long-term maintenance.
- Use template fields exactly where possible so documents remain comparable over time.
- Do not invent incident details, dates, owners, severity, root causes, actions, or evidence.
- Mark missing or uncertain information as TBD, Unknown, or Needs confirmation.
- Keep incident-specific reports separate from general lessons learned.
- Prefer one file per incident report and either one running lessons-learned log or one lesson file per incident, based on the existing structure.
- Use stable, searchable filenames such as YYYY-MM-DD-incident-id-short-title.md.
- Cross-link related documents, for example from an incident report to its lessons-learned entry and action items.
- Preserve original source material when useful by linking to it or summarizing it with clear attribution.
- Do not delete or overwrite existing knowledge base entries unless explicitly asked.

Recommended folder structure:
- knowledge-base/
  - incidents/
  - lessons-learned/
  - action-items/
  - decisions/
  - index.md

Creation steps:
1. Identify the available templates and summarize what each one is for.
2. Inspect existing knowledge base or documentation folders.
3. Decide whether to reuse existing folders or create knowledge-base and needed subfolders.
4. For each source item, classify it as incident report, lesson learned, decision, action item, SOP update, or general reference.
5. Create or update documents using the matching template.
6. Add metadata to each entry where available: date, owner, status, severity, affected service, root cause category, and related links.
7. Create or update knowledge-base/index.md with links grouped by category.
8. Create or update a lessons-learned log if the lessons-learned template indicates a running log is preferred.
9. List unresolved information and recommended follow-up checks.

Return:
1. Knowledge base structure created or updated.
2. Files created or changed and why.
3. Source material used for each entry.
4. Missing information that was marked as TBD or Unknown.
5. Suggested next entries, reviews, or maintenance tasks.
```
