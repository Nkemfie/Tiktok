# CHAT VS DREX — THE LAST 100 (Prototype 0.1)

A free, mobile-first survival game show prototype built with HTML, CSS and vanilla JavaScript. Designed to be tested in Chrome on an Android phone before attempting TikTok LIVE integration.

## Files
- `index.html` — app screens and controls
- `styles.css` — mobile-first visuals and battlefield effects
- `app.js` — match state, five crises, manual voting, resources, Drex attacks and results

## Run locally on Android
1. Download and extract the ZIP.
2. Open `index.html` in a mobile browser or use a simple static preview/editor app that can serve local HTML files.
3. Tap **Start Survival**.
4. Use **Demo Vote** to test a full vote cycle, or **Open 20-second Vote** and enter your own vote totals.
5. Tap **Close Vote & Resolve**, then choose a Drex attack or **Hold Fire**.
6. Continue through five crises. The match ends with a survivor-based verdict.

Some Android file managers open HTML in a restricted preview. If that happens, upload the files to a new GitHub repository and connect it to Vercel as a static site. No build command or output directory is needed; keep `index.html`, `styles.css`, and `app.js` in the repository root.

## Current rules
- Start: 100 survivors, 60 energy, 50 supplies, 6 threat points.
- Five crisis rounds, each with three community actions.
- Each vote is 20 seconds; for the prototype the host manually enters A/B/C totals.
- If tied, the option with the lower configured resource cost wins; if still tied, A/B/C order is used.
- A no-vote round uses the host's selected option or defaults to B.
- Chat wins with 60 or more survivors at match end.
- Drex has limited threat points and may choose to hold fire.
- Every match resets; no account, backend, database, paid API or TikTok integration is included.

## Important limitations
- This is a playable prototype, not a verified TikTok LIVE overlay. A normal browser page cannot automatically read TikTok comments.
- The top-down battlefield is an illustrative 2D map with animated units, not a full pathfinding simulation.
- The first version is not yet user-tested on the creator's exact Android/TikTok setup.
- The font is requested from Google Fonts; if unavailable, system fallbacks are used.

## Before public use
Play multiple complete matches. Verify resource costs, the vote timer, tie/no-vote rules, threat budget, reset, final result, mobile touch targets and sound mute. Then test a supported broadcast workflow separately.
