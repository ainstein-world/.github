<h1 align="center">Ainstein</h1>

<p align="center">
  A game world where learners build real AI, ML, and coding skills through quests, lessons, XP, and progression.
</p>

<p align="center">
  <a href="#what-were-building">What we're building</a>
  ·
  <a href="#inside-the-world">Inside the world</a>
  ·
  <a href="#for-contributors">For contributors</a>
</p>

---

## What we're building

Ainstein turns learning AI and software engineering into an explorable RPG.
Instead of treating progress as a checklist, Ainstein gives every learner a
character, a dashboard, a world map, quests, portals, skill growth, streaks,
badges, and boss challenges.

The goal is simple: make serious technical learning feel alive enough to keep
coming back to.

## Inside the world

- **The Realm**: an explorable 3D village where learners enter coding portals,
  solve lessons, collect coins, and unlock progress.
- **The Library**: structured curriculum paths such as Python foundations,
  AI basics, and project-based machine learning.
- **The System**: the progression layer that tracks XP, levels, ranks, stats,
  streaks, titles, achievements, and long-term mastery.
- **Quests and boss fights**: real projects that move learners from beginner
  coding toward advanced AI engineering.
- **Personal progression**: one character connects the world, lessons, quests,
  dashboard, and skill tree into a single learning journey.

## Current stack

Ainstein is currently built as a standalone React app backed by Supabase.

- React + Vite for the app experience
- Three.js for 3D world and character scenes
- Supabase Auth, database, storage, RLS, and progression logic
- Tailwind CSS and reusable UI components
- Base44 archive tooling for migrated content and assets

## Repository map

The organization will grow around a few clear surfaces:

- **App experience**: the learner-facing world, dashboard, lessons, profile,
  quests, and progression screens.
- **Curriculum content**: lessons, quests, checkpoints, project paths, and boss
  challenges.
- **Platform systems**: auth, persistence, progression rules, data migrations,
  seeding, media assets, and deployment.
- **Design system**: components, visual language, animations, audio cues, and
  interaction patterns that make Ainstein feel like a world.

## For contributors

We care about contributions that make Ainstein more useful, more stable, and
more delightful for learners.

Good places to help:

- Build or polish learner workflows
- Add curriculum paths, lessons, or projects
- Improve quest and progression systems
- Strengthen Supabase schema, RLS, and data integrity
- Tune performance for 3D scenes and dashboards
- Improve accessibility, responsiveness, and onboarding
- Write tests and documentation for core behavior

Before opening a pull request, please keep changes focused and explain the
learner outcome. If a change touches progression, auth, stored player state, or
database rules, include how you tested it.

## Local development

Most app repositories in this organization follow the same shape:

```bash
npm install
npm run dev
```

Apps that depend on Supabase also need local environment variables and database
setup instructions from their repository README.

## Principles

- Learning should feel earned, not assigned.
- Progression should reflect real work, not inflated numbers.
- Game mechanics should support mastery, not distract from it.
- The product should be welcoming for beginners and still meaningful for
  ambitious builders.
- Data integrity belongs in the platform, not just in the client.

---

<p align="center">
  Learn by building. Level by finishing. Grow one quest at a time.
</p>
