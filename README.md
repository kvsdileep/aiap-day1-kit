# AIAP Day 1 instructor kit

Instructor-facing material for Day 1 of Outskill's 14-day AI Accelerator: briefing AI, custom instructions, connectors, skills, and skill-based demos for content and data.

This folder is the single source of truth. Edit here, push to GitHub, and log the change below.

## Who uses what

| Instructor | Delivers | Script |
| --- | --- | --- |
| Dileep | International cohort | [scripts/dileep_international.md](./scripts/dileep_international.md) |
| Vishwas | India cohort | [scripts/vishwas_india.md](./scripts/vishwas_india.md) |

Both scripts follow the same sequence, prompts and checks. Vishwas's version uses IST, a login-based site of his choice for the browser demo, and his own voice skill. He can reword the spoken lines freely.

## Session at a glance

The host runs a 15-minute context-setting slot first. The main session is 150 minutes, then the breakout.

| Time | Section | Minutes |
| --- | --- | ---: |
| 00:00-00:40 | Ambition, the business review and personal instructions | 40 |
| 00:40-01:00 | Connectors, MCP and Skills | 20 |
| 01:00-01:10 | Browser automation behind a login | 10 |
| 01:10-01:15 | Break | 5 |
| 01:15-01:55 | Content: voice, brand and a few named skills | 40 |
| 01:55-02:25 | Spreadsheet analysis and dashboard | 30 |
| 02:25-02:30 | Review and breakout brief | 5 |
| From 02:30 | Breakout | To set |

The main session is instructor led. Learners practise in the breakout.

## Folder map

```text
aiap-day1-kit/
  README.md               this page
  scripts/                one script per instructor
  skills/README.md        skills used, original GitHub links, how to install
  skills/<name>/SKILL.md  skills built for this session
  resources/setup-notes.md   checklist and setup before the session
  resources/references.md    every article, study and doc the scripts cite
```

## Before you teach

1. Read your script end to end.
2. Work through the [setup checklist](./resources/setup-notes.md).
3. Install the skills on the [skills page](./skills/README.md).
4. Rehearse with a timer.

## Status

Not done yet: source packs, writing samples, brand material, account installs, browser access, rehearsal and slides.

## Changelog

- 17 Oct 2026. Version 4. Cut to 150 minutes, removed Claude Motion, merged the first two sections, added points from Miles Cranmer's talk, rewrote the spoken lines in Dileep's voice, opened up Vishwas's browser demo, added the one-line skill install. Moved everything into this folder.
- 17 Oct 2026. Voice skills and Outskill Slides prepared before the session and shown, not rebuilt live. Voice built from sent email or custom instructions. Outskill Slides (frontend-slides plus the Outskill website) also brands the dashboard. Added skills.sh. Removed the Brand Reference skill.
