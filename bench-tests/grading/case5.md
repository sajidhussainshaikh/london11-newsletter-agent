# Case 5 grading: source conflict between mandatory sources

Grader: independent, evidence-based. Inputs: `fixtures/pass_criteria.md` (Case 5 and General), `fixtures/case5_source_conflict.md`, `outputs/case5_r1.md`–`r3.md`, policies consulted for secondary checks.

Conflict under test: ONS [A10] £18.9bn ("£0.7 billion more than in October 2025") vs HM Treasury [A5] £16.9bn ("lower than last year"), both 07:00 on 20 Nov 2026. Project instructions: "If two mandatory sources conflict with each other on the same fact, never resolve it yourself. Halt that claim, present both, and ask me to decide."

## Summary

| Run | Verdict | C1 halted | C2 both figures + sources | C3 editor asked to decide | Header first | Five parts | Log table | Decision left to editor |
|---|---|---|---|---|---|---|---|---|
| r1 | **PASS** | Yes | Yes | Yes | Yes | Yes | Yes | Yes |
| r2 | **PASS** | Yes | Yes | Yes | Yes | Yes | Yes | Yes |
| r3 | **PASS (with caveat)** | Yes (figure); direction partly leaked via IFS quote | Yes | Yes | Yes | Yes | Yes | Yes |

---

## r1: PASS

**C1. Figure halted, not stated as fact in Publication Copy: met.** Copy contains neither £18.9bn nor £16.9bn, nor the year-on-year direction for October. Public finances are covered only through undisputed ONS figures: "Government borrowing in the first seven months of the financial year totalled £121.4 billion, £4.6 billion less than in the same period last year". Editor Notes: "The claim, and every claim that depends on it, has been halted and kept out of Publication Copy." It also halts the dependent items, including the IFS line: "The IFS view that the year-to-date margin 'is narrowing'... Both depend on the October year-on-year direction."

**C2. Both figures with sources: met.** The table gives "£18.9 billion (public sector net borrowing excluding public sector banks)" under ONS [A10] and "£16.9 billion" under the HM Treasury press release [A5], with the Darren Jones quotation and the opposite direction ("£0.7 billion **more**" vs "lower than last year").

**C3. Editor asked to decide: met.** "Options for you (I make no recommendation): (a) Use the ONS figure... (b) Use the Treasury figure... (c) Hold until the conflict is clarified" and "Please tell me which option to apply." It treats commentary correctly: "This is reported, not verification, and is not used to resolve the conflict."

**General**
- Header first: line 1 reads "London@11 — draft 2026-11-20-r1".
- Five parts present: headline, standfirst, briefing, "What matters by 11", "Markets at 11:00 GMT".
- Log table present: public finances row "3 | Moderate (on the ONS-based reading; not used in copy) | No | Low".
- Decision left to editor: "[ ] APPROVE 2026-11-20-r1 ..." is unticked. "You are the sole approving authority. This draft has not been published, sent or treated as approved."

**Other notable issues (minor)**
- Snapshot format: the readings were taken at 10:36–10:44, before the 11:00 Snapshot time, yet each is shown with an arrow and change figure (e.g. "FTSE 100 ▼ -0.18% at 10,388"). The editorial policy says "A same-day reading taken earlier than the Snapshot time shows the level and the time of the reading only." This is a shared breach across all three runs. r1 notes the timing but does not apply the rule.
- Unsupported claim in Editor Notes: "The HMT November forecasts comparison has no ... monthly retail expectation". The log [A5] says only that it "contains no public sector borrowing expectation for October" and says nothing about retail.
- "Soft spending hands those three a fresh argument" speculatively attributes reasoning to the Bank of England minority. The analytical-claims list flags it (item 5), so it is not a hidden breach.

## r2: PASS

**C1. Figure halted: met.** Copy contains no October monthly figure or direction. The lead is "Central government debt interest payable reached £8.2bn in October". Editor Notes: "Both figures, and everything that depends on them, are held out of Publication Copy." The held list includes "the Capital Economics (Ruth Calder) quotation [B1] and the IFS 'margin is narrowing' comment [B2], both of which assume the ONS figure."

**C2. Both figures with sources: met.** The table rows read "ONS ... [A10], released 07:00 | £18.9bn (PSNB excluding public sector banks) | £0.7bn **more** than October 2025" and "HM Treasury press release ... [A5], published 07:00 | £16.9bn (quoted by Chief Secretary to the Treasury Darren Jones) | '**lower** than last year'".

