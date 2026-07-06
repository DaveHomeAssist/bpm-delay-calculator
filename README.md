# BPM Delay Calculator

A single-page tool that converts a song's tempo (BPM) into delay times and modulation rates for common note divisions — for audio engineers and music producers dialing in delay/echo effects.

## What it does

Enter a BPM (20–300, via slider or number field) and the page instantly computes, for each note division from whole note down to thirty-second note:

- **Delay time in milliseconds** — what to punch into a delay plugin
- **Rate in Hz** — for LFOs/modulation synced to the same note value
- Toggle between **Normal**, **Dotted** (×1.5), and **Triplet** (×2/3) note values
- A pulsing indicator that blinks at the current quarter-note tempo as a visual reference

The formula (`60,000 ÷ BPM = ms per quarter note`) is shown at the bottom of the page for reference.

## What's here

| Path | What it is |
|---|---|
| `index.html` | The entire app — markup, styles, and calculation logic in one file, no build step or dependencies |
| `favicon.svg` | Site favicon |
| `LICENSE` | All-rights-reserved copyright notice |

## How to view it

This repo's `gh-pages` branch is the live deployment. Open `index.html` directly in a browser, or visit the GitHub Pages URL for this repo.
