# Akinci Strength — Announcement Bar Copy (5-slot, per brief)

Mobile-first, one line at 320px. Every line counted ≤40 characters total. Slots 1–4 use
two-beat ` • ` format (left = headline beat, right = qualifier beat, no trailing period).
Slot 5 is a single-sentence CTA stinger with trailing period. No banned words. No em
dashes. No fake urgency. No fulfilment-origin claims.

**Format decision:** the announcement bar is a rotating strip widget. Two-beat ` • ` lines
scan in one second, carry two trust signals per slot, and match the storefront convention
buyers already pattern-match (Shopify default + brand sites). Single-sentence prose lines
read flat in a strip and waste horizontal real estate. Slot 5 stays single-sentence on
purpose — the CTA reads as a direct address, distinct from the trust beats.

**Display spec:**
- Rotation: 5 seconds per slot, fade transition
- Order: Proof → Shipping → Warranty → Compliance → Discount
- Hide Slot 5 when no live code → rotation drops to 4
- Separator: real `•` (U+2022) with one space either side
- Casing: sentence case across all slots (proper nouns and federation acronyms capitalised)

**Whole-bar noun audit (one key noun per slot, no repeats):**
- `belts` and `lever` → Slot 4 only
- `gear` → Slot 3 only (warranty covers the whole catalogue, not just belts)
- `lifters` → not used; Slot 1 carries volume + rating instead

**Cadence rule (two-beat tier):** the right-half qualifier is a label-style beat by design,
so some repetition across markets is inherent to the format. Discipline: **no right-half
signature appears more than 3× within a tier, and never in two adjacent rows.** Six
qualifier variants are used (`Tracked shipping`, `Tracked delivery`, `Fully tracked`,
`Ships tracked`, `Fully tracked delivery`, `Shipping fully tracked`); left-halves vary
between geo-only, region-with-preposition, qualifier-noun, and buyer-address shapes so the
master list never reads as a country-swap template.

---

## Slot 1 — Proof (static, all markets)

| Line | Chars |
|---|---|
| `3,700+ orders shipped • Rated 4.9/5` | 35 |

Rationale: two trust signals in one slot — order volume (social proof at scale) and rating
(satisfaction). `3,700+` rounds down with a `+` so the number stays true as you grow. `4.9`
keeps the exact mean (no inflated "5-Star"). **Owner-confirm:** the 3,700+ figure must be
the true current shipped count before publish.

---

## Slot 2 — Shipping (per market, two-beat)

### Free markets

| Flag | Market | Line | Chars |
|---|---|---|---|
| 🇺🇸 | USA | `USA • Free shipping, tariff covered` | 35 |
| 🇸🇬 | Singapore | `Singapore • Free express shipping` | 33 |
| 🌏 | ASIA LCL (JP, TH, PH, HK, TW, CN, KR) | `Across Asia • Free shipping` | 27 |
| 🇹🇼 | Taiwan | `Taiwan • Free express shipping` | 30 |
| 🌏 | Asia PP (MY, TH, BN, ID, KH) | `Southeast Asia • Free & tracked` | 31 |
| 🇨🇦 | Canada | `Canada • Free shipping, tracked` | 31 |

### Paid markets (rate shown at checkout)

| Flag | Market | Line | Chars |
|---|---|---|---|
| 🇬🇧 | UK | `UK • Tracked shipping` | 21 |
| 🇦🇺 | Australia | `Australia • Tracked delivery` | 28 |
| 🇳🇿 | New Zealand | `New Zealand • Fully tracked` | 27 |
| 🇩🇰 | Denmark | `Denmark • Tracked shipping` | 26 |
| 🇧🇬 | Bulgaria | `Bulgaria • Ships tracked` | 24 |
| 🇲🇽 | Mexico | `Mexico • Tracked delivery` | 25 |
| 🇮🇳 | India | `India • Fully tracked delivery` | 30 |
| 🇪🇺 | EU (FI, PL, CH, IE, AT) | `Across Europe • Tracked shipping` | 32 |
| 🇪🇺 | Small EU (AD, GR, HU, IS, LT, LU, MD, RO, SK) | `European orders • Fully tracked` | 31 |
| 🇪🇺 | Global market (BE, IT, LV, PT, SE) | `Across the EU • Shipping fully tracked` | 38 |
| 🗺️ | Balkans (RS, BA, AL) | `Balkans • Tracked delivery` | 26 |
| 🌎 | South America (AR, CL, EC) | `South America • Ships tracked` | 29 |
| 🌍 | Africa (DZ, MA, TN, ZA, EG) | `Africa • Fully tracked` | 22 |
| 🌐 | Randoms (mixed continents) | `Wherever you lift • Ships tracked` | 33 |
| 🌐 | International (49-country catch-all) | `Worldwide • Shipping fully tracked` | 34 |
| 🇺🇸 | Backup region (USA) | uses the USA line above | 36 |

