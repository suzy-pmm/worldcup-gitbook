---
description: "The source of truth. Edit a match status from TBD to Final to trigger an Agent update."
icon: list-check
---

# Match Results

{% hint style="warning" %}
**This is the only page you edit by hand.** Change a match from `TBD` to `Final` and commit to `main`. The Agent reads this page and opens a change request updating the standings, bracket, and leaderboard automatically.
{% endhint %}

## How to update a result

{% stepper %}
{% step %}
## Open this file in GitHub

Navigate to `data/results.md` in your repo → click the pencil (edit) icon.
{% endstep %}

{% step %}
## Change the status and score

Find the match row. Change `| TBD | TBD | TBD |` to `| FT | 2 | 1 |` (or the actual score).
{% endstep %}

{% step %}
## Commit to main

Scroll down → commit message: `"Result: [Team A] vs [Team B]"` → commit to `main`.

The Agent picks it up within minutes and opens a change request.
{% endstep %}
{% endstepper %}

---

## Group Stage Results

### Group A

| Match | Home | Score | Away | Status |
|-------|------|-------|------|--------|
| 1 | USA | FT 2-0 | Jamaica | FT |
| 2 | Panama | TBD | Bolivia | TBD |
| 3 | USA | TBD | Panama | TBD |
| 4 | Jamaica | TBD | Bolivia | TBD |
| 5 | USA | TBD | Bolivia | TBD |
| 6 | Jamaica | TBD | Panama | TBD |

### Group B

| Match | Home | Score | Away | Status |
|-------|------|-------|------|--------|
| 7 | Mexico | TBD | Honduras | TBD |
| 8 | Ecuador | TBD | Venezuela | TBD |
| 9 | Mexico | TBD | Ecuador | TBD |
| 10 | Honduras | TBD | Venezuela | TBD |
| 11 | Mexico | TBD | Venezuela | TBD |
| 12 | Honduras | TBD | Ecuador | TBD |

### Group C

| Match | Home | Score | Away | Status |
|-------|------|-------|------|--------|
| 13 | Argentina | TBD | Peru | TBD |
| 14 | Chile | TBD | Canada | TBD |
| 15 | Argentina | TBD | Chile | TBD |
| 16 | Peru | TBD | Canada | TBD |
| 17 | Argentina | TBD | Canada | TBD |
| 18 | Chile | TBD | Peru | TBD |

### Group D

| Match | Home | Score | Away | Status |
|-------|------|-------|------|--------|
| 19 | Spain | TBD | Morocco | TBD |
| 20 | Portugal | TBD | Germany | TBD |
| 21 | Spain | TBD | Portugal | TBD |
| 22 | Morocco | TBD | Germany | TBD |
| 23 | Spain | TBD | Germany | TBD |
| 24 | Morocco | TBD | Portugal | TBD |

### Group E

| Match | Home | Score | Away | Status |
|-------|------|-------|------|--------|
| 25 | France | TBD | Belgium | TBD |
| 26 | England | TBD | Paraguay | TBD |
| 27 | France | TBD | England | TBD |
| 28 | Belgium | TBD | Paraguay | TBD |
| 29 | France | TBD | Paraguay | TBD |
| 30 | Belgium | TBD | England | TBD |

### Group F

| Match | Home | Score | Away | Status |
|-------|------|-------|------|--------|
| 31 | Brazil | TBD | Croatia | TBD |
| 32 | Netherlands | TBD | Japan | TBD |
| 33 | Brazil | TBD | Netherlands | TBD |
| 34 | Croatia | TBD | Japan | TBD |
| 35 | Brazil | TBD | Japan | TBD |
| 36 | Croatia | TBD | Netherlands | TBD |

---

{% hint style="info" %}
Scores use format `FT | [home goals] | [away goals]`. For extra time: `AET`. For penalties: `PSO`.
{% endhint %}
