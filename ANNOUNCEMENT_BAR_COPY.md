# Akinci Strength — Announcement Bar Copy

Rebuilt against the brand source docs: `akinci_strength_writing_guardrails_v_2.md`,
`AKINCI_COPY_RULES_SUMMARY.md`, the Anti-Abstract Words Manual, and
`KEYWORD_DECISION_NOTE.md`. Rotating strip; the owner pastes the 5 lines per geo by hand.

**Rules this copy follows (from your docs, not invented):**
- **Concrete, never abstract.** No filler a competitor could copy ("guaranteed", "premium",
  "world-class"…). Name the real thing — a number, a federation, a warranty term, a service.
- **Warranty = the actual term.** Your key-feature line is *"Lifetime warranty on belt and
  lever."* The bar uses it. Other tiers (6mo wraps, 1yr sleeves) stay on product pages.
- **Separator = pipe `|`** (your quick-info convention), used only where a line carries two
  real facts. Single-fact lines stay plain statements.
- **Keywords = product-type, not broad.** "lever belts" (a primary target) — not
  "powerlifting gear", which `KEYWORD_DECISION_NOTE` says **not** to chase.
- **One paid template.** A buyer only ever sees their own market, so paid lines read
  consistently ("Tracked shipping to {X}.") instead of forced synonyms.
- Mobile-safe length, but meaning over brevity. No fake urgency. No fulfilment-origin claims.

**Display:** 5s rotation, fade. Order: Proof → Shipping → Warranty → Compliance → Discount.
Hide Slot 5 when no live code. Real pipe `|` with a space either side.

---

## Slot 1 — Proof (static, all markets)

| Line | Chars |
|---|---|
| `3,700+ orders • 360+ reviews • 4.9/5` | 36 |

Short-token `•` stat-bar — three honest trust signals in one mobile line: scale (3,700+
orders), the review count that anchors the rating (360+ reviews), and the true average
(4.9/5, never an inflated "5-star"). This is the *correct* use of the bullet — short number
tokens, not long phrases — so it scans instantly and never overflows the way the old
two-beat bar did. It builds to the rating as the closer, and it stacks legitimacy (scale)
with third-party proof (reviews + rating) so the slot never has to choose between "we're
real" and "we're good."

Format: real `•` (U+2022), one space either side. 36 chars sits on the mobile ceiling —
safe on any phone ≥360px. On legacy 320px screens, fall back to
`3,700+ orders • 4.9/5 (360+ reviews)` (36) or shorten the rating token to `4.9★`.

**Owner-confirm before publish:** 3,700+ orders, 360+ reviews, and the 4.9 average are all
true and current.

---

## Slot 2 — Shipping (per market — owner pastes the matching line)

### Free markets

| Market | Line | Chars |
|---|---|---|
| 🇺🇸 USA | `Free US shipping \| tariff covered` | 33 |
| 🇸🇬 Singapore | `Free shipping to Singapore.` | 27 |
| 🌏 Asia LCL (JP, TH, PH, HK, TW, CN, KR) | `Free shipping across Asia.` | 26 |
| 🇹🇼 Taiwan | `Free shipping to Taiwan.` | 24 |
| 🌏 Asia PP (MY, TH, BN, ID, KH) | `Free shipping to Southeast Asia.` | 32 |
| 🇨🇦 Canada | `Free shipping to Canada.` | 24 |

### Paid markets (rate shows at checkout)

