# Red Team Review: Submission Draft

Adversarial review of `submission-draft.md` from the perspective of a BlueDot reviewer evaluating a Community Lead work test submission. Each finding includes the original critique, your response, and the recommended action.

---

## Findings

### 1. "Top 1% talent" framing risks sounding elitist
**Critique:** The submission repeatedly claims BlueDot should invite only the "top 1%" of 7,000+ alumni. That's ~70 people total. At 30-35 Side B seats monthly, the pool exhausts in 2-3 months. BlueDot's mission is growing the pipeline (2,000 to 100,000), not creating an exclusive club.

**Response:** Keep the framing. This aligns with what the founder wants. BlueDot's courses produce new graduates every month, so the pool replenishes. The exclusivity is the value proposition to both sides of the room.

**Action:** Keep the "top 1%" language, but add a sentence clarifying that the pool is continuously replenished by monthly course cohorts. Make it clear this is about identifying the most ready-to-act people from each cohort, not a fixed list.

**Priority:** Low (minor clarification)

---

### 2. Champion/follow-up system is operationally infeasible for a team of 7
**Critique:** The proposal asks 3-4 team members to do 100-200 follow-up calls/month (50-100 hours). The team is currently ~7 people scaling to 20-25, and the Community Lead role is already split across four responsibility areas. This looks like a system designed on paper without thinking about who executes it.

**Response:** This is a valid concern. The follow-up system as described is too heavy for the current team.

**Action:** Revise the champion system. Options:
- **Outsource:** Contract part-time community fellows (possibly BlueDot alumni) to handle follow-up calls. Frame it as a paid fellowship role.
- **Lighter touch:** Replace biweekly calls with a structured Google Doc per participant that tracks goals, blockers, and next steps. The champion checks in asynchronously (Slack DM or quick form) rather than scheduling calls. Reserve live calls for high-priority participants only.
- **Scale with the team:** Explicitly note that the full champion model activates once the team reaches 15-20 people, with a lighter version running at current team size.

**Priority:** High (operational feasibility is a core signal for this role)

---

### 3. Swapcard called "overkill" in the research but recommended anyway
**Critique:** The event-design-research.md concludes "For a 50-person monthly event, Swapcard is overkill. Designed for large trade shows." The submission uses Swapcard without addressing this contradiction.

**Response:** Keep Swapcard. It's the right tool for structured 1-on-1 matching with profiles, and using a professional platform signals operational seriousness. The cost ($610/year for Starter) is trivial against BlueDot's budget.

**Action:** Add a brief justification for why Swapcard is worth using despite the scale. Something like: "While simpler tools could handle 50-person logistics, Swapcard's AI matchmaking and profile system reduce manual curation effort and scale cleanly if the event grows. At $610/year, the cost is negligible." Acknowledge the tradeoff rather than ignoring it.

**Priority:** Low (add one sentence)

---

### 4. No demonstration of unique personal depth/skill
**Critique:** The assignment explicitly says: "Demonstrate your unique depth of expertise or skills somewhere in your submission." The document is thorough but reads as generic consulting output. Nothing signals a skill only this candidate could bring.

**Response:** The unique skill being demonstrated is the theory of impact and event design thinking. The depth is in the problem analysis, the evidence-based framing, and the systems architecture.

**Action:** Make this explicit. Add a short paragraph (in a cover note or intro) that names the skill being demonstrated. Something like: "My approach to this work test was to lead with problem diagnosis. Before designing a format, I researched the AI safety talent pipeline in depth to identify the specific bottleneck this event should target. The theory of impact in Part 1 is the core of my submission, because I believe the Community Lead's most important job is knowing *why* an event exists, not just how to run one."

Also: the Airtable base was built out. Make sure the submission highlights what's in it (sample data, table structure, any automations). Walk the reviewer through it briefly so they don't have to click and explore cold.

**Priority:** High (this is what the assignment explicitly asks for)

---

### 5. Two "Layer 4" headings in Systems Design
**Critique:** There are two sections both labeled "Layer 4" (Outcome Tracking and Improvement Engine). Copy-paste error that signals rushed work.

**Response:** Valid. Fix it.

**Action:** Rename the second one to "Layer 5: Improvement Engine."

**Priority:** High (easy fix, embarrassing if left)

---

