# A Few Things I Kept ☕

A tiny interactive birthday memory box for Snigdha.

The idea: there aren't years of memories yet. So instead of pretending there are, the site keeps a few real little moments — the Hinge-to-Instagram origin story, the 7 AM failure, the name corrections, the course-bidding outrage, the South Ex lookalike investigation, the voice-note marathon, the library detour (now with an actual ten-second video), the snake-uncle trauma, the Spider-Man ticket that never became two tickets, and the height audit. 14 in total.

## Run

No build step.

```bash
python3 -m http.server 4173
```

Then open `http://localhost:4173`.

## Notes

The public version deliberately does **not** include private voice recordings or raw WhatsApp exports. Those should only be added if the people in them are comfortable with them being publicly accessible.

One real clip is included: `assets/mussoorie-rain.mp4`, a 10-second selfie video (just Pranav) attached to "The Proof Of Rain." Other candidate clips from the export — the McDonald's lookalike video and a clip that includes a roommate in frame — were left out because they show identifiable people who didn't choose to be in this archive. Swap `assets/mussoorie-rain.mp4` for anything else by dropping a new file in `assets/` and updating the `object.file` path on that memory in `index.html`.