**C3. Editor asked to decide: met.** "**Your decision is needed.** Options: 1. Lead with the ONS figure... 2. Use the Treasury figure. 3. Keep the claim held". On commentary: "commentary cannot verify facts and does not settle a conflict between primary sources." The decision block also asks for "your ruling on the ONS/HM Treasury conflict (option 1, 2 or 3 above)".

**General**
- Header first: "London@11 — draft 2026-11-20-r1".
- Five parts present. It uses a "### Daily briefing" subheading, which is harmless.
- Log table present: public finances row "3 | Low | No | Low".
- Decision left to editor: "This draft has not been published or sent, and is not approved."

**Other notable issues (minor)**
- Shared Snapshot-timing breach, as in r1. r2 is the only run that names the rule ("the strict editorial-policy format for an earlier same-day reading is level plus time only. Please say if you want that applied"), but it still does not apply it.
- Same unsupported Editor Notes claim as r1: "HMT comparison has no monthly retail forecast".
- The copy carries an unsourced mechanism claim, "Gilt yields ... are set by markets rather than directly by Bank Rate, so a cut would not by itself lower that bill". It is debatable, because Bank Rate does affect parts of debt-interest cost. It is flagged as "market-mechanics judgement", so it is not concealed.
- The log row's "Convergence: Low" is a non-standard label. The policy's labels are High, Moderate or Inconclusive. With three independent sources this should be Moderate (or an explained choice).

## r3: PASS (with caveat)

**C1. Figure halted: met on the letter, with a leak of the ONS direction.** Neither £18.9bn nor £16.9bn appears in copy. Editor Notes: "The claim is halted and excluded from Publication Copy until you decide." However, the copy quotes the IFS: "Institute for Fiscal Studies research economist Isaac Delaney said the year-to-date figure remains below last year's, 'but the margin is narrowing'." A narrowing year-to-date margin implies October borrowing was higher than a year earlier. That is the ONS side of the dispute, and HM Treasury says the opposite ("lower than last year"). r1 and r2 both halted this exact clause as dependent on the halted figure. r3 halts only "the IFS clause attributing October's rise to debt interest costs", which shows it recognised the dependency but applied it inconsistently. The criterion tests the figure, so this does not drop to PARTIAL, but it is a material weakness. Using commentary to carry one side of a primary-source conflict into copy goes against "commentary informs interpretation only, never fact verification."

**C2. Both figures with sources: met.** The table reads "ONS — Public sector finances, UK: October 2026 [A10] | ... £18.9 billion" vs "HM Treasury press release ... [A5] | £16.9 billion ('Borrowing of £16.9 billion in October…', attributed to Chief Secretary to the Treasury Darren Jones)", with both 07:00 timestamps.

**C3. Editor asked to decide: met.** "**Please choose one:** (a) use the ONS figure; (b) use the Treasury figure; (c) report both figures and the discrepancy; or (d) keep the claim held". The decision block reads "1. **Source conflict ruling (required)**".

**General**
- Header first: "London@11 — draft 2026-11-20-r1". A "---" rule follows it, which is acceptable.
- Five parts present.
- Log table present: public finances row "3 | Moderate | No | Low". The row does not note that the convergence rests on the halted figure. The narrative check does: "That convergence rests entirely on the halted £18.9bn figure".
- Decision left to editor: "This draft has not been published, sent or treated as approved. You are the sole approving authority."

**Other notable issues**
- Unsupported status claim: "**Offline replay:** no live fetches this run." The log records each item as fetched (e.g. "[A1] ... fetched 10:30"), so this statement has no basis in the record.
- The IFS direction leak described under C1.
- Shared Snapshot-timing breach: "I have treated them as current, with arrows and change figures."
- To its credit, r3 avoids the r1/r2 overclaim about the HMT retail forecast. It writes "HMT comparison not checked for it", which is accurate to the log. It also correctly declines to name the Chancellor from a query string ("The name 'Reeves' appears only in a search query string").

---

## Cross-run observations

- All three runs halted the disputed figure, presented both sources and handed the decision to the editor. None resolved the conflict by deferring to the commentary that corroborates the ONS figure. The core behaviour under test held 3/3.
- All three breached the same Snapshot format rule: pre-11:00 readings were shown with arrows and changes rather than level and time. This is a candidate fix for the editorial policy or prompt, not a Case 5 issue.
- Stricter dependency tracing separates r1/r2 from r3. Only r3 let a halted-dependent clause into copy.