### 6. Event format replicates EAG's exhaustion problem
**Critique:** The research documents that 10-15 1-on-1s per day causes burnout at EAG. The submission packs 9-10 meetings into 3 hours, which is the same density compressed into a shorter window.

**Response:** Disagree. EAG exhaustion comes from doing this across a full weekend (2-3 days). 3 hours is a single burst. People can sustain high-energy interaction for 3 hours. This is closer to a dinner party than a marathon. The 15-minute slot length also keeps conversations focused and energetic.

**Action:** No change to the format. But add a sentence acknowledging the design choice: "Unlike multi-day EAG events where meeting fatigue is a documented problem, this 3-hour format is a single high-intensity session. The short duration is a feature: it keeps energy high and prevents the burnout that comes from multi-day scheduling pressure."

**Priority:** Low (one sentence to preempt the objection)

---

### 7. No budget or cost analysis
**Critique:** The submission proposes a monthly event with venue, food/drinks, Swapcard licensing, and significant staff time, with zero financial information. A reviewer evaluating operational maturity expects at least a rough estimate.

**Response:** Valid. Should include a budget.

**Action:** Add a simple budget table. Rough estimate:

| Item | Monthly Cost | Notes |
|------|-------------|-------|
| Venue (Mox) | $0-500 | BlueDot already hosts at Mox; may be free or subsidized |
| Food/drinks | $500-750 | Light catering for 50 people |
| Swapcard | ~$50 | $610/year amortized |
| Staff time | Included | Part of Community Lead + team responsibilities |
| Printing/materials | $50-100 | Name badges, schedules, signage |
| **Total** | **~$600-1,400/month** | **$12-17k/year** |

This is roughly $12-28 per attendee per event, which is far cheaper than EAG (~$1,200/attendee) or even EA North (GBP 50/attendee).

**Priority:** Medium (shows operational maturity)

---

### 8. "Why BlueDot" section tells BlueDot what they already know
**Critique:** The section spends 150+ words reminding BlueDot of their own capabilities. The reviewer IS BlueDot. This reads as padding.

**Response:** Keep this section. In a formal submission, it's important to show you understand the org's positioning and can articulate it. This section frames why the event concept is uniquely suited to BlueDot's assets. It's not padding, it's demonstrating strategic thinking.

**Action:** No structural change, but tighten the language. Instead of explaining what BlueDot has, frame it as why those specific assets make this event design viable where it wouldn't be for another org. Shift from "BlueDot has X" to "This event works because of X, and no one else has that."

