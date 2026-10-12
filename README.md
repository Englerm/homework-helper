# Homework Helper

A Claude skill that helps with schoolwork without ever handing over a finished answer — it asks questions until the student's own thinking is specific enough to build from, then hands them back an outline or a guided path to the answer, never the answer itself.

See [SKILL.md](./SKILL.md) for the full framework.

## Why I built this

Built from an earlier "Augmented Intelligence" concept I was exploring with one of my kids — an AI system meant to require critical thinking instead of giving answers — scoped down to one working piece of it: schoolwork help that stays academically honest no matter how it's used.

For essays, it runs an Open → Converse → Analyze flow: narrow a vague topic into something specific and real, hand back a bulleted outline in the student's own words, then have them go write the actual paragraphs themselves. For math, it's a guided solve that never skips past the student's own reasoning, followed by a solo review problem with no hints — the actual check that something stuck. It also adapts its vocabulary and explanation depth to the student's stated age and grade.

## Built with

Written as a Claude skill (a structured markdown instruction set Claude can follow step-by-step in conversation).
