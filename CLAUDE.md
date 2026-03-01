# Monikers — Party Card Game PWA

## Overview
PWA implementation of the card game Monikers. Players add custom words, then play 3 rounds:
1. **Describe It** — say anything except the word
2. **One Word** — only one word as a clue
3. **Charades** — act it out, no words

Two teams, timer-based turns, point tracking.

## Tech Stack
- Single HTML file with embedded CSS/JS (no build step)
- Vanilla JS, no frameworks
- PWA with service worker for offline use

## File Structure
- `index.html` — entire app (HTML + CSS + JS)
- `manifest.json` — PWA manifest
- `sw.js` — service worker (cache-first)
- `icon-192.png`, `icon-512.png` — app icons

## Design
- Dark warm palette (#1a1210 bg, cream cards, coral accent)
- Mobile-first, portrait orientation
- Card-swipe animations for Got It / Skip

## Game Flow
Setup (add words) → Ready (team + round info) → Play (timer + cards) → Turn Summary → Ready (next team) → ... → Round Transition → ... → Game Over

## Running
Just open `index.html` in a browser, or serve with any static server.

## Kanban Board
Project card: `C:\Users\emily\projects\board\monikers.md`
