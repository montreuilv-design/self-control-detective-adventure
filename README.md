# Self-Control Detective Adventure

React + TypeScript + Motion + Vite. Original animated SVG characters and school-map illustrations. Designed for a landscape smartboard or desktop, preferably 1280×800 or larger.

## Status — verification blocked

All six destination activities are implemented in source. This is an **unverified source delivery**, not a completed or tested deployment.

Dependency installation could not finish because the environment proxy is unavailable. A connection check to https://registry.npmjs.org/react failed with:

`curl: (7) Failed to connect to proxy port 8080 ... Could not connect to server`

`npm run build` consequently failed with `sh: 1: tsc: not found`.

The preview infrastructure also failed: `sites-preview status` returned `preview relay unavailable: No such file or directory (os error 2)`. No supported browser-control tool was available. No browser playthrough or visual/layout QA has been completed. No working preview URL or published site is available from this session.

## Run locally

Install Node.js 20.19+ or 22+ and run in this folder:

```sh
npm install
npm run dev
```

Open the Local URL printed by Vite, usually http://localhost:5173. This is a URL on your own computer, not a preview currently running in the cloud session.

## Play

Open the briefcase, choose any school destination, and inspect all three scene clues. Practice three paced breaths, then solve the destination's challenge. Incorrect choices offer feedback and retries. Completed cases earn badges saved in this browser. Use the book icon for the grown-up guide, the full-screen icon for classroom play, and Read to me for browser speech narration. Speech availability depends on browser and operating-system voices.

- Classroom: investigate an accidental tower fall, choose helpful words, build wide-to-narrow.
- Cafeteria: use numbered arrival tickets to restore the lunch queue.
- Playground: make a fair turn plan and wait for the practice sand timer.
- Bus: remain seated until stopped, then request driver assistance.
- Hallway: navigate adjacent tiles around a spill and notify an adult.
- Library: choose a whisper level before sharing a dinosaur discovery.

## Build and publish online

```sh
npm run build
npm run preview
```

After a successful build and the checks below, deploy the generated `dist` directory to any static web host:

1. For Netlify: upload `dist` through its manual deploy interface. For a connected Git repository, use build command `npm run build` and publish directory `dist`.
2. For Cloudflare Pages: connect the repository, use `npm run build`, and set output directory to `dist`.
3. For another static host: upload the contents of `dist` with its `index.html` at the website root.

No backend, API key, account system, or external assets are required by the game. The local progress data is specific to the browser and site origin.

## Required verification before classroom use

Run `npm run build`. Play every case through both an incorrect choice and successful completion. Check clue gating, all three breaths, timer waiting, all hallway paths, completion badge persistence after refresh, replay, reset cancellation and confirmation, narration, and full screen. Check at 1280×800 and 1920×1080 for clipping, overlapping clues, and panel scrolling. Keyboard-check all controls. These checks remain outstanding in this delivery.
