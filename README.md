---
description: "A live World Cup bracket maintained by GitBook Agent — updated overnight while Europe sleeps."
icon: futbol
layout:
  width: wide
  cover:
    visible: false
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: false
  pagination:
    visible: false
---

# ⚽ Async World Cup Tracker

**Days correct, zero manual edits: <code class="expression">space.vars.zero_edits</code>**

Matches play in North American evenings. Europe sleeps. The Agent updates the bracket. You wake up to docs that are already correct.

This site is a live demo of how GitBook Agent maintains documentation against a changing source — the same motion as keeping docs current with a moving codebase, running on the most perishable document we could find.

---

<table data-view="cards">
  <thead>
    <tr>
      <th></th>
      <th></th>
      <th data-hidden data-card-target data-type="content-ref"></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>📊 Group Standings</strong></td>
      <td>Live tables, updated after every matchday. Agent-maintained — do not edit by hand.</td>
      <td><a href="groups/standings.md">standings</a></td>
    </tr>
    <tr>
      <td><strong>🏆 Knockout Bracket</strong></td>
      <td>Who advances, who's eliminated. Redrawn by the Agent after each round.</td>
      <td><a href="knockout/bracket.md">bracket</a></td>
    </tr>
    <tr>
      <td><strong>🎯 Team Predictions</strong></td>
      <td>The GitBook team backs their nations. Human-written, no Agent involved.</td>
      <td><a href="team/predictions.md">predictions</a></td>
    </tr>
    <tr>
      <td><strong>📋 Match Results</strong></td>
      <td>The source of truth. Edit this file to trigger an Agent update.</td>
      <td><a href="data/results.md">results</a></td>
    </tr>
    <tr>
      <td><strong>🔁 How This Works</strong></td>
      <td>The product loop behind this site — and why a World Cup bracket is the perfect test.</td>
      <td><a href="how-it-works/the-loop.md">the-loop</a></td>
    </tr>
    <tr>
      <td><strong>🏅 Leaderboard</strong></td>
      <td>Whose predictions are holding up? Updated after every round.</td>
      <td><a href="team/leaderboard.md">leaderboard</a></td>
    </tr>
  </tbody>
</table>

---

{% hint style="info" %}
**Last updated:** <code class="expression">space.vars.last_updated</code> · Tournament runs <code class="expression">space.vars.tournament_start</code> – <code class="expression">space.vars.tournament_end</code>
{% endhint %}
