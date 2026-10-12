DREX LIVE UNIVERSE — PROTOTYPE 02

WHAT'S NEW
- More animated portal, glowing headline, and card transitions.
- Locally generated sound effects (no external audio files or paid API).
- Cosmic particle burst button and stronger activation effect.
- Optional front-camera preview bubble inside the webpage. It is mirrored like a selfie and can be dragged around the screen.
- Camera and sound have separate on/off controls.

HOW TO TEST ON ANDROID
1. Host the folder on an HTTPS static host (for example GitHub Pages) and open the HTTPS URL in Chrome.
2. Tap “Sound off” to enable sound effects; browsers require a user tap before audio can play.
3. Tap “Camera off” and grant camera permission. The front-camera selfie preview should appear over the show; drag it to move it.
4. Test all modes and the “Burst” button.
5. Run a short TikTok LIVE screen-share test to verify viewers can see the webpage and camera bubble.

CAMERA NOTES
- Camera access normally requires HTTPS (or localhost); opening the file directly from Downloads may not permit camera access.
- The webpage camera bubble is part of the shared browser screen. It is not TikTok's native camera overlay.
- Android may pause the browser camera when the page is backgrounded, the phone locks, permissions are denied, or TikTok's screen-sharing workflow takes over camera resources. Test this on your device before a public LIVE.
- Camera video is shown locally in the page; this prototype does not upload or record it. Audio is not requested from the camera.

LIMITATIONS
- No TikTok API, live comments, gifts, viewer counts, or automatic audience triggers are connected.
- AI Lab uses prepared demo concepts, not live AI generation.
- Static HTML/CSS/JavaScript; no PHP, MySQL, Node.js, or build tools needed.
