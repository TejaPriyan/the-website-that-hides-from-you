# The Website That Hides From You (WTHFY)

> *“Hello. There’s nothing here.”*  
> An elusive, sentient interactive web art piece by **Teja Priyan**.

[![Live Demo: Vercel](https://img.shields.io/badge/Live%20Demo-Vercel-black?logo=vercel&logoColor=white)](https://websitethathidesfromyou.vercel.app)
[![GitHub Repository](https://img.shields.io/badge/GitHub-Repository-181717?logo=github&logoColor=white)](https://github.com/TejaPriyan/the-website-that-hides-from-you)
[![License: All Rights Reserved](https://img.shields.io/badge/License-All%20Rights%20Reserved-red.svg)](./LICENSE)
[![Zero Dependencies](https://img.shields.io/badge/Dependencies-0%20(Pure%20Vanilla)-success.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Web Audio API](https://img.shields.io/badge/Audio-Procedural%20Web%20Audio-blue.svg)](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)

---

## ✦ Quick Links
* 🌐 **Live Website**: [websitethathidesfromyou.vercel.app](https://websitethathidesfromyou.vercel.app)
* 📦 **GitHub Repository**: [github.com/TejaPriyan/the-website-that-hides-from-you](https://github.com/TejaPriyan/the-website-that-hides-from-you)

---

## ✦ Overview

**The Website That Hides From You** is a minimalist interactive browser game, psychological puzzle, and creative coding experiment. 

Disguised as a quiet, editorial landing page set in classic Georgia serif typography and stark parchment tones, the website conceals a living, reactive personality. When your cursor approaches interactive elements, the website calculates real-time evasion vectors, slips along screen borders, fakes its death, splits into decoys, and reacts dynamically to your cursor speed and habits.

Can you earn its trust, solve its acoustic riddles, and discover all **8 narrative endings** and **20 hidden secrets**?

---

## ✦ Key Features & Mechanics

### 1. Vector Evasion Physics & Behavioral AI
* **Dynamic Mood State Machine**: The website transitions between 7 emotional states (`calm`, `nervous`, `playful`, `scared`, `defiant`, `curious`, `trust`) based on cursor velocity, approach trajectory, and player gentleness.
* **Repulsion Physics**: Letters in the `HELLO.` hero header physically scatter and spring back under cursor proximity.
* **Predictive Escape Math**: Buttons calculate escape coordinates away from your heading vector, learn whether you attack from the left or right, and deploy decoys or counter-maneuvers when cornered.

### 2. Procedural Spatial Web Audio
* Zero external audio files or mp3 assets. Every sound effect—radar hums, sonar pings, escape glides, and musical chimes—is synthesized procedurally in real time using the native browser **Web Audio API** and stereo panners.

### 3. The Memories & Secrets Codex (`MEMORIES`)
* A built-in, minimalist parchment ledger tracking all:
  * **8 Narrative Endings** (Endings `A` through `G`, plus Escape `X`).
  * **20 Discoverable Secrets** (with enigmatic, poetic hints for undiscovered items).

### 4. "Blindfold" Echolocation Mode
* Type `BLIND` or `LISTEN` on your keyboard to shroud the screen in darkness. Locate the hidden resonance source purely using stereo audio pings and frequency pitch cues.

### 5. The Ink Crumb Lure
* Click and hold still on empty space for 0.75 seconds to drop a pulsing ink droplet. Back your cursor away, and watch shy buttons creep out of hiding to investigate.

### 6. The Watchful Eye ("Red Light, Green Light")
* The period in `HELLO.` occasionally morphs into an eye (`HELLO◉`). Stand completely still while it watches—any sudden cursor movement triggers instant retreat!

### 7. Multi-Tab Hide-and-Seek (`BroadcastChannel`)
* Open the website in two tabs simultaneously. The button in Tab 1 slips into Tab 2, communicating across browser windows using the native `BroadcastChannel` API.

### 8. The Backside Dimension
* Find the secret asterisk mark `*` to slip behind the curtain into a dark, tilted 3D realm where the website flips the script—and a button hunts **your** cursor.

### 9. DevTools Detective
* Curious developers who open the console (`F12`) are greeted with special inspectable commands: `reveal()`, `apologize()`, and `hint()`.

---

## ✦ Keyboard Commands

Type these words anywhere on the page at any time:

| Word | Action / Effect |
| :--- | :--- |
| `PLEASE` | The magic polite word. Buttons surrender their stamina. |
| `SORRY` | Calms the website when it becomes frantic or frightened. |
| `HELLO` | Greets the website back and softens its guard. |
| `WHO` | Inquires about authorship (*“CODE & CONCEPT BY TEJA PRIYAN”*). |
| `WHY` | Questions its purpose (*“BECAUSE YOU WOULDN'T STAY IF IT WERE EASY”*). |
| `DANCE` | Conducts all active buttons in a playful circular waltz. |
| `BLIND` / `LISTEN` | Activates acoustic echolocation mode. |
| `LIGHT` / `DARK` | Smoothly switches between parchment light and midnight dark themes. |
| `HINT` / `CLUE` | Whispers a cryptic clue for an undiscovered secret. |
| `Escape` | Exits panels, blindfold mode, or triggers the Departure ending. |


---

## ✦ Author & Credits

* **Concept, Design & Development**: **Teja Priyan**
* **Live Website**: [websitethathidesfromyou.vercel.app](https://websitethathidesfromyou.vercel.app)
* **GitHub Profile**: [@TejaPriyan](https://github.com/TejaPriyan)
* **Project**: The Website That Hides From You (WTHFY)

---

## ✦ License & Intellectual Property

**Copyright © 2026 Teja Priyan. All Rights Reserved.**

This work, including its source code, design aesthetic, audio algorithms, and concept, is proprietary. 
* Personal viewing and interactive play in a browser is warmly welcomed.
* **No copying, cloning, modification, republishing, commercial use, or derivative distribution** is permitted without prior written consent from Teja Priyan. See [LICENSE](./LICENSE) for complete terms.
