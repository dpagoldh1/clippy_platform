# Lessons Learned — {{INC-ID}}

Keep this schema fixed across every incident so entries stay comparable and searchable over time. One entry per incident, appended to a running `lessons-learned/log.md` (or one file per incident, your call).

---

- **Incident ID:**
- **Date:**
- **Severity:**
- **Root cause category:** (choose one — extend this list as patterns emerge)
  - Deployment / release process
  - Configuration error
  - Capacity / scaling
  - Third-party dependency
  - Missing monitoring/alerting
  - Missing test coverage
  - Data issue / migration
  - Human process gap
  - Other: {{specify}}
- **SLA met?** Yes / No / Partial (specify which stage missed)
- **If SLA missed, why:**
- **Lesson (one sentence, generalizable beyond this incident):**
- **Action item(s) created:** (link to tracking ticket)
- **Recurrence check:** Has this root cause category appeared before? (search prior entries) — Yes/No, link if yes

---

## Periodic review (fill quarterly / after every 5 incidents)

- Most common root cause category this period:
- Most common SLA-missed stage this period (ack / mitigate / resolve):
- New guardrail or prompt added to this library as a result:
- New alert/dashboard added as a result:
