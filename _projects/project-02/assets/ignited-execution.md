# Etaphi — Execution Layer

## Season 2 — Built on top of the IGNITED Brand Strategy

_Status: Structure scoped, not yet fully detailed. Built in this order — Infrastructure Setup, SOPs, Content Production Workflow, Publication Workflow — so their combined real load can inform the Work Schedule, built last._

---

## How This Document Relates to the Strategy

This document does not add new principles — everything here executes decisions already locked in the IGNITED Brand Strategy (Modules 1–8). Where a strategy document states a governing principle, this document states the concrete, repeatable procedure that satisfies it. If something here seems to contradict the strategy, the strategy wins — this document should be revised, not the other way around.

**The five components, and the sequencing logic:**

|#|Component|Why it's sequenced here|
|---|---|---|
|1|Infrastructure Setup|Prerequisite — nothing else can run without the domain, tooling, and Backend basics existing|
|3|SOPs|Defines _how_ recurring work gets done, which determines how long each task actually takes|
|4|Content Production Workflow|The specific pipeline SOPs plug into, for making content|
|5|Publication Workflow|The specific pipeline SOPs plug into, for shipping and logging content|
|2|Work Schedule|Built last, once the real time cost of 1, 3, 4, and 5 is visible — not guessed at in advance|

---

## Part 1 — Infrastructure Setup

Directly operationalizes Module 7's Front-End and Backend tables as an ordered build sequence, not just a category list.

### 1.1 — Build Order (Front-End)

|Order|Item|Depends on|Notes|
|---|---|---|---|
|1|Domain registration|Nothing|Anchors everything else — do this first|
|2|Professional email|Domain|Immediately after domain|
|3|Hosting/funnel platform account|Domain (for connecting it)|Systeme.io-style candidate, per Module 7 — confirm choice before building anything on top of it|
|4|Design tooling confirmed|Nothing (already in use — Canva)|No new setup, just formal confirmation this is the standing tool|
|5|Content-production tooling confirmed|Nothing (already in use — Claude)|Same — formal confirmation, workflow expected to expand later|
|6|Tracking/analytics tool selection|Hosting platform, for integration|Lower priority than 1–3; needed before Campaign 1's data collection ideally, not before infrastructure basics|
|7|Payment processing (collection side)|Hosting platform|**Blocked** — see Module 2, Part G / Module 7, B.2 disclosed constraint; revisit once entity/financial timeline resolves|

### 1.2 — Build Order (Backend — Independent-of-Entity Items Only)

Per Module 7's split, only the non-entity-dependent items are buildable now. The entity-dependent items (formal invoicing, tax records tied to registered income, contracts requiring a legal entity) remain correctly blocked and are not listed here — they're picked up once the ~5–6 month constraint resolves.

|Order|Item|Depends on|Notes|
|---|---|---|---|
|1|Terms & Conditions / Privacy Policy (draft)|Nothing|**Hard prerequisite for Phase 2** — must exist before any lead capture goes live|
|2|Contract/service-agreement template (draft)|Nothing|Draftable now, formalized later once an entity exists|
|3|Refund/dispute policy (written)|Nothing|Written stance decided in advance, not improvised later|
|4|Basic CRM (spreadsheet)|Nothing|Structure only needs defining — columns for Prospect/Lead/Buyer status, source, date, notes|
|5|Basic bookkeeping/expense ledger|Nothing|Separate from formal tax records — just disciplined tracking of business-related spend (Canva Pro, domain, hosting) from day one|

### 1.3 — Infrastructure Completion Checklist (for Module 8's audit cadence)

A simple binary checklist — this is what Module 8's "Infrastructure Audit" cadence actually checks against, ahead of each phase transition:

- [ ] Domain registered
- [ ] Professional email active
- [ ] Hosting/funnel platform account live
- [ ] Design and content tooling confirmed
- [ ] Tracking/analytics tool selected and connected
- [ ] Terms & Conditions / Privacy Policy published
- [ ] Contract template drafted
- [ ] Refund/dispute policy written
- [ ] Basic CRM structure created
- [ ] Basic bookkeeping ledger created
- [ ] _(Blocked, tracked separately)_ Payment processing — pending entity/financial timeline

---

## Part 2 — SOPs (Standard Operating Procedures)

Scoped here as a **named list with defined purpose and rough shape** — not fully written out step-by-step yet. Each SOP gets fully detailed when it's actually about to be used for the first time, consistent with the "build ahead of need, not before it's useful" discipline from Module 7. What matters for scheduling purposes is knowing _that_ each of these exists as a distinct piece of work and roughly what it governs.