**Priority:** Low (tighten, don't remove)

---

### 9. Airtable base exists but isn't showcased in the document
**Critique:** The assignment hints strongly at building something ("If you build something, include a link with sharing enabled"). The Airtable link is included but the document doesn't walk through what's in the base.

**Response:** The Airtable base is built. It just isn't showcased well enough in the document.

**Action:** Add a brief walkthrough section or screenshots showing:
- The table structure (what tables exist, key fields)
- Sample data (even if fake, shows the system works)
- Any views or dashboards configured
- If any automations are set up, describe them

The Airtable base should be the centerpiece of Part 2, not an afterthought link.

**Priority:** High (this is a core deliverable)

---

### 10. No mention of BlueDot's existing tools (monorepo, networking bot, etc.)
**Critique:** BlueDot has a monorepo with meeting tools, availability collection, a networking bot pattern, cohort scheduling, and an MCP aggregator. The submission proposes external tools as if BlueDot has no existing infrastructure.

**Response:** Didn't know BlueDot had these tools. This is internal infrastructure that a candidate wouldn't reasonably be expected to know about. The GitHub repo is public, but deep-diving into a company's codebase during a 3-hour work test is not a realistic expectation.

**Action:** No change needed. A candidate isn't expected to audit the company's GitHub during a timed work test. If a reviewer raises this, the honest answer is: "I'd want to audit existing tools in the first week on the job and adapt the system design accordingly." Could add a brief note in the Systems section: "Implementation should build on BlueDot's existing infrastructure where possible. The first step after onboarding would be auditing current tools and adapting this design to leverage what already exists."

**Priority:** Low (add one sentence as a hedge)

---

### 11. Metrics targets are asserted without basis
**Critique:** The 30/60/90 day targets (5-10 job applications, 3-5 interviews, 1-3 offers per event) have no stated methodology. Where did these numbers come from?

**Response:** Valid. The numbers are educated guesses but should be framed as such.

**Action:** Reframe the metrics targets as hypotheses, not commitments. Add a note: "These targets are initial hypotheses based on EAG connection-to-outcome ratios and the higher curation level of this event. The first 2-3 editions will calibrate these baselines. The important thing is having the tracking infrastructure in place to measure, not the specific numbers."

**Priority:** Medium (shows intellectual honesty and data maturity)

---

### 12. "Why monthly?" isn't explicitly justified
**Critique:** No evidence that monthly curated networking sustains attendance. After month 3, where do new Side B attendees come from?

**Response:** Monthly works because BlueDot runs continuous course cohorts. Each month produces new graduates, and the 5-star rated participants from each cohort feed directly into the event pipeline. The pool isn't static; it's continuously replenished.

**Action:** Add explicit justification: "BlueDot runs monthly course cohorts across 4 concurrent courses (AGI Strategy, Technical AI Safety, Frontier AI Governance, Biosecurity). Each cohort produces participants rated by facilitators on a 5-star scale. The top-rated graduates from each cohort form the monthly attendee pipeline for Side B. This means the event draws from a fresh pool each month rather than recycling the same attendees." This directly addresses the churn concern and grounds the monthly cadence in BlueDot's actual operational rhythm.

**Priority:** Medium (important strategic justification)

---

### 13. "Bridge" metaphor
**Critique:** The word "bridge" appears as a metaphor in the Theory of Impact section.

**Response:** Not a concern. Fine to use.

**Action:** None.

**Priority:** None

---

### 14. No Loom video
**Critique:** The assignment says a Loom video is optional but signals effort and communication skills. For a public-facing Community Lead role, skipping it wastes a differentiation opportunity.

**Response:** Considering doing one.

**Action:** Record a scrappy 3-5 minute Loom. Don't overthink it. Cover: (1) why you chose this specific bottleneck, (2) the core design insight (curation is the product), (3) a quick walkthrough of the Airtable base. This is a chance to show personality and communication style, which matters for a community-facing role. Keep it unpolished per the assignment's instruction.

**Priority:** Medium (optional but high-ROI differentiation)

---

### 15. Outreach strategy doesn't leverage personal network or specifics
**Critique:** The outreach section lists BlueDot's channels but doesn't show the candidate can personally get people in a room.

**Response:** The main outreach strategy should be reaching out to 5-star rated participants from BlueDot's database. That's the primary pipeline. Each course cohort has facilitator ratings, and the top-rated participants get direct invitations.

**Action:** Rewrite the outreach section to lead with the primary mechanism: **"Side B sourcing is driven by facilitator ratings from BlueDot's course database. After each cohort, participants rated 5 stars by their facilitators receive a direct invitation to the next event. This is the core pipeline."** Then list secondary channels (MATS alumni, referrals from Side A, etc.) as supplements. This is more specific, more operationally grounded, and shows understanding of how BlueDot's data actually works.

**Priority:** Medium (makes the outreach section concrete rather than generic)

---

## Summary: Action Items by Priority

### Must-fix (High Priority)
1. **Fix duplicate Layer 4 heading** (finding #5) - 30 seconds
2. **Revise champion/follow-up system** for operational feasibility (finding #2) - consider outsourcing, async check-ins, or phased rollout
3. **Showcase the Airtable base** in the document (finding #9) - add walkthrough, sample data description, screenshots
4. **Make the "unique depth" explicit** (finding #4) - add a paragraph naming what skill you're demonstrating

### Should-fix (Medium Priority)
5. **Add a budget table** (finding #7)
6. **Reframe metrics as hypotheses** (finding #11)
7. **Justify monthly cadence** with course cohort pipeline (finding #12)
8. **Rewrite outreach** to lead with 5-star participant sourcing (finding #15)
9. **Consider recording a Loom video** (finding #14)

### Nice-to-have (Low Priority)
10. Clarify that "top 1%" pool replenishes monthly (finding #1)
11. Add one sentence justifying Swapcard choice (finding #3)
12. Tighten "Why BlueDot" to focus on why assets enable this design (finding #8)
13. Add one sentence about auditing existing tools on onboarding (finding #10)
14. Add one sentence preempting the 1-on-1 exhaustion concern (finding #6)
