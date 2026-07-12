# Mind Muncher — interactive concept demo

**Dump it. Sort later.**

A single-page, client-side demo of the Mind Dump concept: feed a stray thought to
the muncher, watch it "sync", and sort it on the mini dashboard below. Everything
runs in your browser — your dumps are stored only in your own `localStorage`;
nothing is sent anywhere.

**Live demo:** *(GitHub Pages URL goes here after deploy)*

## What this is (and isn't)

This page is the **brochure, not the product**. The real Mind Dump system runs
fully local: an Android capture app (Kotlin) and a macOS dashboard (Tauri +
Rust + Vue) sharing one spreadsheet through peer-to-peer file sync (Syncthing) —
no server, no account, no subscription, $0 to operate. The demo simulates that
loop in ~700 lines of dependency-free HTML/CSS/JS.

## Run locally

Open `index.html` in a browser. That's it — no build step, no dependencies.

---

© 2026 Krisna Leo Parista. All rights reserved. This repository is published for
demonstration purposes; no license is granted for reuse of the code or design.
