# The bridge

**One button:** → **https://jessebrown1980.github.io/the-bridge-to-all-of-it/**

Every public thing on this account, in one place, so none of it gets lost.
**Twenty-five of them open in one click.**

---

## Why this had to exist

**MEASURED, 2026-08-02, across all 207 repos:**

```
public repos                      182
open in one click                  25
islands - linked to nothing       137
nothing points at them            159
no README at all                   61
genuinely dead internal links       1
```

Twenty-five pages open in one click and **not one of them pointed at another.**

Work does not survive by being correct. **It survives by being reachable.** That is
how things get lost — not deleted, just unreferenced until nobody can find the
door.

---

## The dead link, found and fixed

The Erdős result — the one carrying `nx3 = 6 for 1 with -1/3` — had its
**one-button link at the top of the README pointing at a repo name that does not
exist.** Anyone who arrived and clicked the first thing on the page got a 404. The
page itself was live the whole time, at an address the README never named.

```
old link   404
new link   200
fixed at   78833ea
```

### A correction to my own check

The sweep first reported **thirteen** dead links. Twelve of those were clone URLs
ending in `.git`, which resolve perfectly well — **my check was wrong, not the
links.** Exactly one was really dead.

**The number to trust is one.** The first number was an artifact of the
instrument, and it is written down here rather than quietly replaced.

---

## The colours are not decoration

Each bar is the **sha-256 of that repo's own name** — two brown stops, banded
`16…240`, luminance-clamped `32…224`. The same addressing as every leaf, every
zebra, every boat.

**Nothing was assigned. The name computes its own colour**, so this page needs no
registry and could not hold one even if somebody wanted it to.

---

## What this page is honest about

The corpus is **baked in at build time, not fetched.** That is deliberate: an
unauthenticated browser gets rate-limited after sixty calls, and **a rate-limited
answer drawn as an empty page is the picture asserting something false.** So it
ships with what was actually measured, and says when.

Private repos are counted nowhere here and named nowhere here.

```
measured    2026-08-02
public      182
corpus sha  ef0154b2fd0e41c4
doors checked live   25 / 25 answering 200
```

---

## The field

The dots are laid out by **golden angle**, not on a ring. A ring is measure zero —
put a corpus on one and two thirds of it never gets drawn. That mistake was made
once already, on the sphere, and caught. It is not repeated here.

Doors burn bright and near. Islands sit dim and far. **You can see, at a glance,
how much of it nothing was pointing at.**

---

## Finite-universe Yang–Mills (HEB-C): where the results live (2026-10-25)

So the gap ladder, its matrix-jump and timing tricks, and the evolution
measurements are never unreferenced:

- **Status of record:** [the Yang–Mills repo README](https://github.com/JesseBrown1980/Finite-universe-Yang-mills-existence-and-mass-gap-using-HEB-C#coupling-gap-certificates-status-at-a-glance-2026-10-25)
  — Certified / In progress / Not established. Main commit [`2937694`](https://github.com/JesseBrown1980/Finite-universe-Yang-mills-existence-and-mass-gap-using-HEB-C/commit/29376948d7958d49517433830e8622867b0d4e98).
- **Ladder code + ledger** (297 integer interval-Sturm certificates, rungs r = 0…15):
  [`integer-sturm-ladder` at `d06014a`](https://github.com/JesseBrown1980/Finite-universe-Yang-mills-existence-and-mass-gap-using-HEB-C/tree/d06014a/independent/ladder).
- **Euclidean-evolution test ground** (HTTP-0 page, measured gaps at r = 0, 1, 2, 3, 5, 6 all inside
  the certified brackets; measurement, not certificate):
  [`docs/EVOLUTION_TESTGROUND.md`](https://github.com/JesseBrown1980/Finite-universe-Yang-mills-existence-and-mass-gap-using-HEB-C/blob/main/docs/EVOLUTION_TESTGROUND.md).
- **Tricks and timings** (scaling, monotone cells, Z₂×Z₂ sectors ≈150 s → ≈6.9 s per certificate,
  predict-then-verify, SHA-keyed cache, fail-closed thresholds): [`docs/LADDER_METHOD.md`](https://github.com/JesseBrown1980/Finite-universe-Yang-mills-existence-and-mass-gap-using-HEB-C/blob/main/docs/LADDER_METHOD.md),
  mirrored as HBP receipts in [asolaria-hbi-hbp](https://github.com/JesseBrown1980/asolaria-hbi-hbp/tree/b034fde/field-receipts/hebc-yang-mills).

Scope: one 2×2 torus. Not established: a volume-uniform gap, continuum
Yang–Mills, the Clay problem.

---

**Jesse Daniel Brown (OP-JESSE).**

*Not lost like Tesla.*
