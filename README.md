# 🏉 Nations Championship 2026 Predictor

A single-file browser app for predicting the 2026 Rugby Nations Championship — enter scores, rank conferences, and pick your Grand Final champion.

## Features

- **Two prediction modes** — Quick Rank (drag teams into finishing order) or Match Predictor (enter scores for live standings)
- **Live standings** — automatically calculated using World Rugby bonus point rules (4 pts win, 2 draw, 1 losing bonus within 7)
- **Team Path** — trace any team's journey through their conference and into the Grand Final
- **Full schedule** — all 26 fixtures across the July and November series, with venue details
- **Grand Final picker** — conference winners auto-populate the final; click to crown your champion
- **Autosave** — all picks persist in `localStorage`, no backend needed

## Usage

Just open `NationsChampionship2026.html` in any modern browser. No build step, no dependencies, no server required.

## Tournament Format

12 nations split into Northern and Southern conferences. Each team plays 6 cross-hemisphere fixtures — 3 away in July (Southern Hemisphere) and 3 at home in November. The conference winner from each side meets in the Grand Final at Allianz Stadium, London on 29 November 2026.

| Conference | Teams |
|---|---|
| 🌍 Northern | Ireland, France, England, Scotland, Wales, Italy |
| 🌏 Southern | South Africa, New Zealand, Argentina, Australia, Fiji, Japan |

## Stack

Vanilla HTML, CSS, and JavaScript. Zero dependencies. Flags via [flagcdn.com](https://flagcdn.com). Typography via [Google Fonts](https://fonts.google.com) (Barlow / Barlow Condensed).
