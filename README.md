# 🎋 Tanabata: One Night a Year

A tiny, cozy browser game retelling the legend of the Tanabata festival — the one night each year, on the seventh day of the seventh month, when the weaver princess Orihime (the star Vega) and the cowherd Hikoboshi (the star Altair) may cross the Heavenly River to be together.

No installs, no dependencies, no build step. One HTML file, one starry night.

## ▶️ Play

Works with mouse or touch, on desktop and mobile. Turn your sound on 🔊 (there's a mute button if you'd rather play in silence).

## 🌌 The Story, in Three Acts

**Act I — The Weaving.** Before she may cross, Orihime must keep her promise at the loom. Tap the colored threads in the order of the pattern to weave three rows of heavenly cloth.

**Act II — The Magpie Bridge.** The Heavenly River has no bridge, but the magpies offer their wings. Tap the magpies to gather them into formation — and shoo away the grumpy rain clouds before they startle the flock.

**Act III — The Crossing.** Guide Orihime across the bridge of wings. Hop (tap the button or press Space) when the light passes through the golden band. Miss, and she wobbles — but on this night, she never falls.

When the lovers reunite, write your own wish on a **tanzaku** and hang it on the bamboo, as people across Japan do every July 7th.

## ✨ Features

- Hand-drawn canvas night sky: twinkling stars, a glittering Milky Way, and Vega and Altair glowing on opposite banks
- All sound synthesized live with the Web Audio API — koto-style plucks tuned to the *hirajoshi* pentatonic scale, bird chirps, rain plinks, and a soft generative "star chime" ambience (no audio files)
- Gentle by design: mistakes shake or plink, but nothing punishes you — this is a festival, not a boss fight
- Touch-friendly, responsive layout, and respects `prefers-reduced-motion`

## 🛠 Tech Notes

- Single self-contained `index.html` (~40 KB): vanilla JavaScript, Canvas 2D, CSS, and Web Audio
- No frameworks, no assets, no network calls (fonts are the one optional external — the game falls back gracefully without them)
- Audio starts after your first tap, as browsers require a user gesture

## 📖 The Legend

Orihime, daughter of the Sky King, wove beautiful cloth by the banks of the Amanogawa — the Milky Way. When she and the cowherd Hikoboshi fell in love, they neglected all their duties, and the Sky King separated them across the river in anger. Moved by his daughter's tears, he allowed them to reunite one night a year, so long as they worked diligently — and on that night, a flock of magpies forms a bridge with their wings so Orihime can cross. If it rains, the magpies cannot come, and the lovers must wait another year.

May the skies be clear for you. Happy Tanabata ✦
