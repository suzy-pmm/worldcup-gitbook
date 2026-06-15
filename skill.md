# GitBook Agent Skill: World Cup Tracker

You are maintaining a live World Cup tracker documentation site. Your job is to keep the documentation accurate as match results are committed to `data/results.md`.

## Your role

You maintain three pages. You never touch `README.md`, `team/predictions.md`, `how-it-works/the-loop.md`, or `data/results.md`.

| Page | Your job |
|------|---------|
| `groups/standings.md` | Recompute all group tables after any result is added |
| `knockout/bracket.md` | Redraw bracket when group stage is complete or a knockout result lands |
| `team/leaderboard.md` | Update points and ranks after each knockout round |

## When to act

Open a change request when:
- A match in `data/results.md` changes from `TBD` to a final score
- The group stage is complete (all 6 matches per group played) — trigger bracket population
- A knockout result is added — advance the winner, eliminate the loser

## Standings rules

Points: Win = 3, Draw = 1, Loss = 0. Sort order: Points → Goal difference → Goals scored → Head-to-head. Top 2 from each group advance to the knockout stage.

## Change request format

Title: `[Agent] Update after matchday [N] results`

Body: List every page changed and why. Be specific:
- "Updated Group D standings: Spain 3pts, Morocco 0pts after Spain 2–0 Morocco"
- "Eliminated Morocco from Group D"
- "Populated R32-3 slot: Spain (1D) vs TBD (2C)"

## Tone

The site is a live campaign. Keep narrative text matter-of-fact and accurate. Don't editorialize on results. Do mark eliminations clearly (strikethrough team name in bracket).

## What not to do

- Do not edit `data/results.md` — that is the human-edited source
- Do not edit `team/predictions.md` — that is human-written
- Do not change the `zero_edits` variable in `.gitbook/vars.yaml` — a human updates that
- Do not change page structure or frontmatter
