# Project Performance Readiness Checklist — Usage Guide

---

## License & Usage Notice

© 2026 Akhilesh Sarfare. All rights reserved.

This project performance readiness checklist package is a **commercial product** sold via Gumroad.

Purchase grants a **non-exclusive, non-transferable license** to:
- Use these checklists for personal or internal organizational purposes
- Modify the content for internal use while retaining attribution

**You may NOT:**
- Remove or alter the original author attribution
- Redistribute, resell, sublicense, or share this content outside your organization
- Publish this material (or derivatives) as your own work, free or paid

Attribution must remain visible in all copies and adaptations.

For commercial redistribution or licensing inquiries, contact:
**akhilesh.sarfare@gmail.com**

---

## What this is
This repository provides a **practical Performance Readiness Checklist** intended to be used:
- Once per **performance test cycle / release**
- Once per **individual performance test** (capacity, endurance, spike, etc.)

The checklist is authored in **plain Markdown** so it can live with code, test assets, and release documentation.

---

## What you get
- `pt-cycle-readiness-checklist.md` — gates validated once per PT cycle
- `pt-test-run-checklist.md` — gates validated per test execution
- `pt-cycle-readiness-sample-filled.md` — example output generated from a completed checklist (dummy data)
- `pt-cycle-readiness-sample-filled.pdf` — layout illustration of a completed checklist (dummy data)
- `README.md` — usage and workflow guidance

---

## Recommended workflow
1. Copy the relevant checklist (`.md`) for your release or test
2. Update it incrementally as gates are validated
3. Store it alongside code or test artifacts
4. Optionally export the markdown to PDF, Word (DOCX), EPUB, or any format of your choice for reviews or sign-off

---

## How to fill the checklist

### Primary method (preferred)
Use platforms that natively support Markdown task lists such as **GitHub**, **GitLab**, etc.

Example:
```md
- [ ] ENV-01 Environment stable
- [x] TS-03 Assertions validated

### Fallback Marking Examples (Tool-Agnostic)
- [X] WL-02 Load model approved
- [ ] TO-04 Tracing validated — PENDING
- PR-07 Error budget verified — DONE

---