|SOP|Governs|Rough shape|
|---|---|---|
|**SOP-1: Weekly Review**|Module 8's weekly cadence|Checklist: pull outcome/process metrics, update campaign tracker, log any Open Hypotheses, note buffer level|
|**SOP-2: Campaign Setup**|Launching a new Module 5 campaign|Fill the six-field campaign brief (Module 5, Part A), confirm locked constants, set start/end dates|
|**SOP-3: Campaign Close & Comparison**|Ending a campaign|Pull full data set, compare against control/prior sub-campaign, apply graduation rule, log conclusion|
|**SOP-4: Single Video Production**|Making one Tino-facing TOFU video|Idea → costume-check against Module 4's job table → script → film/design → edit → move to content bank|
|**SOP-5: Build Log Episode Production**|Making one Track 1 episode (Intro/Launch/Close, for now)|Pull prior week's data → draft hypothesis/reflection → film → edit → move to content bank|
|**SOP-6: Publishing & Tagging**|Posting anything|Confirm content-bank item ready → post at the campaign's locked time slot → apply full tag set (costume, funnel stage, track, time-slot) → log into documentation trail|
|**SOP-7: Documentation Trail Update**|The actual data-logging habit|Pull per-post metrics at defined check intervals → enter into tracking structure → flag anomalies for the weekly review|
|**SOP-8: Infrastructure Audit**|Module 8's pre-phase-transition check|Run the Part 1.3 checklist above, confirm nothing's missing before a phase opens|

---

## Part 3 — Content Production Workflow

The pipeline SOP-4 and SOP-5 actually plug into — the path an idea takes from nothing to a content-bank-ready asset.

**Stage 1 — Sourcing:** Idea originates from the costume-cluster bank (per Module 4/existing content-clustering work) for Track 2, or from the prior week's documentation-trail data for Track 1 (Build Log).

**Stage 2 — Costume/Job Check:** Before scripting, confirm which Module 4, Part A journey-stage job this piece is doing, and which Three Costume it addresses (for Track 2) — per Module 4's governing rule, if this can't be answered, the idea isn't ready yet.

**Stage 3 — Script/Structure Draft:** Written using Claude (per Module 7's confirmed tooling), checked against Module 4's density principle (Stage 1–2 content stays light; Track 1 content is permitted to assume more context).

**Stage 4 — Visual/Production:** Design assets built in Canva (Track 2 visuals, any on-screen text) or filmed directly (talking-head format, per the Build Log's likely format). Checked against the Visual Style Guide (Module 1, Part M) — Fraunces/Poppins/Caveat, the locked color palette, "workshop not showroom."

**Stage 5 — Edit & Finalize:** Final cut/export, ready for posting.

**Stage 6 — Content Bank Entry:** Finished asset enters the content bank inventory, satisfying Module 2, Part D's buffer requirement — not published immediately, held until its scheduled slot per the Publication Workflow below.

---

## Part 4 — Publication Workflow

The pipeline SOP-6 and SOP-7 plug into — what happens between "content bank" and "logged data."

**Step 1 — Slot Confirmation:** Check the active campaign's locked time slot (currently, per Module 5's Campaign 1, either 11PM–12AM or 11AM–12PM depending on which sub-campaign is active).

**Step 2 — Publish:** Post the content-bank item at the confirmed slot.

**Step 3 — Tagging:** Apply the full tag set at time of publishing, not retroactively — costume (Module 1, Part E), funnel/journey stage (Module 4, Part A), track (Build Log vs. Tino-Facing Cluster), and time-slot (Module 2, Part E). This is what makes Module 8's later review actually possible; untagged content can't be filtered or compared.

**Step 4 — Initial Log Entry:** Create the documentation-trail row for this post — date, slot, tags, and a placeholder for metrics to be filled at the next check interval.

**Step 5 — Metrics Check(s):** Per Season 1's proven cadence pattern, checked at defined intervals (e.g., ~24hrs, then folded into the weekly rollup) — not continuously monitored throughout the day.

**Step 6 — Weekly Roll-Up:** Feeds directly into Module 8's Weekly Review (SOP-1).

---

## Part 5 — Work Schedule _(Deferred — Built Next, Once 1–4 Above Are Reviewed)_

Not yet built, by design. Once you've reviewed Parts 1–4 above and have a real sense of the total task load (one-time infrastructure setup, the ongoing weekly cadence of SOPs 1, 4/5, 6, 7, and the periodic SOPs 2/3/8), the schedule gets built against that real picture — fit around the existing day-job constraint (Module 1's Personal Why, Module 2's disclosed financial timeline), rather than estimated in advance and likely proven wrong.

**Open question for that next conversation, worth having in mind:** roughly how much weekly time is realistically available outside the day job, so the schedule gets built against a real constraint rather than an aspirational one.

---

_End of Execution Layer v1. Parts 1–4 are structurally complete; Part 5 (Work Schedule) is the next piece of work, to be built once this structure has been reviewed._