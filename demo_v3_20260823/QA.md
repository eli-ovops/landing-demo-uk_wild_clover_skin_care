# Local QA — Wild Clover Skin Care v3

> **AUTHORITATIVE 9.5 FINISHING-PASS QA — 2026-08-23.** This supersedes earlier top-viewport descriptions. The refreshed Hero occupies the full 1440px viewport, keeps its one real treatment image and original mark, and carries the verified 151-public-review and Fox Den/Shawlands details as a quiet decision line below the existing booking handoff. No claim, image, route or interactive scope was added.

| Check | Result | Current evidence |
|---|---|---|
| Desktop Hero viewport | PASS | `qa/final/desktop-1440x900.png` is an actual `1440 × 900` viewport capture; the Hero height evaluated to 900px and the booking CTA remains visible. |
| Mobile Hero viewport | PASS | `qa/final/mobile-390x844.png` is an actual `390 × 844` viewport capture; the booking CTA is visible and has a 50px height. |
| Mobile safety check | PASS | At 375px, browser evaluation returned `scrollWidth = 375`; no horizontal overflow. |
| Images | PASS | After a full-page browser scroll, all 6 rendered ledgered images had positive natural width. |
| Browser console | PASS | 0 errors and 0 warnings in the final local browser session. |

`INDEPENDENT VISUAL RE-ACCEPTANCE = AWAITING`  
`CLIENT-SHOWABLE DEMO = FAIL`

---

> **AUTHORITATIVE LOWER-PAGE RECOMPOSITION QA — 2026-08-23.** This record supersedes earlier statements in this file that describe visible `Concept Preview`, a full-coral booking panel, or the prior sparse practice layout. Direct user feedback removed the visible internal label. The current lower-page composition is a compact sage practitioner/location panel followed by a dark booking handoff with coral used only for the decisive button and separator.

## Current verification for this revision

| Check | Result | Current evidence |
|---|---|---|
| Required desktop viewport | PASS | `qa/final/desktop-1440x900.png` — actual `1440 × 900` top-of-page viewport from this revision. |
| Required mobile viewport | PASS | `qa/final/mobile-390x844.png` — actual `390 × 844` top-of-page viewport from this revision. |
| Lower-page desktop viewport | PASS | `qa/final/desktop-practice-booking-1440x900.png` — actual `1440 × 900` viewport covering the recomposed practitioner/location and booking sections. |
| Lower-page mobile viewport | PASS | `qa/final/mobile-practice-booking-390x844.png` — actual `390 × 844` viewport covering the responsive lower-page transition. |
| Narrow overflow | PASS | Current Playwright evaluation at 390px returned `false`. |
| Browser console | PASS | Current local Playwright session returned 0 errors and 0 warnings. |
| Booking handoff | PASS | The retained CTA targets the existing `https://wildcloverskin.book.app/book-now` route. |

No deployment, upload, publication, contact, outreach, login, payment or Git write was performed. This is local browser QA only; it does not replace independent visual acceptance.

**INDEPENDENT VISUAL RE-ACCEPTANCE = AWAITING**  
**CLIENT-SHOWABLE DEMO = FAIL**

---

> **AUTHORITATIVE FINAL-POLISH QA — 2026-08-23.** This record supersedes the prior photo-editorial output below. Current first-viewport proof requires the Hero to contain the real treatment image, current transparent brand mark, factual location statement, and an externally linked booking CTA. Current page verification must use the fresh `qa/final` screenshots produced after this rebuild, not previous screenshots or frozen hashes.

## Final-polish browser verification

| Check | Result | Current evidence |
|---|---|---|
| Desktop decision viewport | PASS | `qa/final/desktop-1440x900.png`, actual `1440 × 900` viewport screenshot. Hero CTA is fully visible. |
| Mobile decision viewport | PASS | `qa/final/mobile-390x844.png`, actual `390 × 844` viewport screenshot. Hero CTA is fully visible. |
| Service composition | PASS | `qa/final/desktop-services-1440x900.png` shows all five verified services in the current asymmetric hierarchy. |
| Treatment composition | PASS | `qa/final/desktop-treatment-sequence-1440x900.png` shows the current ledgered public-treatment-image composition. |
| Public review composition | PASS | `qa/final/desktop-reviews-1440x900.png` and `qa/final/mobile-reviews-390x844.png` show three current public review excerpts with their visible names, dates, five-star ratings, and an external reviews-page link. |
| 390px overflow | PASS | Current browser evaluation returned `false`. |
| Images | PASS | 6 rendered images loaded with positive natural width after scrolling through the page. |
| Links | PASS | 2 links to the existing Ovatu booking page and 1 link to the existing public reviews page. |
| Browser console | PASS | 0 errors and 0 warnings in the current local Playwright session. |
| Client-visible internal-text gate | PASS | Current `index.html` and `styles.css` scan returned no prohibited internal, AI, rights, authorization, source, ledger, TODO, draft, PMO, or placeholder language. |

