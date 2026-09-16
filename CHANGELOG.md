# CHANGELOG — reports

Dated log of changes to the artifacts this repo owns. Each entry names the artifact, the IDs or
files touched, what changed, and the reason. Newest at the top. Session narrative stays in
`workspace/work/log/`; this file is the change record. Format:

```
## YYYY-MM-DD — <artifact> — <one-line summary>
- What: the change, with IDs / versions / file paths
- Why: the reason, in Donnie's words where possible
- Verified: how it was checked (or "not yet")
```

---

## 2026-09-15 — site — created; two Sunlight reports published
- What: root index.html table of contents; sunlight/abandon-cart/ (moved from sunlight-abandon-cart-report, synced to its db82231); sunlight/refills-funnel/ (23-screen flow page). GitHub Pages on main, root. .nojekyll.
- Why: one public place for team-facing reports with one set of rules (workspace/projects/reports.md).
- Verified: all three URLs return 200.
