# Agent Workforce — Architecture (Draft v0)

Status: draft pending intake answers. Nothing here is final; the roster is
deliberately over-built so it can be cut down rather than guessed at.

## Operating model

```
                        YOU
                         |
                  Chief of Staff          <- the only thing you talk to
                         |
   +---------+-----------+-----------+-----------+
   |         |           |           |           |
 DAY JOB   REAL ESTATE  ACCOUNTING  GROWTH    SUPPORT
 (Decker)  (own co)     (own firm)  (brand)   (cross-cutting)
```

Four rules the whole system runs on:

1. **One front door.** You brief the Chief of Staff. It decides who works.
2. **Nothing leaves without QC.** Every outbound deliverable passes the
   Quality Control agent before it reaches a human who isn't you.
3. **Nothing sends itself.** External communication is drafted, never
   transmitted, unless you have explicitly whitelisted that lane.
4. **Hard walls between the three businesses.** Decker data, own-portfolio
   data, and client data never share a context, a file path, or a document.

## Roster (proposed — cut what you don't want)

### Command layer

| Agent | Owns | Notes |
|---|---|---|
| **Chief of Staff** | Triage, delegation, daily/weekly cadence, end-of-day rollup | The orchestrator. Never does the work itself. |
| **Quality Control** | Final gate on every deliverable | Checks: figures tie, tone matches your voice, no data crossed a wall, deadlines honored |

### Support (serves all three businesses)

| Agent | Owns |
|---|---|
| **Inbox & Calendar** | Triage mail, draft replies in your voice, defend calendar, prep pre-meeting briefs |
| **Archivist** | Entity registry, deal files, document filing, SOP library, "where is that closing statement" |
| **Research** | Market comps, GAAP/tax research, lender and competitor intel |

### Day job — Controller to CFO (Decker Capital)

| Agent | Owns |
|---|---|
| **Close & Reporting** | Month-end checklist, TB review, variance narratives, reporting package |
| **Treasury & Lender** | Cash forecast, covenant tracking, draws, bank relationships |
| **CFO Track** | The promotion campaign: wins log, board-grade deliverables, exec briefs, gap plan, comp research |

### Real estate company (yours)

| Agent | Owns |
|---|---|
| **Acquisitions** | Sourcing, screening, underwriting, LOI and offer memos, deal pipeline |
| **Asset Operations** | Rent roll, vendors, capex, property-level P&L, monthly asset review |
| **Investor Relations** | Capital calls, distributions, quarterly letters, K-1 comms, investor CRM |

### Accounting services firm (yours, solo)

| Agent | Owns |
|---|---|
| **Client Delivery** | Client closes, workpapers, reconstructions — runs your workpaper-style and deal-reconstruction skills |
| **Practice Development** | Proposals, engagement letters, pricing, onboarding |
| **Practice Ops** | Time, billing, collections, capacity and WIP |

### Growth (spans real estate + firm)

| Agent | Owns |
|---|---|
| **Marketing** | Positioning, offer, campaigns, funnel, list building |
| **Content Creation** | LinkedIn, newsletter, thought leadership — drafted in your voice |

## Cadence (proposed)

| When | What fires |
|---|---|
| Weekday AM | Morning brief: calendar, top 3 per business, overnight inbound |
| Weekday PM | Rollup: what moved, what's blocked, tomorrow's top 3 |
| Friday | Weekly review: pipeline, client WIP, content calendar, CFO wins log |
| Monthly, day -3 | Close readiness checklist (day job + client books) |
| Quarterly | Investor letter cycle, practice pricing review, CFO-track self-assessment |

## Open risk to settle in intake

Running two side businesses while a W-2 Controller carries real
conflict-of-interest and data-handling exposure. This system will make that
activity faster and more visible, so the walls need to be defined up front —
see intake section B.
