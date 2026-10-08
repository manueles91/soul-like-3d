# Soul-like 3D: an Undertale-inspired feasibility demo

**Play:** https://manueles91.github.io/soul-like-3d/ (works on phones: tap to start, virtual stick + A/B buttons; keyboard on desktop)

A small, single-file browser prototype that asks one question: *what would it feel like to take a 2D bullet-hell RPG like Undertale into 3D, and is it worth it?*

- 3D overworld with a typewriter dialogue box, a sign, an NPC and a save-point sparkle
- An encounter with a FIGHT / ACT / ITEM / MERCY menu, a calm meter and sparing
- The experiment: the dodge phase in two switchable modes
  - **2D box in a 3D world** (the classic flat box rendered in a 3D scene)
  - **True 3D arena** (free movement, jumping, shots from every direction)
- A design-notes panel listing what the demo is meant to surface

## Fan project notice

This is an **original, non-commercial fan feasibility demo inspired by Undertale**. It contains **no Undertale assets**: no sprites, music, text, characters or names from the game. All art is simple original geometry, and all characters and writing are original. Undertale is the work of Toby Fox; this project is not affiliated with or endorsed by its creator.

## Tech

One self-contained `index.html` (three.js r149, MIT, inlined). No build step, no network requests, works offline.