**INDEPENDENT VISUAL RE-ACCEPTANCE = AWAITING**  
**CLIENT-SHOWABLE DEMO = FAIL**

---

> **AUTHORITATIVE PHOTO-EDITORIAL REBUILD QA — 2026-08-23.** This is the only current QA record for the photo-editorial rebuild. Every entry below this block that refers to an earlier palette, layout, frozen hash, score, or time-review closure is historical only and must not be used as acceptance evidence.

## Current browser verification

| Check | Result | Reproducible evidence |
|---|---|---|
| Desktop viewport | PASS | `qa/final/desktop-1440x900.png` is an actual `1440 × 900` viewport capture from the current local page. |
| Mobile viewport | PASS | `qa/final/mobile-390x844.png` is an actual `390 × 844` viewport capture from the current local page. |
| Treatment sequence viewport | PASS | `qa/final/desktop-treatment-sequence-1440x900.png` is a separate `1440 × 900` viewport capture after scrolling to the real-treatment-image section. |
| Service and decision details | PASS | `qa/final/desktop-services-1440x900.png` is a current `1440 × 900` viewport capture of all five verified services, durations and prices. |
| Responsive overflow | PASS | Browser evaluation at both required viewport widths returned no horizontal overflow. |
| Image loading | PASS | All 6 rendered image elements completed with a positive natural width: six distinct public assets, including the verified transparent logo used once as the Hero mark. |
| Booking handoff | PASS | Exactly 3 page links target the existing `https://wildcloverskin.book.app/book-now` route. |
| Browser console | PASS | Current local Playwright session: 0 errors, 0 warnings. |
| Client-visible internal text | PASS | Scan of current `index.html` and `styles.css` found no visible internal/governance, source, rights, authorization, AI, TODO, draft, or placeholder language. `Concept Preview` remains intentionally visible. |

## Current design and scope check

- Opening now leads with the owner’s real treatment image and restrained practitioner/location context; the display type is a supporting note, not the spectacle.
- The verified transparent Wild Clover logo is reused as a restrained, non-interactive Hero mark; it is not re-drawn, altered, or AI-generated.
- The middle of the page uses four distinct, real public Wild Clover treatment images as an editorial sequence. They are documented in `IMAGE_LEDGER.md`; the previously generated botanical image is retained locally but is not rendered.
- Current service choice uses only five verified appointment names, durations and prices. It makes no outcomes, clinical, credential, testimonial excerpt, package, discount, or gift-card claims.
- The current service list now includes all five verified appointments. The decision layer states the verified location/postcode and 150 published-review count. Fixed weekly opening hours remain unlisted publicly, so the page accurately says appointments are by booking with live times online.
- All interaction remains a static external handoff to the existing Ovatu booking page. No form, backend, login, payment, tracking, deployment, publication, contact or outreach was performed.

## Acceptance boundary

`Actual Demo Minutes` for this final photo-editorial revision is **NOT VERIFIED**; prior time figures are tied to an earlier frozen state and cannot close the current time-anomaly review.

This producing Owner does not assign a visual score or claim `CLIENT-SHOWABLE`, `READY`, Hook PASS, Product PASS, Bottom-40% PASS, or independent acceptance. A different Owner must assess the current desktop and mobile artifacts against all eight criteria (average ≥ 8.0; no criterion < 7.0).

**INDEPENDENT VISUAL RE-ACCEPTANCE = AWAITING**  
**CLIENT-SHOWABLE DEMO = FAIL**

---

> **AUTHORITATIVE OPTIMISATION QA — 2026-08-23.** The direct user feedback on prior v3 presentation led to a new information architecture and CSS system. Earlier screenshots and local QA entries below are historical and cannot evidence this revision.

## Current local verification

