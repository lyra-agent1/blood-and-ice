# Agent Acceleration Plan - Blood Under Ice (2026-06-12)

**Goal**: Highest-leverage parallel work to advance Book One while strictly obeying the new Agent Operating Rules (README.md section "Agent Operating Rules").

**Context**:
- Manuscript rough draft complete through Chapter 28.
- Next immediate packet: "Stores And Splinters" (Chapters 29-32) per next-scene-queue.md and book-one-production-plan.md.
- Latest change (PR #3): Added strict Agent Operating Rules + continuity requirements.
- All work must:
  - Read README (esp. Agent Operating Rules), docs/continuity/index.md, next-scene-queue.md, names-and-terms.md, banned-ip-checklist.md before touching anything.
  - Only edit the exact assigned section + the minimal required continuity files.
  - Run banned-term scan before finishing.
  - Update relevant continuity (timeline, cost-ledger, names-and-terms, next-scene-queue) in the same change.
  - Never do broad rewrites of completed material.

**8 Parallel Sub-Agent Tasks** (scoped for independent execution):

1. **Sub-Agent 1: Draft Chapter 29 - "The Open Store"**
   - Scope: Write full rough draft of Chapter 29 per exact spec in docs/continuity/next-scene-queue.md ("The Open Store").
   - Constraints: First-person Rook voice only. Advance plot + one relationship + one tribal rule + The Red cost. End ready for public inspection pressure.
   - Required updates: Append to docs/continuity/timeline.md, add entries to cost-ledger.md and names-and-terms.md if new terms appear. Add any open questions to next-scene-queue.md.
   - Deliverable: New file or update in manuscript/book-one/part-05-after-crown/029-the-open-store.md (or correct part). Short "what this chapter accomplished" note at top of the PR diff.

2. **Sub-Agent 2: Draft Chapter 30 - "Naim Without Staff"**
   - Scope: Full rough draft of Chapter 30 per next-scene-queue.md spec.
   - Constraints: Same chapter standard as #1. Focus on private/semi-private doubt scene + Hollow Antler doctrine reveal.
   - Required updates: Continuity files as in Task 1.
   - Deliverable: manuscript/.../030-naim-without-staff.md + continuity updates.

3. **Sub-Agent 3: Draft Chapter 31 - "Useful Sacrifice"**
   - Scope: Full rough draft of Chapter 31 per spec (Dremm faction + sacrifice proposal + Rook response).
   - Constraints: The Red must press for strategic answer. Show restraint vs. utility tension.
   - Required updates: Continuity files + cost-ledger emphasis.
   - Deliverable: manuscript/.../031-useful-sacrifice.md + continuity.

4. **Sub-Agent 4: Draft Chapter 32 - "The Small Tribe Bargain"**
   - Scope: Full rough draft of Chapter 32 per spec (minor tribe + winter-road bargain + evidence of lingering opposition reach).
   - Constraints: Extend authority beyond central camps. End with forward pressure.
   - Required updates: Continuity + next-scene-queue with Packet 6 ideas.

5. **Sub-Agent 5: Continuity Hygiene Pass (Timeline + Cost + Names)**
   - Scope: Systematic review and update of docs/continuity/timeline.md, cost-ledger.md, and names-and-terms.md for chapters 1-28 accuracy + stubs/prep for 29-32.
   - Constraints: Do NOT rewrite manuscript. Only continuity files. Run banned-ip-checklist scan at end.
   - Deliverable: Updated continuity files + a short "gaps found" summary added to next-scene-queue.md. Banned-term scan report (clean or fixed items).

6. **Sub-Agent 6: Recent Packet Quality Review (Chapters 21-28)**
   - Scope: Read chapters 21-28. Produce targeted edit notes against "Chapter Standard" in book-one-production-plan.md and the review questions in README.
   - Constraints: Only suggest or make **minimal, high-precision fixes** to already-drafted chapters if they violate continuity or obvious cost/voice issues. Prefer adding notes to next-scene-queue or a new review notes file rather than broad edits. Do not touch earlier packets.
   - Deliverable: New file docs/review/chapter-21-28-review-notes.md + any tiny targeted fixes + updates to continuity if facts were clarified.

7. **Sub-Agent 7: Bibles & World Refinement**
   - Scope: Update docs/characters/protagonist.md and docs/characters/tribal-leaders.md with any new durable character/political facts established in chapters 21-28. Light pass on docs/world/four-tribes.md and docs/world/blood-and-ice-magic.md only where recent chapters force canon changes.
   - Constraints: Only add established facts. Do not invent. Update cost-ledger if new The Red mechanics appear. Run banned scan.
   - Deliverable: Updated bibles + short change log in docs/continuity/index.md or next-scene-queue.

8. **Sub-Agent 8: Production Planning & Packet 6 Outline**
   - Scope: 
     - Update docs/story/book-one-production-plan.md with accurate current status (post ch28 + status of 29-32 once drafted).
     - Flesh out a high-level Packet 6 outline (chapters 33-36) in the production plan and next-scene-queue.md.
     - Minor update to docs/story/long-series-roadmap.md if Book One implications are clear.
   - Constraints: Do not draft prose. Focus on structure and next-scene-queue entries. Reference the new Agent Operating Rules.
   - Deliverable: Updated production-plan.md + next-scene-queue.md entries for Packet 6 + any necessary continuity cross-references.

**Execution Rules for All 8 Sub-Agents**:
- Start by reading (in order): README.md (full Agent Operating Rules section), docs/continuity/index.md, next-scene-queue.md, names-and-terms.md, banned-ip-checklist.md.
- Work only in the blood-and-ice clone at /home/alex/.openclaw/workspace/blood-and-ice/.
- Before any edit, state in your internal notes the exact file(s) you are allowed to touch.
- After changes: Run the banned-term rg scan. If anything appears outside the checklist file itself, fix or document.
- All changes must be reviewable diffs. Update continuity in the same logical change.
- End with a short summary: "Accomplished X. Updated Y continuity. Banned scan: clean. Open questions moved to next-scene-queue."

**Priority Order** (if not all can run simultaneously):
Highest leverage = Tasks 1-4 (actual manuscript pages) + Task 5 (continuity hygiene). Then 6, 7, 8.

**Success Criteria**:
- 4 new rough chapters (29-32) exist in manuscript/.
- Continuity files are accurate and forward-looking.
- No banned IP terms introduced.
- Project is in a cleaner state for the next human review pass.

This plan respects the "one section at a time" preference while using parallel sub-agents for speed on independent workstreams.