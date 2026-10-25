# Hyperframes Composition Brief: Campus Creator AI

## Objective
Create a 25-second launch-style video showing the current event-copy prototype and teasing the user's proposed next build: visual poster generation plus Google Forms registration.

## Output
- Composition directory: `brag-output-2026-10-25-202557/composition/`
- Rendered video: `brag-output-2026-10-25-202557/brag.mp4`
- Format: landscape — 1920x1080
- Duration: 25 seconds

## Source Material
- Project root: `D:\Coding material\Projects\hackthon\Campus-Creator-ai`
- Primary files: `src/App.tsx`, `src/components/LiveDemo.tsx`, `src/components/DocumentView.tsx`, `src/index.css`
- Product name: Campus Creator AI
- Current capability: Gemini generates poster copy, Instagram caption, WhatsApp text, email draft, LinkedIn post, and taglines from event details and a style profile.
- Current UI moment: Style Profile + Event Details forms, Generate Promotional Kit action, and result cards.
- User-requested future concepts: generate a visual poster and create a registration form through Google Forms.
- Required distinction: poster generation and Google Forms registration are roadmap concepts, not implemented features. Label them “NEXT BUILD,” “Concept preview,” or “Planned flow” within those scenes. Do not invent a live form URL.
- Fictional event stand-in for the video: Tech for Good Night — Nov 12, 2026, 5 PM, Student Center, all students.

## Creative Direction
- Tone: app-store; polished campus-tech product demo with an honest roadmap tease.
- Angle: show current copy generation first, then make the requested poster and registration features feel like the next natural step.
- Hook: “One event. A whole launch kit.”
- Outro: “Copy now. Poster + signup next.”
- Avoid implying the poster generator, Google Forms integration, engagement prediction, or saved style memory are already available.

## Visual Identity
- Background: zinc-50 `#fafafa`
- Text: zinc-900 `#18181b`
- Accent: indigo `#4338ca`
- Fonts: system sans-serif
- References: current white rounded cards, light zinc canvas, indigo selections, and two-column prototype layout.

## Storyboard
Use `brag-plan.md` as the creative contract.
1. One event — 3s — hook and event brief.
2. Set the club voice — 3s — current Style Profile.
3. Ask for the event — 4s — current event details fields and Generate action.
4. Copy for every channel — 4.5s — current generated copy kit.
5. Poster generation, next — 4s — clearly labeled poster concept.
6. Google Forms registration, next — 3.5s — clearly labeled registration concept.
7. Copy now. Poster + signup next. — 3s — close.
Total: 25 seconds.

## Audio
- Music: `assets/music/happy-beats-business-moves-vol-9-by-ende-dot-app.mp3`
- Volume: 0.32; fast fade-in, 1-second fade-out.
- Cue metadata: `assets/music/happy-beats-business-moves-vol-9-by-ende-dot-app.music-cues.json` (114.84 BPM); use cues near 10.54s for generated copy and 14.76s for poster reveal.
- SFX: soft click on Generate and light reveal accents for copy/poster.
- Audio-reactive extraction unavailable because the `media-use` extraction skill could not be installed in this environment. Use authored beat-timed motion instead.

## Hyperframes Notes
The current event-copy interface should read as the implemented product. Poster artwork and Google Forms UI are intentionally static concept mockups, labeled as planned work. Run `npx hyperframes check`, inspect key frames, render locally to `brag.mp4`, extract a settled poster frame, and bake the poster into frame 0.

