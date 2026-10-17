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
| 02:25-02:30 | Review and hand over to the team | 5 |
| From 02:30 | Breakout, briefed and run by the team | Set by the team |

The main session is instructor led. The team briefs and runs the breakout separately.

## Folder map

```text
aiap-day1-kit/
  README.md               this page
  scripts/                one script per instructor
  slides/slides.md        deck source, one spoken beat per slide
  resources/setup-notes.md   checklist and setup before the session
  resources/references.md    every article, study and doc the scripts cite
```

## Before you teach

1. Read your script end to end.
2. Work through the [setup checklist](./resources/setup-notes.md).
3. Build and install your own skills for the demos. Each mentor does this separately.
4. Rehearse with a timer.

## Status

Not done yet: source packs, voice and brand skills, account installs, browser access, rehearsal and the HTML deck. The deck source is in [slides/slides.md](./slides/slides.md).

## Changelog

- 17 Oct 2026. Version 4. Cut to 150 minutes, removed Claude Motion, merged the first two sections, added points from Miles Cranmer's talk, rewrote the spoken lines in Dileep's voice, opened up Vishwas's browser demo, added the one-line skill install. Moved everything into this folder.
- 17 Oct 2026. Voice skills and Outskill Slides prepared before the session and shown, not rebuilt live. Voice built from sent email or custom instructions. Outskill Slides (frontend-slides plus the Outskill website) also brands the dashboard. Added skills.sh. Removed the Brand Reference skill.
- 17 Oct 2026. Removed the skills folder. Each mentor builds and demos their own skills. Scripts link the public originals inline.
- 17 Oct 2026. Added slides/slides.md: 78 slides, intl-workshop family, one deck for both presenters.
- 17 Oct 2026. Removed the breakout activity from the scripts and slides. The team briefs and runs it.
- 17 Oct 2026. slides.md now shows each slide's on-screen text in its own block, separate from presenter notes.
- 17 Oct 2026. Slides cut to 66: removed the promise slide, the optional newest-tool slide and all demo slides. Each demo now sits in the facilitator notes, run by the presenter on screen.
