# Oblivion Remastered — Codex

A fan-made companion for **The Elder Scrolls IV: Oblivion Remastered**, in two parts:

- **[`index.html`](index.html) — the landing page.** A cinematic hero with a fully interactive **WebGL** backdrop: an orbitable aerial view of the Imperial City rising out of Lake Rumare, the White-Gold Tower glowing at its heart, drifting embers, and an Oblivion Gate burning on the horizon. Drag to orbit, move to parallax, scroll to descend.
- **[`codex.html`](codex.html) — the completionist checklist.** Every guild, the main quest, both DLCs, all fifteen Daedric shrines, side quests, player homes, offerings and collection quests — charted end to end, with per-quest walkthroughs, known bugs, and quest-givers.

**Live:** open [`index.html`](index.html) in any browser, or use the GitHub Pages link.

*Fan work. Not affiliated with Bethesda or ZeniMax.*

## The completionist checklist (`codex.html`)

## Features

- **Two views** — browse *By Location* (each city, guild, and region) or *Optimal Order* (a level-friendly run from the sewers to the finale).
- **Per-quest detail** — click any quest for its objective, a full walkthrough, and known bugs / fixes, plus a direct link to its UESP page.
- **Progress tracking** — check quests off; progress bars fill per section and overall. Everything auto-saves to your browser (`localStorage`).
- **Backup / Load** — export your progress to a JSON file and reload it on any device.
- **No accounts, no server, no tracking** — one HTML file, works fully offline.

## Notes

- Lists cross-checked against UESP, Game8, and the Oblivion Remastered wiki.
- Some Daedric shrines and side quests carry level minimums — badges flag these.
- The optimal order flags points of no return (e.g. the Dark Brotherhood *Purification*) so you finish earlier content first.

## Local use

No build step. Clone and open the file:

```bash
git clone https://github.com/LKocaj/oblivion-completionist-codex.git
cd oblivion-completionist-codex
open index.html      # macOS  (or just double-click it)
```

Fonts (Cinzel + EB Garamond) load from Google Fonts when online, with serif fallbacks offline.

---

Progress is stored locally in your browser and never uploaded.