| Check | Result | Stable evidence |
|---|---|---|
| Desktop viewport | Rendered at exactly 1440 × 900 | `qa/final/desktop-1440x900.png` — actual PNG 1440 × 900 |
| Mobile viewport | Rendered at exactly 390 × 844 | `qa/final/mobile-390x844.png` — actual PNG 390 × 844 |
| Narrow viewport overflow | PASS | At 390px, `scrollWidth = 390`; no horizontal overflow |
| Visible Concept identity | PASS | Header exposes the natural visible label `Concept Preview` in both layout modes |
| Existing booking route | PASS | 3 page links, all exactly `https://wildcloverskin.book.app/book-now` |
| Browser console | PASS | 0 errors, 0 warnings in local Playwright session |
| Image loading | PASS | 6 image elements: verified logo, original verified treatment image and 4 additional verified public `/pass` treatment images; all loaded |
| Treatment-sequence viewport | PASS | `qa/final/desktop-treatment-sequence-1440x900.png` — actual 1440 × 900 viewport, distinct from the required top-of-page captures |
| Client-visible internal-text scan | PASS | No visible AI, source, rights, authorization, ledger, draft, PMO, TODO or placeholder language; permitted `Concept Preview` retained |

## Revision-specific review

- The opening is now a concise practitioner introduction. The public treatment image is a separate documented scene, rather than a darkened Hero or a text-overlay campaign panel.
- Selected appointments are a vertical, non-card decision list with real service name, duration and price. The visible copy does not add results, credentials, customer quotations or unverified treatment benefits.
- Four real images from Wild Clover’s public `/pass` page now form a treatment-process sequence after appointment choices. No pass/package copy, price, expiry, purchase controls or discounts are brought into the Demo; the generated botanical image is not rendered.
- Only the registered public Wild Clover logo and current treatment image are used; `IMAGE_LEDGER.md` and `BUSINESS_FIDELITY_MAP.md` remain applicable.
- No backend, form, login, payment, tracking, deployment, upload, contact or outreach was performed.

`TIME ANOMALY REVIEW = CLOSED — EVIDENCE SUBMITTED FOR FINAL RE-ACCEPTANCE`: PMO's task-state second read establishes two auditable Agent execution turns: `01a02dd2-c42f-7751-a5e7-106436cec31a` = `711165ms`, and `01a02de5-5fd3-7083-abfc-fea3707e1135` = `471565ms`. The total is `1182730ms` (`19m42.730s`), recorded as `Actual Demo Minutes: 19m43s` (approximately `19.7 minutes`). No human time, research time or older-version time is asserted.

Because the total is below 20 minutes, speed is not an automatic pass. The anomaly may close only on the current frozen terminal independent visual evidence: average score `8.3`, every criterion at least `7`, real customer assets, strict `1440 × 900` Desktop and `390 × 844` Mobile review, visible `Concept Preview`, non-isomorphic architecture, and frozen source/render hashes. The conclusion comes from that independent visual evidence, not from elapsed time alone.

The four frozen artifacts remain identified by the Lavella `FINAL FROZEN BASELINE`:

| Frozen artifact | SHA-256 |
|---|---|
| `index.html` | `aaee0c65bdbfbac56b63038fc8d6ec587c55c86b74d5c57b4088b1dcbfee9f2d` |
| `styles.css` | `a0f856274c98e7700552376a127a7745d5bcbe57fb037a0332bc11009ff0f688` |
| `qa/final/desktop-1440x900.png` | `6fb9ad1bed0cfb2c81b4c216a7249e58f05c25eeba5505929a63c8a39daf5f43` |
| `qa/final/mobile-390x844.png` | `370f8aed1cb04301aa1a2db1820d65293e9583ca1d8b8d610809641db1a3a79d` |

**STATUS: AWAITING FINAL TIME-EVIDENCE RE-ACCEPTANCE**

**INDEPENDENT VISUAL ACCEPTANCE = AWAITING**  
**CLIENT-SHOWABLE DEMO = FAIL**

---

> **AUTHORITATIVE INDEPENDENT-REVIEW REWORK — 2026-08-23.** The prior full-page screenshots, old palette and first-v3 self-check below are historical only and cannot support the rework.

## Rework local verification

