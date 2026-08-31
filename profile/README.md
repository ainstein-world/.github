<p align="center">
  <img src="./assets/ainstein-world-preview.png" alt="Ainstein world preview" width="100%">
</p>

<h1 align="center">Ainstein</h1>

<p align="center">
  An AI learning world where students build real coding, machine learning, and product skills through quests, lessons, projects, and progression.
</p>

<p align="center">
  <a href="https://ainstein-alpha.vercel.app"><strong>Open the App</strong></a>
  ·
  <a href="https://github.com/ainstein-world/ainstein-app">Main Repository</a>
  ·
  <a href="#repository-map">Repository Map</a>
  ·
  <a href="#contributing">Contributing</a>
</p>

---

## What We Are Building

Ainstein turns technical learning into a living game world. Instead of moving
through disconnected lessons, learners step into a guided environment with a
character, world map, dashboard, quests, streaks, badges, skill growth, and
project-based challenges.

The mission is to help learners go from curiosity to capability by making
serious AI and software engineering practice feel structured, visual, and worth
returning to.

## Product Experience

- **Ainstein Realm**: an explorable world for portals, quests, lessons, and
  progression.
- **Learner Dashboard**: a home base for XP, level, rank, coins, streaks,
  skills, titles, and achievements.
- **Library and Paths**: structured learning paths for Python, AI foundations,
  machine learning, and project-based practice.
- **Quests and Boss Challenges**: hands-on projects that turn lessons into
  applied work.
- **Progression System**: a persistent layer connecting the learner profile,
  world activity, skill growth, and mastery.

## Live Deployment

The current production app is available at:

**[ainstein-alpha.vercel.app](https://ainstein-alpha.vercel.app)**

Deployments are managed from the organization repository
[`ainstein-app`](https://github.com/ainstein-world/ainstein-app).

## Technology

Ainstein is currently built as a standalone React app backed by Supabase.

- React + Vite for the app experience
- Three.js for 3D world and character scenes
- Supabase Auth, database, storage, RLS, and progression logic
- Tailwind CSS and reusable UI components
- Base44 archive tooling for migrated content and assets

## Repository Map

The organization is split into focused repositories so the product, platform,
content, and visual direction can evolve cleanly.

| Repository | Purpose |
| --- | --- |
| [`ainstein-app`](https://github.com/ainstein-world/ainstein-app) | The learner-facing app: world, dashboard, lessons, profile, quests, and progression screens. |
| [`ainstein-platform`](https://github.com/ainstein-world/ainstein-platform) | Supabase schema, migrations, RLS policies, progression rules, seed scripts, and platform setup. |
| [`ainstein-content`](https://github.com/ainstein-world/ainstein-content) | Lessons, quests, learning paths, archive data, authored metadata, and curriculum material. |
| [`ainstein-design`](https://github.com/ainstein-world/ainstein-design) | Brand assets, design direction, visual prompts, production kits, and experience references. |

## Contributing

We care about contributions that make Ainstein more useful, reliable, and
delightful for learners. The best contributions improve a real learner outcome:
clarity, momentum, correctness, accessibility, performance, or creative depth.

Good places to help:

- Build or polish learner workflows
- Add curriculum paths, lessons, or projects
- Improve quest and progression systems
- Strengthen Supabase schema, RLS, and data integrity
- Tune performance for 3D scenes and dashboards
- Improve accessibility, responsiveness, and onboarding
- Write tests and documentation for core behavior

Before opening a pull request, keep the change focused and explain the learner
outcome. If a change touches progression, authentication, stored player state,
or database rules, include how it was tested.

## Local Development

Most app repositories in this organization follow the same shape:

```bash
npm install
npm run dev
```

Apps that depend on Supabase also need local environment variables and database
setup instructions from their repository README.

## Operating Principles

- Learning should feel earned, not assigned.
- Progression should reflect real work, not inflated numbers.
- Game mechanics should support mastery, not distract from it.
- The product should be welcoming for beginners and still meaningful for
  ambitious builders.
- Data integrity belongs in the platform, not just in the client.

---

<p align="center">
  <strong>Learn by building. Level by finishing. Grow one quest at a time.</strong>
</p>
