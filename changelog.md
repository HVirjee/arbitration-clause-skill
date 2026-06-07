# Arbitration Clause Design and Review — Changelog

---

## v0.7.5

Seat selection and output structure improvements.

- Seat candidates must now respond to a specific fact in the transaction. Generic global shortlists are not permitted.
- Seats are named at city level in clause drafting and analysis (Port Louis, Kigali, London, Paris).
- Regional institution scenario outputs now lead with a practical recommendation and complete clause where sufficient information is available, followed by brief reasoning and a concise alternatives list. Where a genuine strategic choice remains open, an options-based structure is used instead.
- Cost comparison outputs follow a clear hierarchy: attempt live calculator first; if unavailable, identify the required comparison and provide calculator links; never estimate.
- GAP materials, once retrieved and used, do not require a further general review caveat. Specific legal flags are reserved for specific identified issues.
- Expedited procedure thresholds are not hardwired; the applicable threshold depends on the institution, rules version, and date of the arbitration agreement. SIAC's three-tier procedure structure (Streamlined, Expedited, standard) is noted as a material differentiator.
- Cost calculator guidance in sources aligned with the binary calculator rule introduced in v0.7.4.
- Three residual fee-schedule references removed from the Time, cost and dispute value section. Permitted cost-figure sources are now stated consistently throughout: live calculator run, official calculator output, or stored verified example.

---

## v0.7.4

Analytical discipline and output quality improvements.

- The skill now extracts claimant/respondent posture, relationship duration, payment structure, and governing law context from available information before asking follow-up questions.
- Seats and institutions are treated as separate analytical choices throughout. They are never bundled in shorthand.
- GAP materials now appear as clickable hyperlinks in the output. Where a live jurisdiction chapter is found, the specific chapter link is included. Where not found, the GAP jurisdiction-analysis page is linked with a brief note.
- Cost figures must come from a live calculator run or a verified stored example with stated assumptions. Scale-based estimation from fee schedules is not permitted.
- Market preference claims require a citable source and calibrated language. Unsupported generalisations are not permitted.
- Where the governing law analysis identifies the controlling party's law as the natural starting point, any departure to a neutral third-country law must be supported by a stated positive justification.

---

## v0.7.3

GAP output links.

- Where GAP materials are relied on, clickable links to the relevant public resources are now included directly in the output: the traffic-light table where seat assessment is relevant, and the GAP jurisdiction-analysis page or specific chapter link where applicable. Chapter-author firms are not named in default outputs.

---

## v0.7.2

Institution selection and non-EMEA coverage.

- Institution selection no longer infers party preferences from nationality. Where party familiarity matters and no user-provided information is available, institutions are presented by role: conventional global option, regionally coherent neutral option, party-home option, proportionate-process option, sector-specific option.
- New worked example: Korea/Turkey franchise agreement demonstrating role-based institution selection and Korean law as the governing law starting point.
- New QA scenario covering non-EMEA transactions and role-based institution selection.

---

## v0.7.1

Institution selection calibration and cost-rule alignment.

- Institution selection now requires justification by transaction profile and user priorities. No institution is selected by default.
- Cost comparison surfacing aligned with the conditional rule introduced in v0.7: internal sense-check always; public output only where relevant criteria are met.
- New worked example: Italy/Egypt franchise agreement demonstrating Italian law as the governing law starting point and criteria-based institution selection.

---

## v0.7

Cost comparison discipline and output structure.

- Cost sense-check is now always performed internally where a value is available. Public surfacing is conditional: cost predictability, proportionality, access to justice, Delos on the shortlist, or user request.
- Regional institution proposal scenarios remain a specific exception: the cost comparison appears in the main answer where a value is available.
- Design Path outputs lead with the clause. Review Path outputs lead with the overall assessment.
- Seat selection, language of arbitration, and alternative institution selection all require positive justification tied to the transaction.

---

## v0.6

Governing law framework and attribution.

- Governing law analysis now follows a structured five-step framework: legal family of the parties; commercial leverage and subject matter control; place of performance; coherence with the seat; recommendation.
- Author attribution simplified to name only; fuller attribution in the README.
- Duration statistics reframed as most recently published relevant figures, with an instruction to verify before use.

---

## v0.5

Multilingual support and North American coverage.

- Where the user is working in a language other than English, the skill notes that most major institutions make their rules and model clauses available in multiple languages.
- AAA-ICDR and JAMS added as live options for contracts with a North American nexus.

---

## v0.4

SOE counterparties and multi-party architecture.

- Contracts involving SOEs and public bodies are not automatically outside scope. The skill assists with the commercial arbitration clause while flagging immunity, authority, procurement, and enforcement issues for specialist advice.
- Multi-party and multi-contract scenarios receive the commercial arbitration architecture before any specialist referral.

---

## v0.3.1

Institutional neutrality.

- Bias safeguards refined to apply symmetrically: no automatic inclusion of any institution, and no omission of relevant options where they match stated priorities.

---

## v0.3

DELOS COMARB, GAP chapter routing, and clause validity rating.

- DELOS COMARB flagged as a sector-specific option for commodity trading in energy and mining.
- GAP chapter routing: the skill checks the GAP jurisdiction-analysis page for live chapters and links them where available.
- Red / potentially void introduced as a severity rating distinct from Red / serious issue, for clauses that may not constitute a valid arbitration agreement at all.

---

## v0.2

Regional institution proposal structure.

- Where a counterparty proposes a regional institution, outputs follow a mandatory scenario framework: counterparty-proposed option, conventional international option, and a time- and cost-disciplined administered option.

---

## v0.1

Initial public release.

Core design path and review path. Seat assessment with GAP integration. Institution and rules selection. Governing law companion clause. Confidentiality. Tiered dispute resolution. Bias and credibility safeguards.
