# Off-Grid Field Guide 📡

A mobile-friendly, interactive beginner guide to **MeshCore** and the community-run **MountainWest Mesh** network. Built for sharing with friends.

## Two ways to use the same guide

**Regular website:** Open https://dallaskirk.github.io/meshcore-field-guide/ in any browser. Share that exact link with friends, including Logan. No account or installation required.

**Installable phone app (PWA):** Open the same URL in **Chrome on Android** or **Safari on iPhone**, rather than an in-app preview browser.
- **Samsung Galaxy / Android:** Tap **Install guide app** inside the guide if offered. Otherwise in Chrome tap **⋮ → Add to Home screen → Install app**. The installed version gets a home-screen icon and opens without browser tabs.
- **iPhone:** In Safari tap **Share → Add to Home Screen**.
- **Desktop:** On compatible browsers, use the browser's install option.

Both modes show the **same content** and receive updates from this repository. The installed app caches core guide pages for offline reading after it has loaded successfully online. External links, online maps, firmware downloads, and product shopping still require connectivity.

If an Android browser says the app cannot be installed, confirm you're using Chrome directly (not a messaging-app browser), reload after the latest GitHub Pages deployment, and try the Chrome menu. This is an installable web app, **not** a Google Play Store APK.

## GPS friend-tracking and Raspberry Pi maker lab (November 19, 2026)

Two new mobile navigation tabs are published in the website and installable PWA:

- **GPS:** Practical comparison of phone + MeshCore companion radio, RAK4631 WisBlock + GNSS, and a self-contained LILYGO T-Deck Plus. Includes the actual GPS → app → radio → mesh → map data path, illustrated last-heard friend map, privacy considerations, old SIM-less iPhones, offline maps, and step-by-step MeshCore TEAM setup.
- **Pi lab:** Why a Raspberry Pi is a controller, not the MeshCore LoRa radio; choosing a Pi Zero 2 W versus Pi 4/5; starter bill of materials; USB serial firmware flashing; soldering practice, LED/button projects, custom PETG cases, a future Pi dashboard and sensor expansions.

