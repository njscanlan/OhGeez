# Oh Geez for Claude

An appointment companion for parents and caregivers of kids with a feeding tube or feeding difficulty.

Kids on tubes often see a whole team: speech (SLP), occupational therapy (OT), physical therapy (PT), feeding therapy, a dietitian, GI, ENT, pulmonology and a medical supply company. Each one hands parents different notes, reports and homework. Oh Geez helps Claude keep it all in one plain-English place.

## What it does

- **Keeps one Care File per child:** the care team and contacts, the current plan with who prescribed each part and when, therapy goals and home programs, confirmed findings, open questions, a visit log and a glossary.
- **Prepares you for an appointment:** a one-page brief with what changed since the last visit, the top three questions for that provider, and what to bring.
- **Makes sense of it afterward:** paste in visit notes, an after-visit summary or a voice memo transcript and get what changed, what to confirm with the team and what to update at home.
- **Decodes reports:** swallow studies (VFSS, FEES), therapy evaluations and dietitian notes, one finding at a time, including scales like IDDSI and the Penetration-Aspiration Scale.
- **Turns homework into a daily checklist.**
- **Works with the free Oh Geez app** (https://oh-geez.netlify.app): it can summarize the logs in an Oh Geez backup file, or update the plan inside one.

## What it won't do

Oh Geez organizes and explains. It never diagnoses and never changes feed amounts, pump rates, formulas, textures, medications or exercises. Those always come from the child's care team. For urgent signs, such as trouble breathing or a G-tube that has come out, it tells parents to contact their team or emergency services right away.

## Data

This plugin is a single skill made of instructions. It runs no code, calls no services and sends nothing anywhere. It only works with what you share in your conversation with Claude, and it asks you to leave out record numbers, insurance IDs and birth dates.

## Install

In Claude Code:

```
/plugin install oh-geez --marketplace njscanlan/OhGeez
```

On claude.ai, you can also save the skill on its own: download `skills/oh-geez/SKILL.md` from this folder and add it under Settings > Capabilities > Skills.

## How to use it

Say something like "Help me get ready for my daughter's SLP visit on Tuesday" or "Here's the swallow study report, what does it mean?" and attach any notes or photos.

## License

MIT