Per-line notes:
- **USA** — leads with the geo, lands on the tariff (the US buyer's real fear). Express pause
  not advertised here; put it on the shipping page.
- **EU / Global / Small EU** — `EU` says *Europe* (Switzerland isn't in the EU); `Global`
  says *the EU* (all five members); `Small EU` says *European* (Andorra, Iceland, Moldova
  aren't EU).
- **Randoms** — continent-mixed bucket; "Wherever you lift" stays destination-neutral and
  nods to the buyer's identity without burning the `lifters` noun.

---

## Slot 3 — Warranty (static, all markets)

| Line | Chars |
|---|---|
| `Powerlifting gear • Guaranteed` | 30 |

Rationale: keyword-first headline beat (`powerlifting gear` carries the SEO weight); single
word `Guaranteed` lands the promise. Drops the "is under warranty" boilerplate that read
like legal small print. Blanket claim is honest — every product, including deadlift
slippers, is confirmed warranty-covered (AU ACL, EU/UK statutory-guarantee markets safe).

Trade made on purpose: keyword wins this slot over the lifetime-belt flex. Per-product terms
(lifetime on lever belts and buckles; shorter on the rest) live on each product page.

No `belt`, `lever`, or `lifters` spent — Slot 1 and Slot 4 keep their nouns.

---

## Slot 4 — Federation / compliance (per market — geo-split)

Federations are regional, so this slot is geo-targeted like shipping. A US lifter competes
under the American bodies; everyone else competes under the international one. Two true
values, mapped to the same 21 markets as Slot 2.

| Region | Market(s) | Line | Chars |
|---|---|---|---|
| 🇺🇸 America | USA (+ USA backup region) | `Lever belts • USAPL & USPA compliant` | 36 |
| 🌍 International | every other market: SG · Asia LCL · TW · Asia PP · CA · UK · AU · NZ · DK · BG · MX · IN · EU · Small EU · Global · Balkans · S. America · Africa · Randoms · International | `Lever belts • IPL compliant` | 27 |

Rationale: keyword **compliant** — the belts pass the rulebook (the correct tier, not
*approved* or *sponsored*, which assert a formal relationship that isn't true across the
whole range). **USAPL & USPA** are the American bodies (USPA only exists in the US), so the
US buyer sees the feds they actually lift under; **IPL** is the international body, so every
overseas buyer sees the one that governs their platform.

Why two values and not 21: state compliance only where the source confirms it — never
invent. USAPL, USPA, and IPL are confirmed. Writing a different national federation for each
country would be a fabricated legal claim, so the slot personalizes on the only real axis —
American vs international — and stops there.

Scoped to lever belts only, on purpose — sleeves are made to spec but not legal, slippers
made to spec, straps and wraps unconfirmed — so the rest never reads as competition-legal.

---

## Slot 5 — Campaign discount (single-sentence stinger; shown only when a code is live)

| Template | Example | Chars |
|---|---|---|
| `Code {CODE} knocks {X}% off.` | `Code AKINCI15 knocks 15% off.` | 29 |

Rationale: the CTA stays a single sentence on purpose — it reads as a direct address to the
buyer, breaking the two-beat rhythm of the trust slots so the eye lands on it as the
"close." "knocks" is physical and does real work. No countdown, no "selling fast." Hide the
slot when no code is active so the rotation cleanly drops to 4.

---

## Trades for you to decide

1. **Slot 1 `3,700+` needs owner confirmation.** Must be the true current shipped count.
   Round down to a defensible figure if the live number is lower; the `+` keeps it honest
   as you grow.
2. **Slot 3 is a catalogue-wide claim.** Covers sleeves, wraps, straps, belts, and deadlift
   slippers — all confirmed warranty-covered by the owner, so the blanket claim is honest,
   including in AU ACL and EU/UK statutory-guarantee markets. Per-product terms (lifetime on
   lever belts and buckles; shorter on the rest) live on each product page.
3. **Paid lines omit cost.** They state tracked delivery; the rate shows at checkout. No
   line claims free.
4. **USA omits the express pause.** The tariff line is the stronger message; put the
   suspension on the shipping page.
5. **AU / NZ surcharges** surface at checkout — they don't fit a 40-char line, and no line
   promises a flat rate.
6. **Slot 4 international says IPL (the body you confirmed).** IPF — not IPL — governs most
   EU / UK / AU / NZ / Asia platforms. If your lever belts also meet IPF spec, confirm it
   and the international line can geo-target IPF to those markets; until then it stays IPL
   so it never fabricates a federation.

## Shopify admin fixes (data, not copy)

These are zone/profile overlaps the copy can't control — fix the bucket each country
resolves to in Shopify:

- **CN, HK — blocker.** Both sit in ASIA LCL (**free**) *and* Randoms (**paid**). If the
  paid Randoms zone wins, a free-promised buyer sees a tracked-not-free line or gets
  charged. Make the **free Asia LCL** bucket win for CN and HK.
- **TH** is in both ASIA LCL and Asia PP — both free, so no contradiction; pick one (Asia
  PP fits "Southeast Asia") to drop the duplicate zone.
- **SK** (Slovakia — *not* South Korea, which is KR in Asia LCL) is in both Small EU and
  Randoms — both paid; keep it in **Small EU** for the right regional line.
- **Randoms** traps FR, DE, ES, NL, NO — all paid, so no free/paid break, but they'd get
  the proper "across Europe" line if moved to the **EU** market.
