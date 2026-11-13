# VELOCITY X — Web Racing Prototype

A small, static browser racing game project designed for Vercel. The cars, tracks, trackside scenery and showroom are generated in code; no large model or image packs are included.

## Deploy to Vercel
1. Extract `velocity-x-web.zip`.
2. Open https://vercel.com/new or https://vercel.com/drop in your browser.
3. Upload the extracted `velocity-x-web` folder (the folder containing `index.html`).
4. Use the default static deployment settings. No build command is required.
5. Open the generated HTTPS deployment URL.

## Controls
- Android: use the on-screen left/right, GAS, BRAKE and N2O controls. Landscape is recommended.
- Desktop: WASD or arrow keys to steer/accelerate/brake; Space brakes; Shift uses nitro; P or Escape pauses.

## Included
- Three original procedural circuit layouts.
- Five selectable cars with different handling statistics and paint choices.
- Third-person racing camera.
- Player acceleration, braking, steering, basic off-track slowing and speed response.
- Seven AI rivals following the circuit at different paces.
- Lap and finish logic, race timing, position display and results/rewards.
- Touch and keyboard input.
- Local browser saves for driver name, settings, credits, wins, races and best lap.
- First-run driver-name setup, editable player profile, and driver name on the home screen, race HUD, career record and race results.
- Driver names are validated and saved locally in the current browser on the current device.
- Low/Medium/High quality setting.
- Procedurally created engine tone and UI beeps.

## Player profile note
- Player names and career progress currently use browser LocalStorage. They do not automatically sync to another phone or browser. Account-based cloud saves and online multiplayer identity require a secure backend.

## Important limitations
- Three.js is loaded from jsDelivr, so the first visit needs an internet connection. Browser caching can reduce repeat downloads.
- This is a polished playable prototype, not a commercial-grade simulation. Vehicle dynamics are arcade-style; AI rivals follow programmed racing paths and do not yet perform sophisticated strategic overtakes or collision avoidance.
- The visual models are original procedural geometry, not high-polygon imported supercar assets. Dynamic lighting and environmental geometry are optimized for browser performance.
- The 3D game has been syntax-checked and its project structure validated. Actual performance can vary by phone, browser and thermal conditions; test on the target device before sharing publicly.
- LocalStorage progress is stored in that browser on that device and is not synced across devices.
