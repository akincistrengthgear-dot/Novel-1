# Akinci Strength — Announcement Bar Copy

Geo-targeted 5-slot rotating bar. Mobile-first. Every line counted at ≤40 characters
so it holds one line at 320px. No banned words. No em dashes. No fake urgency.
Flags appear on Slot 2 only.

Character counts below are of the **text** (the star ★ counts as one). Flags are a
separate leading glyph and are not included in the text count.

---

## Cadence decision (read first)

Slot 2 uses **two deliberate shapes, split by shipping tier**. This is a feature, not
the fragmentation the last draft fell into.

1. **Free markets → benefit-led.** Lead with the word the buyer wants: *Free*. Then
   name the perk (express, no minimum, tariffs on us, Canada is free).
2. **Paid markets → reassurance-led.** Lead with *Tracked*, then set the cost
   expectation (*priced at checkout*) so there are no surprises. The destination is
   named inline when it fits ≤40 chars; otherwise the flag/globe carries the geo and
   the line stays generic.

Reasoning: the buyer's actual question differs by tier. Free-market buyers want to
know the perk; paid-market buyers want reassurance the parcel is tracked and that the
price is transparent. One unified shape would either bury the free perk or imply a
promise we don't keep in the paid markets. The split is intentional and it reads
intentional.

**Key-noun audit (whole bar as a set):** `belt` appears once, in Slot 4. Slot 3 uses
`buckle`. No noun is shared across adjacent slots.

---

## Slot 1 — Proof (static, never rotates, all markets)

| Line | Chars |
|---|---|
| `Rated 4.9/5 ★ by 360+ lifters` | 29 |

Rationale: leads with the rating, attributes it to lifters (not "customers"), and
stays inside the true claim. Deliberately **not** "360+ 5-star reviews" — a 4.9
average means not every review is 5 stars, so that would overclaim.

---

## Slot 2 — Shipping (changes per market)

### Free-shipping markets (benefit-led)

| Flag | Market | Line | Chars |
|---|---|---|---|
| 🇺🇸 | USA | `Free shipping. We cover US tariffs` | 34 |
| 🇸🇬 | Singapore | `Free express shipping, no minimum` | 33 |
| 🇨🇦 | Canada | `Free tracked shipping to Canada` | 31 |
| 🌏 | ASIA LCL (JP, TH, PH, HK, TW, CN, KR) | `Free express shipping, no minimum` | 33 |
| 🇹🇼 | Taiwan | `Free express shipping, no minimum` | 33 |
| 🌏 | Asia PP (MY, TH, BN, ID, KH) | `Free express shipping, no minimum` | 33 |

### Paid markets — destination named inline (reassurance-led)

| Flag | Market | Line | Chars |
|---|---|---|---|
| 🇬🇧 | UK | `Tracked to the UK, priced at checkout` | 37 |
| 🇩🇰 | Denmark | `Tracked to Denmark, priced at checkout` | 38 |
| 🇧🇬 | Bulgaria | `Tracked to Bulgaria, priced at checkout` | 39 |
| 🇲🇽 | Mexico | `Tracked to Mexico, priced at checkout` | 37 |
| 🇮🇳 | India | `Tracked to India, priced at checkout` | 36 |
| 🌍 | Africa (DZ, MA, TN, ZA, EG) | `Tracked to Africa, priced at checkout` | 37 |

### Paid markets — flag carries the geo, generic line (name too long or a catch-all)

All use the same line: **`Tracked shipping, priced at checkout`** (36 chars).

| Flag | Market |
|---|---|
| 🇦🇺 | Australia |
| 🇳🇿 | New Zealand |
| 🇪🇺 | EU (FI, PL, CH, IE, AT) |
| 🇪🇺 | Small EU (AD, GR, HU, IS, LT, LU, MD, RO, SK) |
| 🇪🇺 | Global market (BE, IT, LV, PT, SE — all European) |
| 🗺️ | Balkans (RS, BA, AL) |
| 🌎 | South America (AR, CL, EC) |
| 🌐 | Randoms (mixed continents) |
| 🌐 | International (49-country catch-all) |
| 🇺🇸 | **Backup region (USA)** → uses the USA free line above |

Dedupe summary: 4 Asia/SG markets share one free line; 9 paid markets share one
generic line; 6 paid markets are localized; USA, Canada are bespoke.

