# Off-Grid Field Guide 📡

A mobile-friendly, interactive beginner guide to **MeshCore** and the community-run **MountainWest Mesh** network. Built for sharing with friends.

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