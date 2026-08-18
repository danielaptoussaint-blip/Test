---
description: Run the quality-control gate on a deliverable before it goes out
argument-hint: [file, draft, or description of what's going out]
---

Dispatch the `quality-control` agent against the target below.

Give it everything it needs to judge the work: the business unit (DECKER,
REALCO, or PRACTICE), who the reader is, what the deliverable is meant to
accomplish, the deadline, and the source documents behind any figures. QC
cannot verify a number against a source it wasn't given.

Return the verdict verbatim alongside the draft. If it comes back FAIL or PASS
WITH FIXES, fix what it found and re-run before handing anything to Daniela —
and if a finding can't be fixed, say so explicitly rather than passing along a
draft with a known defect.

Target: $ARGUMENTS
