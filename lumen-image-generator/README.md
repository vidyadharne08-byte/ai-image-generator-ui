# LUMEN — Synthesis Darkroom

A self-contained, single-file AI image generator UI concept.

## Run it
Just open `index.html` in any modern browser — no build step, no dependencies, no server required.

## What it does
- Type a prompt, pick a style, aspect ratio, and number of exposures
- Press "Develop" to watch frames resolve from blur/grain into focus, contact-sheet style
- Each frame is generative abstract art (gradients + noise), deterministically seeded from your prompt + style + seed — same inputs always reproduce the same image
- Download any developed frame as a PNG

## Note
There's no real diffusion/AI model wired in — this is a UI/UX concept with on-device generative art standing in for "exposures." Swap in a real image-generation API call inside the `generateBtn` click handler in `index.html` to make it functional.
