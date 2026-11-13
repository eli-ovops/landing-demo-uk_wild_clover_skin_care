# Local v2 QA — Wild Clover Skin Care

Last locally verified: 2026-08-23T16:46:53+08:00. Scope: local static draft only.

## Mandatory reset status

- The prior `demo/` directory was not changed and remains the failed, read-only predecessor.
- The user’s visual-direction feedback (“low-grade”) overrides prior Owner self-assessment. Its self-check and screenshots are not used as v2 evidence.
- This v2 was made only after `DESIGN_INTENT.md` and `CROSS_DEMO_SIMILARITY_CHECK.md` were written.
- After user feedback that oversized words do not equal quality, the local draft was revised: headline scale is restrained and repetitive small-caps section labels were removed. The actual treatment photograph, booking metadata and spacing now carry the hierarchy. This remains an Owner revision, not independent visual acceptance.

## Rendered local evidence

| Check | Result | Reproducible evidence |
|---|---|---|
| Desktop render | Rendered at 1440 × 900 viewport | `qa/final/desktop-1440x900.png` (full-page capture: 1440 × 2471) |
| Mobile render | Rendered at 390 × 844 viewport | `qa/final/mobile-390x844.png` (full-page capture: 390 × 2928) |
| Horizontal overflow at 390px | None observed | Playwright evaluation returned `false` for `document.documentElement.scrollWidth > innerWidth` |
| Browser console | 0 errors, 0 warnings after final reload | Playwright `console error` on final local render |
| Booking actions | 2 visible booking links; both target the existing Ovatu booking URL | Playwright link inventory: `https://wildcloverskin.book.app/book-now` twice |
| Images | 2 image elements: current official logo and current official treatment photograph | `IMAGE_LEDGER.md`; no AI image used |
| Client-visible internal text | No placeholder, TODO, draft, internal process, deployment or outreach wording found in `index.html` / `styles.css` | local text scan on 2026-08-23 |

## Fidelity and scope check

- Customer-specific business, price, timing, location, treatment-method and review statements are mapped in `BUSINESS_FIDELITY_MAP.md` to official sources checked on 2026-08-23.
- Asset provenance, minimum use, authorization limitation and no-AI decision are recorded in `IMAGE_LEDGER.md`.
- Static-scope boundary: HTML/CSS only; there is no form, login, payment, backend, tracking, deployment or new booking system. All booking actions are ordinary external links to the existing Ovatu route.

## Required independent gate — not self-assessed

This Owner does **not** assert `CLIENT-SHOWABLE DEMO`, `READY`, or a visual score. A different Owner must assess the eight mandatory criteria from current `PROJECT_CORE.md` 14.6 and may pass only when the average is at least 8.0 and every criterion is at least 7.0.

**Status: 本地v2草稿完成，AWAITING INDEPENDENT VISUAL ACCEPTANCE。**

No deployment, upload, public release, contact, outreach, login, payment or external action was performed.
