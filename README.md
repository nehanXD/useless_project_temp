<img width="3188" height="1202" alt="frame (3)" src="https://github.com/user-attachments/assets/517ad8e9-ad22-457d-9538-a9e62d137cd7" />


# JACKBEATS 🎯


## Basic Details
### Team Name: JACKBOYS


### Team Members
- Team Lead: Nehan Bahar - SCMS SCHOOL OF ENGINEERING AND TECHNOLOGY
- Member 2: Hadi Konnola - SCMS SCHOOL OF ENGINEERING AND TECHNOLOGY

### Project Description
JACKBEATS is a gloriously useless browser app that turns frantic keyboard mashing into questionable dance beats and reactive neon blobs. Each key triggers a sound; your chaos becomes a loop. Absolutely no musical talent required.

### The Problem (that doesn't exist)
Idle finger-tapping produces nothing but noise and judgmental looks. Your keyboard wants to be a drum machine. Your laptop fan wants a concert.

### The Solution (that nobody asked for)
Map every keystroke to a drum/percussion sample, quantize it to a grid, loop it at a fixed BPM, and splash visuals that pretend it’s art. Export your “masterpiece” just to annoy your friends.

## Technical Details
### Technologies/Components Used
For Software:
- Languages: TypeScript, HTML, CSS
- Frameworks/Build: Vite (dev server + build)
- Libraries: Tone.js (audio), Canvas 2D (visuals), ESLint/Prettier (lint/format)
- Tools: Node.js (>= 18), npm

For Hardware:
- Components: Any keyboard, speakers/headphones
- Specs: Works in modern Chromium/Firefox
- Tools required: None (optional USB MIDI keyboard for extra chaos)

### Repository Structure (technical files)
- index.html — base document and root app container
- src/main.ts — app bootstrap, wiring audio + UI
- src/audio/engine.ts — Tone.js Transport, Sampler, effects chain
- src/audio/mapping.ts — keyboard→sample mapping, quantization
- src/ui/visualizer.ts — analyser node + Canvas renderer
- src/ui/controls.ts — play/stop, BPM, kit selection, record toggle
- styles/main.css — minimal styles
- public/samples/ — kick.wav, snare.wav, hat.wav, perc/*.wav
- public/icons/ — app icon and favicon

### Implementation
For Software:
# Installation
- Prereq: Node.js >= 18
- Commands:
  - npm install
  - npm run dev        (start local dev server)
  - npm run build      (production build)
  - npm run preview    (preview production build)

# Run
- Visit the printed local URL (usually http://localhost:5173)
- Smash your keyboard; press Space to start/stop; use on-screen controls for BPM/kit

### Project Documentation
For Software:

# Screenshots (Add at least 3)
![Home](Add screenshot of landing UI with controls)
*Landing screen with transport, BPM, and kit selector*

![Typing](Add screenshot while typing with highlights)
*Keystroke-to-sample mapping in action*

![Visualizer](Add screenshot of visuals)
*Reactive blobs driven by the audio analyser*

# Diagrams
![Workflow](Add your workflow/architecture diagram here)
*KeyboardEvent → Mapping → Tone.js Sampler → Transport/FX → Output → Analyser → Canvas*

For Hardware:

# Schematic & Circuit
N/A (only your keyboard and speakers)

# Build Photos
![Setup](Add photo)
*Laptop, a keyboard, and regret*

### Project Demo
# Video
[Add your demo video link here]
*A 30–60s run-through: start/stop, BPM change, typing chaos, visuals, optional export*

# Additional Demos
[Add any extra demo links: short social clip, GIF, or beats “album”]

## Team Contributions
- Nehan Bahar: Audio engine (Tone.js), keystroke mapping, quantization, export
- Hadi Konnola: UI/visuals (Canvas), controls, build tooling, project polish

---
Made with ❤️ at TinkerHub Useless Projects 

![Static Badge](https://img.shields.io/badge/TinkerHub-24?color=%23000000&link=https%3A%2F%2Fwww.tinkerhub.org%2F)
![Static Badge](https://img.shields.io/badge/UselessProjects--25-25?link=https%3A%2F%2Fwww.tinkerhub.org%2Fevents%2FQ2Q1TQKX6Q%2FUseless%2520Projects)