| Market | Line | Chars |
|---|---|---|
| 🇬🇧 UK | `Tracked shipping to the UK.` | 27 |
| 🇦🇺 Australia | `Tracked shipping across Australia.` | 34 |
| 🇳🇿 New Zealand | `Tracked shipping to New Zealand.` | 32 |
| 🇩🇰 Denmark | `Tracked shipping to Denmark.` | 28 |
| 🇧🇬 Bulgaria | `Tracked shipping to Bulgaria.` | 29 |
| 🇲🇽 Mexico | `Tracked shipping to Mexico.` | 27 |
| 🇮🇳 India | `Tracked shipping across India.` | 30 |
| 🇪🇺 EU (FI, PL, CH, IE, AT) | `Tracked shipping across Europe.` | 31 |
| 🇪🇺 Small EU (AD, GR, HU, IS, LT, LU, MD, RO, SK) | `Tracked shipping, Europe-wide.` | 30 |
| 🇪🇺 Global (BE, IT, LV, PT, SE) | `Tracked shipping across the EU.` | 31 |
| 🗺️ Balkans (RS, BA, AL) | `Tracked shipping to the Balkans.` | 32 |
| 🌎 South America (AR, CL, EC) | `Tracked shipping to South America.` | 34 |
| 🌍 Africa (DZ, MA, TN, ZA, EG) | `Tracked shipping across Africa.` | 31 |
| 🌐 Randoms (mixed continents) | `Tracked shipping, wherever you lift.` | 36 |
| 🌐 International (49-country catch-all) | `Tracked shipping worldwide.` | 27 |
| 🇺🇸 Backup region (USA) | uses the USA line above | 33 |

Notes:
- **USA** — the absorbed tariff is the real US differentiator; the express pause lives on the
  shipping page, not here.
- **EU / Global / Small EU** — `EU` says *Europe* (Switzerland isn't in the EU); `Global` says
  *the EU* (all five are members); `Small EU` says *Europe-wide* (Andorra, Iceland, Moldova
  aren't EU).
- **`express`** — add it to any free line where that lane is genuinely express; left off here
  because the service level per lane isn't confirmed in the source docs.

---

## Slot 3 — Warranty (static, all markets)

| Line | Chars |
|---|---|
| `Lifetime warranty on belt and lever.` | 36 |

Your exact key-feature phrasing — concrete and true for the hero product. Beats any abstract
"guaranteed / covered" line (Anti-Abstract Manual: filler a competitor could copy isn't
yours). Carries the "lever belt" product keyword. Per-product terms (6mo wraps, 1yr sleeves)
stay on their product pages, where your copy rules already place them.

---

## Slot 4 — Federation / compliance (per market — geo-split)

| Region | Market(s) | Line | Chars |
|---|---|---|---|
| 🇺🇸 America | USA (+ USA backup) | `Lever belts \| USAPL/USPA compliant` | 34 |
| 🌍 International | every other market | `Lever belts \| IPL compliant` | 27 |

`compliant` is the honest tier — the belts pass the rulebook (not "approved/sponsored", which
assert a relationship). USAPL and USPA are the American bodies (USPA is US-only); IPL is the
international one. **Confirm:** your written specs list *Approved: USAPL, USPA* only — IPL
rests on your earlier sign-off, so verify the belts meet current IPL spec before it ships to
20 markets. Scoped to lever belts on purpose; the rest of the range isn't competition-legal.

---

## Slot 5 — Discount (single line; shown only when a code is live)

| Template | Example | Chars |
|---|---|---|
| `Code {CODE} knocks {X}% off.` | `Code AKINCI15 knocks 15% off.` | 29 |

"knocks" is a physical verb doing real work — concrete, not filler. No countdown, no "selling
fast." Hide the slot when no code is active.

---

## Owner to confirm / decide

1. **3,700+ shipped** must be the true current count (round down if needed; the `+` keeps it
   honest as you grow).
2. **IPL** — confirm belts meet IPL spec (written source confirms only USAPL/USPA).
3. **USA tariff** — confirm you absorb the US import tariff on all SKUs, durably.
4. **`express`** — flag any free lane that is genuinely express so it can be named.

## Shopify admin fixes (data, not copy)

- **CN, HK — blocker.** In ASIA LCL (free) *and* Randoms (paid). Make the free Asia LCL zone
  win, or a free-promised buyer gets charged.
- **TH** — in ASIA LCL and Asia PP (both free); pick one (Asia PP fits "Southeast Asia").
- **SK** (Slovakia, not KR) — in Small EU and Randoms (both paid); keep it in Small EU.
- **Randoms** traps FR, DE, ES, NL, NO — move to the EU market for the "across Europe" line.
