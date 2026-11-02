<div align="center">

# TAFAAR

**The risk-grading engine behind the TRUSCOR Rating.**

<p>
  <img src="https://img.shields.io/badge/ACCESS-TRUSCOR%20ONLY-D22128?style=for-the-badge" alt="TRUSCOR only" />
  <img src="https://img.shields.io/badge/LICENSING-NEVER-172B4D?style=for-the-badge" alt="Never licensed" />
  <img src="https://img.shields.io/badge/RATING-300%20–%20900-FFB000?style=for-the-badge" alt="Rating range" />
  <a href="https://truscor.org"><img src="https://img.shields.io/badge/TRUSCOR-PROJECT%20HOME-0B8793?style=for-the-badge" alt="TRUSCOR" /></a>
</p>

</div>

---

## Consumer credit needed a bureau

Lending did not become trustworthy because lenders became honest. It became
trustworthy because a neutral third party started scoring borrowers on one
standard, applied the same way to everyone, with no stake in the outcome of
any single loan.

Autonomous AI has no such institution. Every vendor grades its own homework,
every benchmark is chosen by the party it flatters, and no buyer can compare
two systems on the same axis.

**TAFAAR is the grading engine for that standard.**

## What it produces

TAFAAR takes `.sova` evidence and turns it into:

| Output | What it is |
|---|---|
| **The TRUSCOR Rating** | A private score from **300 to 900** |
| **Estimated Financial Exposure** | What the system's risk could plausibly cost |
| **A risk map** | Where the exposure sits across rules and regulations |

Crucially, it grades **evidence**, not claims, not questionnaires, and not a
vendor's description of its own controls. If it was not recorded and signed, it
does not enter the grade.

## Why it is never licensed

TRUSCOR's value is its neutrality, and neutrality is a structural property, not
a promise:

- No product in any category it rates
- No referral economics
- No certification business today
- No insurance on its balance sheet

Keeping the grading engine in-house is part of that structure. A rating engine
that others can run is a rating engine others can tune. One standard, applied
the same way to everyone, means exactly one operator.

## Where it sits in the stack

| Layer | Role |
|---|---|
| [SOVA Engine](https://github.com/TRUSCOR/SOVA-Engine) | Tests AI products and produces `.sova` evidence |
| [SOVA Black Box](https://github.com/TRUSCOR/SOVA-Blackbox) | Records AI systems running in production |
| [O.W.L](https://github.com/TRUSCOR/O.W.L) | The instrument: checks claims against real effects |
| **TAFAAR** | Grades the evidence into the TRUSCOR Rating |
| [SOVA OSS](https://github.com/TRUSCOR/SOVA-OSS) | The free, open-source toolkit and the open `.sova` format |

## About this repository

This repository is **information only**. TAFAAR is a trade secret and its
source is never published. There is no demo, and there will not be one.

What *is* open is the evidence format it grades — see
[SOVA OSS](https://github.com/TRUSCOR/SOVA-OSS).

## Get rated

**[truscor.org](https://truscor.org)** — five fields and a short call.

---

<div align="center">

© 2026 TRUSCOR Private Limited. All rights reserved.<br/>
<em>Where intelligence meets accountability.</em>

</div>
