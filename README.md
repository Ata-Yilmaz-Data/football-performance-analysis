# Football Performance Analysis | Warta Poznań Academy U16

From raw match footage to coach-ready player reports.

During my data operations internship at Warta Poznań (Feb–Jun 2026), I worked as a performance analyst for the U16 academy team. Raw match footage came in; structured, readable analysis went out to the coaching staff, in a regular analysis-and-feedback cycle with the coach.

This repository contains **anonymized samples** of that work. Player names are replaced with Player A–D.

---

## What I did

- **Analyzed raw match footage** and turned it into structured, trackable player data
- **Designed the report format** so a coach can read a player's match in seconds: one table, one radar chart, one page per player
- **Built a zone-based touch map** that shows where on the pitch the team's touches, key actions and mistakes happen
- **Delivered the reports on a regular schedule** and adjusted them based on the coach's feedback
- **Anonymized all player data** before sharing it here

## Player-specific reports (`WP-PSA`)

One page per player per match.

| Metric | What it captures |
|---|---|
| Goals / Assists | Direct goal contributions |
| Shoot | Shots taken and their outcome |
| Pass | Completed vs. attempted passes |
| 1v1 | Duel outcomes in 1v1 situations |
| Open Position | Finding and using free space |
| Dribble | Successful take-ons |
| Duels | Contested balls won vs. total |
| Line Breaks | Passes or carries that beat a line of defenders |

Each page also has a radar chart across five dimensions: **Finishing, Passing, 1v1 Mastery, Off the Ball, Dribble**. The radar gives the coach the player's profile at a glance, and the table gives the detail behind it.

## Touch map analysis (`WP-TMA`)

The pitch is split into four zones, and every touch is classified:

- Successful pass
- Dribble / progressive carry
- Key action (shot / key pass)
- Lost duel / forced turnover
- Unforced error / bad touch
- Critical turnover

The result is a visual map plus a zone-by-zone count, which shows where possession is built, where it is won and where it is lost.

## Files

| File | Content |
|---|---|
| `reports/Anonymized_WP-PSA-003.pdf` | Player-specific insights, 23.03.2026 |
| `reports/Anonymized_WP-PSA-004.pdf` | Player-specific insights, 23.03.2026 |
| `reports/Anonymized_WP-PSA-005.pdf` | Player-specific insights, 18.04.2026 |
| `reports/Anonymized_WP-PSA-006.pdf` | Player-specific insights, 30.04.2026 |
| `reports/Anonymized_WP-TMA-001.pdf` | Touch map analysis, 23.03.2026 |

## Tools

Excel · SQL · Power BI · Microsoft 365 · Canva

## Why this project

It shows how I work with data end to end: collect messy raw input, define what to measure, structure it, visualize it for a non-technical audience, and keep improving it through feedback.

---

*Author: Ata Yılmaz · [LinkedIn](https://www.linkedin.com/in/ata-yilmaz12/) · [GitHub](https://github.com/Ata-Yilmaz-Data)*
*Samples shared with permission. Match footage and raw data are not included.*