Rationale notes:
- **USA** leads with the tariff line — the single strongest trust lever for a US
  buyer afraid of a customs bill. Express-suspension is intentionally **not**
  advertised (you don't headline a downgrade); "tracked" is implied by the offer.
- **Canada** leads with *Free* and *tracked*. The previous draft undersold Canada by
  omitting "free." Fixed.
- **Europe groups** use the generic line + 🇪🇺 rather than naming "the EU." The EU
  market contains Switzerland (not an EU member), so an inline "EU" claim would be
  false. The flag is geographic and truthful; the text stays accurate.

---

## Slot 3 — Warranty (static, all markets)

| Line | Chars |
|---|---|
| `Lifetime warranty on every buckle` | 33 |

Rationale: leads with the strongest **true** claim. Only belts and lever buckles are
lifetime, and the lever buckle is the part a powerlifter actually worries about
failing, so the specific claim is both credible and accurate. Uses `buckle`, leaving
`belt` for Slot 4 — no noun clash.

It does **not** imply everything is lifetime (sleeves are 1 year, wraps and straps are
6 months). See trade-off below.

---

## Slot 4 — Federation / compliance (static, all markets)

| Line | Chars |
|---|---|
| `Lever belts, USPA & IPL compliant` | 33 |

Rationale: correct claim tier. *Compliant* = passes the rulebook (allowed), not
*approved by* / *official partner* / *sponsored* (a formal relationship we are not
claiming). It is scoped to **lever belts specifically**, which is exactly right per
the gear nuance:

- Lever belts: **compliant**, built to USPA & IPL specs → the only items that earn
  the compliance claim.
- Knee / elbow sleeves: built to spec but **not** legal → deliberately excluded here.
- Shoes / slippers: built to spec (not a compliance claim).
- Straps / wraps: status unconfirmed → excluded.

Naming only "Lever belts" keeps us from implying the sleeves or anything else are
competition-legal.

> **⚠ Owner decision needed — orgs.** Earlier bar drafts said "USAPL & USPA"; the
> platform proof row said "IPL & USPA"; your latest note says "USPA and IPL." I've
> written **USPA & IPL** to match your latest note. Confirm the belts actually pass
> **IPL** (and not USAPL) before this goes live. If it's USAPL, swap to
> `Lever belts, USPA & USAPL compliant` (35 chars — still fits).

---

## Slot 5 — Campaign discount (shown only when a real code is live)

| Template | Example | Chars (example) |
|---|---|---|
| `{X}% off with code {CODE}` | `20% off with code STRONG20` | 26 |

Rationale: states the offer and the code in one complete phrase. No fake urgency, no
countdown, no "selling fast." Keep the code short so the filled line stays well under
40. Hide the slot entirely when no code is active.

---

## Trade-off callouts (your call)

1. **Slot 3 — truth kept, scope narrowed.** "Lifetime warranty on every buckle" is
   true and punchy but does not surface the sleeve (1 yr) and wrap/strap (6 mo) terms.
   I chose the strong lifetime lead over cramming the full matrix into 40 chars; the
   tiered terms belong on the product/warranty page. If you'd rather signal "all gear
   is covered," an alternative is `Lifetime on buckles, warranty on all` (36) — looser
   but broader. I recommend the buckle line.

2. **Paid generic line — accuracy over per-market warmth.** Nine paid markets share
   one line. This is a logistics line; it should be clear and tracked-forward, not
   clever. Punch here comes from brevity and the reassuring "Tracked" lead, not from
   voice. I traded individual warmth for consistency and zero risk of an inaccurate
   per-market promise.

3. **USA — express omitted.** Leading with "We cover US tariffs" means the paused
   express service isn't mentioned. That's deliberate (don't headline a downgrade),
   but if a buyer expects express, the product/shipping page must carry the notice.

4. **AU / NZ surcharges** are surfaced at checkout, not in the bar — there's no room
   for "surcharges may apply" inside 40 chars, and the generic line's "priced at
   checkout" already sets that expectation honestly.

---

## Shopify admin data-quality flags (fix in admin, not the theme)

These don't change the copy but cause markets to collide or mis-target:

- **TH** is in both ASIA LCL and Asia PP.
- **CN** and **HK** are in both ASIA LCL and Randoms.
- **SK** is in both Small EU and Randoms.
- **Randoms** traps major European countries (FR, DE, ES, NL, NO) who would get the
  better "across Europe" treatment if moved into the EU market.
