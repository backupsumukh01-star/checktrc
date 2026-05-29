checktrc.in — Offline mirror
============================

Downloaded: 43 files (~9 MB) from https://checktrc.in/

Contents
--------
- index.html, favicon, logos, manifest, robots.txt, asset-manifest.json
- static/css/main.594df6ad.css
- static/js/main.33073878.js + 19 lazy-loaded chunk files
- static/media/ — 15 PNG images

View locally
------------
From this folder, run:

  python3 -m http.server 8080

Then open: http://localhost:8080/

(Use a local server — opening index.html directly as file:// may break JS chunk loading.)

Not included (external / live-only)
-----------------------------------
- Backend API: https://trcnis.tapfaucet.org
- Telegram endpoint: https://tapfaucet.org/sendTelegram.php
- Third-party services (TronGrid, WalletConnect, Thirdweb, etc.) bundled in JS

Wallet "Check" and email subscribe need the live API; the landing page UI works offline.