| Check | Result | Stable evidence |
|---|---|---|
| Desktop final viewport | Rendered and captured at exactly 1440 × 900 | `qa/final/desktop-1440x900.png` — actual PNG 1440 × 900 |
| Mobile final viewport | Rendered and captured at exactly 390 × 844 | `qa/final/mobile-390x844.png` — actual PNG 390 × 844 |
| Full-page substitution | Not used | The two files above are viewport captures, not full-page images |
| `Concept Preview` | Visible in both required viewports | Playwright `getByText('Concept Preview').isVisible()` returned `true` at final mobile check; header placement is shared by both viewports |
| Horizontal overflow at 390px | None observed | `document.documentElement.scrollWidth > innerWidth` returned `false` |
| Browser console | 0 errors, 0 warnings | Final Playwright console check |
| Booking URLs | 3 links, all to existing Ovatu booking page | `https://wildcloverskin.book.app/book-now` |
| Client-visible internal text | No prohibited governance/source/right/AI text detected; only permitted `Concept Preview` is visible | scan of `index.html` and `styles.css` required before independent review |

## Rework scope / fidelity

- HTML/CSS plus one short GSAP entrance. It uses only transform/opacity and is disabled under `prefers-reduced-motion`.
- No backend, login, form, payment, tracking, analytics, deployment, publication or external contact.
- The page uses only the official public logo and official public treatment photograph once each. `BUSINESS_FIDELITY_MAP.md` and `IMAGE_LEDGER.md` remain the source/risk records.
- `DESIGN_INTENT.md` and `CROSS_DEMO_SIMILARITY_CHECK.md` contain the authoritative rework addenda and explicitly reject the prior shared design system.

## Required independent re-acceptance

`Actual Demo Minutes` is 4, so a time-anomaly explanation is mandatory. The producing Owner does not self-score the eight criteria or claim Hook/Product/Bottom-40% passes.

**INDEPENDENT VISUAL RE-ACCEPTANCE = AWAITING**  
**CLIENT-SHOWABLE DEMO = FAIL**

No deployment, upload, release, contact, outreach, login, payment or Git write was performed.

---

## Rejected first-v3 record (historical)

Last locally verified: 2026-08-23T16:51:37+08:00. Scope: local static draft only.

## Reset and direction

- v1 (`demo/`) and v2 (`demo_v2_20260823/`) were not modified.
- v3 is a full visual and architecture reset following user rejection of the preceding direction. It uses a single forest-green studio-booking language, not a light editorial split screen or display-size-driven hierarchy.
- `DESIGN_INTENT.md` and `CROSS_DEMO_SIMILARITY_CHECK.md` were written before code.

## Final local render evidence

| Check | Result | Evidence |
|---|---|---|
| Desktop | Rendered at 1440 × 900 | `qa/final/desktop-1440x900.png` (full page 1440 × 2389) |
| Mobile | Rendered at 390 × 844 | `qa/final/mobile-390x844.png` (full page 390 × 2701) |
| 390px overflow | None observed | Playwright evaluated `document.documentElement.scrollWidth > innerWidth` as `false` |
| Console | 0 errors, 0 warnings | Final Playwright console check |
| Booking links | 3 links, all exact existing Ovatu route | `https://wildcloverskin.book.app/book-now` |
| Images | Exactly two image elements: one official logo, one official treatment photograph | `IMAGE_LEDGER.md`; image use is single-placement only |
| Internal-text scan | Only the permitted natural identity label `Independent concept preview` found; no prohibited internal/governance/source/rights/AI language | scanned `index.html` and `styles.css` |

## Static scope and fidelity

- HTML/CSS only. No form, database, login, backend, payment, tracking, analytics, deployment or new booking function exists.
- All business claims, prices, durations, location, practitioner identity, methods and review total are mapped in `BUSINESS_FIDELITY_MAP.md`.
- Asset provenance and the `CUSTOMER AUTHORIZATION: NOT VERIFIED` limitation are internal-only in `IMAGE_LEDGER.md`; they are not exposed in the page.
- Bottom 40% applies a verified method/practitioner/location decision layer and an existing Ovatu handoff. No generic CTA panel or duplicate contact channel was added.

## Independent gate — not self-assessed

`TIME ANOMALY REVIEW = CLOSED — EVIDENCE SUBMITTED FOR FINAL RE-ACCEPTANCE`; the current auditable duration is `19m43s`. See `ACTUAL_DEMO_MINUTES.md`.

This Owner does not assert `CLIENT-SHOWABLE DEMO`, `READY`, Hook PASS, Product PASS, Bottom 40% PASS, or the visual rubric. A different Owner must score the final Desktop and Mobile renders against all eight required criteria. Until then:

**INDEPENDENT VISUAL ACCEPTANCE = AWAITING**  
**CLIENT-SHOWABLE DEMO = FAIL**

No deployment, upload, publication, external contact, outreach, login, payment or other external action was performed.