**Important:** This website is an educational guide and optional installable PWA. It is not the separate MeshCore TEAM communication/tracking app. See [MeshCore TEAM user guide](https://tmacinc.github.io/MeshCore-TEAM/) for actual off-grid group tracking. TEAM works with stock MeshCore companion firmware for core map/tracking functions; autonomous phone-free position broadcast needs supported radio GNSS and compatible custom firmware. The T-Deck Plus can be standalone for messaging, but on-device maps are firmware dependent. A phone with GPS can still work without a SIM if the app, maps, radio and battery are prepared beforehand.

Sources: [TEAM manual](https://tmacinc.github.io/MeshCore-TEAM/), [MeshCore hardware/firmware FAQ](https://docs.meshcore.io/faq/), [LILYGO T-Deck Plus specs](https://wiki.lilygo.cc/products/t-deck-series/t-deck-plus/), [Raspberry Pi Zero 2 W specs](https://www.raspberrypi.com/products/raspberry-pi-zero-2-w/).

## New visual walkthroughs

The guide now contains an annotated radio-board illustration, an exploded parts diagram, a six-step assembly flowchart, and a visual network-message route. These are conceptual aids, not electrical schematics. Always verify your exact board model and battery polarity with the manufacturer.

## Public website

Once GitHub Pages is enabled (Settings → Pages → Deploy from a branch → main / root), open **https://dallaskirk.github.io/meshcore-field-guide/** on any phone or computer. This static site has no account/login requirement and can be shared with friends.

## Open on a phone and share with friends

After GitHub Pages is enabled, visit **https://dallaskirk.github.io/meshcore-field-guide/** in any phone browser. It is a mobile-friendly public web page with no sign-in needed.

- **Android / Galaxy:** open the site in Chrome, tap the three-dot menu, then **Add to Home screen**.
- **iPhone:** open it in Safari, tap **Share**, then **Add to Home Screen**.
- **Send to a friend:** copy the published site URL from the address bar and share it in Messages or any chat.

The interactive setup checklist saves independently in each person's browser. It does not sync or expose checkmarks to other visitors.

## What's inside

- **Start here:** what the network does and the fastest route to a first message
- **How it works:** LoRa, companion radios, repeaters, private channels, Meshtastic vs. MeshCore
- **What to buy:** beginner devices, community links, and an interactive budget estimator
- **Setup quest:** eight-step beginner checklist with local progress saving and copyable MountainWest settings
- **What you can do:** direct messaging, private channels, optional GPS tracking, festivals, and home repeaters
- **Help:** FAQ, glossary, and primary reference links

## Publish this site on GitHub Pages

1. Sign in to GitHub and create a **new PUBLIC repository** named `meshcore-field-guide` (or another name). Do **not** make your private DK Brain repository public.
2. Upload `index.html`, `README.md`, and `.nojekyll` into the **root** of that new repository. Do not upload the containing folder as a subfolder. If GitHub created an initial README, replace it with this README or upload `index.html` and `.nojekyll` first.
3. Open the new repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**; choose **main**, **/(root)**, and click **Save**.
5. GitHub will display your public website address after deployment. Share that link with friends.

Typical project site URL format: `https://YOUR-USERNAME.github.io/meshcore-field-guide/` (this is a **format example**, not a verified live URL).

Official instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Local preview

Open `index.html` in any modern browser. No installation, bundler, framework, or API key is required. Link buttons open external information sites. Checklist progress is saved to **that browser/device only** using localStorage; it is not uploaded or shared between users.

## Important notes

- This is an **independent** community-learning resource, not an official MountainWest Mesh publication.
- Source settings and products checked **November 18, 2026**. Always verify newer values at https://mwmesh.com/settings.html and availability at the vendor.
- Do not use a mesh network as your only means of communication in an emergency.
- Public/hashtag channels do **not** provide confidential conversation even if messages are cryptographically formatted.
- Location-sharing depends on supported GPS, software, explicit sharing choices, and message delivery.
- MeshCore and Meshtastic require distinct firmware/protocols.

## Sources

- https://mwmesh.com/
- https://mwmesh.com/devices.html
- https://mwmesh.com/flash.html
- https://mwmesh.com/setup.html
- https://mwmesh.com/settings.html
- https://meshcore.io/
- https://docs.meshcore.io/faq/
- https://www.seeedstudio.com/Wio-Tracker-L1-Pro-for-Meshcore-p-6717.html

Built as a self-contained vanilla HTML/CSS/JavaScript page so it can be forked, customized, and hosted for free on GitHub Pages.

## DIY-first update · November 18, 2026

This edition puts **Build** in the navigation and shifts the main recommendation to building a **Heltec WiFi LoRa 32 V3 (US 915 MHz)** with a safe battery setup, antenna, optional 3D-printed case, and MeshCore BLE Companion firmware. It also covers **RAK4631 + RAK19007** modular builds and the optional use of a **Raspberry Pi** to flash/manage supported radios over USB. **A standard Raspberry Pi alone does not have a LoRa transceiver and is not required for basic MeshCore messaging.**

The Gear budget calculator now compares rough DIY Heltec and RAK planning allowances with a ready-made Wio Tracker option. These are estimates, not guaranteed checkout prices. The guide is static HTML, with no tracking scripts, external JS dependencies, or embedded private data.

Useful references:
- [MeshCore official FAQ (including Raspberry Pi over USB)](https://docs.meshcore.io/faq/)
- [Heltec V3 official board specifications](https://heltec.org/project/wifi-lora-32-v3/)
- [MountainWest supported devices](https://mwmesh.com/devices.html)
- [MountainWest flash setup](https://mwmesh.com/flash.html)
- [MountainWest current radio settings](https://mwmesh.com/settings.html)