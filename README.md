# motion-toolkit

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-green.svg" alt="MIT license"></a>
  <img src="https://img.shields.io/badge/type-curated%20collection-blue.svg" alt="curated collection">
  <img src="https://img.shields.io/badge/tools-8-orange.svg" alt="8 tools">
</p>

## What this is

The motion and animation skills I use when a project needs to move. Same deal as my other toolkit repos: no code copied here, only links to the originals plus notes on when each one is worth reaching for.

## What's inside

| Tool | What it does | Link | License | My note |
|------|--------------|------|---------|---------|
| animate / animate-expo | Build animations from scratch, web and React Native | bundled with my agent environment | check upstream | Start here when something needs to move and you are deciding how. |
| animation-vocabulary | Turns vague motion descriptions into the right terms | bundled with my agent environment | check upstream | For when you know the feel but not the name. Saves a lot of back and forth. |
| find-animation-opportunities | Audits a UI for places that should animate but don't | bundled with my agent environment | check upstream | Read-only. Good second pair of eyes on a static-feeling page. |
| improve-animations / review-animations | Audit and fix existing motion code | bundled with my agent environment | check upstream | One plans, one reviews. Use before rewriting animation code by hand. |
| gsap-skills | GSAP animation | [greensock/gsap-skills](https://github.com/greensock/gsap-skills) | MIT | The workhorse for web animation. Timelines, scroll triggers, the lot. |
| rive-skills | Rive interactive animation | [BowTiedSwan/rive-skills](https://github.com/BowTiedSwan/rive-skills) | check upstream | For interactive characters and state-driven motion. |
| threejs-skills | Three.js 3D scenes | [CloudAI-X/threejs-skills](https://github.com/CloudAI-X/threejs-skills) | check upstream | When a page needs real 3D, not just parallax. |
| wiggle | Animation utility skill | [talknerdytome-labs/wiggle-claude-skill](https://github.com/talknerdytome-labs/wiggle-claude-skill) | Apache | Handy for quick playful motion. |

## How I use these

Static page that feels dead: find-animation-opportunities first, then animate to build what it suggests. Complex sequences: gsap-skills. A mascot or character that should react: rive-skills. Full 3D scene: threejs-skills. Existing janky motion: improve-animations to plan the fix.

## How to use this list

Pick the tool that matches your problem, follow its link, install it per its own README. Star the ones you keep coming back to.

## Attribution

Every tool here belongs to its original author. Licenses in the table are the upstream licenses as I found them. "Check upstream" means I could not verify the license, so check the source before reusing code. The curation text in this repo (the notes, the structure) is mine, MIT licensed, see LICENSE.
