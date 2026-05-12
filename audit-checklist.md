# Help Center Audit Checklist

Working artifact for the PolyFundr help-center audit. Tick items only after the rendered site is verified locally.

## P0 trust blockers

- [x] Fix system-wide inline currency/math rendering caused by unescaped `$` in MDX content.
- [x] Align challenge-pass language with the real rule model: challenge passing is equity-based; funded payout eligibility is realized-profit-based.
- [x] Remove or verify all bank-transfer payout claims so payout docs match the implemented wallet-address flow.
- [x] Document actual payout mechanics everywhere they are referenced: destination required on every request, realized profit only, pending amount reserved, and current payout cap if intentional.
- [x] Verify the documented `90%` payout split against the implemented fallback behavior and remove stale `7000` assumptions or stop relying on them.
- [x] Fix homepage suggested-article visual placeholders and asset/CORS failures.

## P1 content cleanup

- [ ] Make `/getting-started/how-it-works` the canonical overview page and reduce duplicate overview copy elsewhere.
- [ ] Make `/challenges/rules` the canonical rules page and trim `/faq/rules` down to short clarifications.
- [ ] Make `/funded/payouts` the canonical payout page and trim duplicated payout explanations elsewhere.
- [ ] Rewrite `/faq/rules`.
- [ ] Rewrite `/funded/payouts`.
- [ ] Rewrite `/getting-started/introduction`.
- [ ] Rewrite `/challenges/overview`.
- [ ] Rewrite `/faq/payouts`.
- [ ] Remove or verify unsupported availability claims such as broad country-support language.

## P2 layout and UX

- [ ] Add a clearer “Start here” path on the homepage for first-time readers.
- [ ] Replace oversized homepage suggested-article placeholders with real screenshots, diagrams, or smaller useful thumbnails.
- [ ] Add quick-reference rule summaries near the top of `/challenges/rules` and `/funded/risk-rules`.
- [ ] Add a stronger `Demo vs Challenge vs Funded` comparison.
- [ ] Add a stronger `Challenge vs Funded` comparison.
- [ ] Tighten mobile article header and breadcrumb treatment on long-title pages.
- [ ] Keep FAQ answers shorter and link back to deeper source pages.

## P3 diagrams and images

- [ ] Create a simple `Buy challenge -> Pass rules -> Get funded -> Request payout` flow graphic.
- [ ] Create a daily drawdown reset diagram.
- [ ] Create a trailing high-water-mark drawdown diagram.
- [ ] Create a `Demo / Challenge / Funded` comparison visual.
- [ ] Create an annotated event-page screenshot for trading docs.
- [ ] Create a worked PnL example visual.
- [ ] Create a payout lifecycle diagram.
