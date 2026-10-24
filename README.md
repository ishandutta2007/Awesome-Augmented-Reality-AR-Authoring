# Awesome-Augmented-Reality-AR-Authoring

# Top Augmented Reality (AR) Authoring Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on WebAR Authoring, Markerless Tracking & Self-Hosted XR Frameworks*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Augmented Reality (AR) Authoring**. These tools enable creators and developers to build AR experiences—placing 3D content in the real world through image tracking, face effects, or surface detection—ranging from no-code visual editors to code-first libraries that run entirely in the browser.

**Examples** include Adobe Aero, 8th Wall, ZapWorks, Unity MARS, Blippar, PTC Vuforia Studio, Spark AR, Lens Studio, Wikitude, and Overly App (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, avoiding per-view SaaS pricing, and controlling the AR pipeline. The open-source landscape shifted dramatically in **February 2026** when **8th Wall**—formerly a paid WebAR platform—went fully open source . The current landscape is anchored by **8th Wall** (MIT-licensed framework with SLAM binary), **MindAR** (pure-JavaScript image and face tracking), **ViroReact** (React Native AR/VR library), and **HERA** (no-code WebXR authoring), with **encantar.js** providing GPU-accelerated image tracking and **LUTE** serving locative game authoring within Unity.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing | Free Tier Limit |
| :--- | :--- | :--- | :--- |
| **[8th Wall (Legacy Hosted Platform)](https://8thwall.org)** | Formerly a paid WebAR platform. **Hosted platform retired February 28, 2026**—now fully open source . | **No longer offered as SaaS**. All paid subscriptions ended; open-source tools and binary are free . | N/A (discontinued as SaaS). See Open-Source section for current offering. |
| **[Adobe Aero](https://www.adobe.com/products/aero.html)** | No-code AR authoring tool for creating interactive experiences with 3D content. | Included with Creative Cloud subscriptions or free Starter plan. | **Free Starter plan** available with core authoring features. |
| **[ZapWorks](https://zap.works/)** | WebAR and native app authoring platform with drag-and-drop designer and scripting. | Quote-based; pricing not published on main site. | **Free trial** available. No permanent free tier. |
| **[Unity MARS](https://unity.com/products/mars)** | AR authoring within Unity with proxy-based workflow for spatial awareness. | Requires Unity Pro subscription (from ~$2,310/year) plus MARS add-on . | No standalone free tier. Trial via Unity. |
| **[PTC Vuforia Studio](https://www.ptc.com/en/products/vuforia/vuforia-studio)** | Enterprise AR authoring for industrial and product visualization. | Quote-based; enterprise-tier. | Trial available via PTC. |
| **[Spark AR (Meta)](https://spark.meta.com/)** | AR effects authoring for Instagram and Facebook. | **Free** to use. | **Fully free** for creating effects for Meta platforms. |
| **[Lens Studio (Snap)](https://lensstudio.snapchat.com/)** | AR lens authoring for Snapchat. | **Free** to use. | **Fully free** for creating lenses for Snapchat. |

## Open-Source GitHub Projects

- **[8th Wall](https://github.com/8thwall/8thwall)** [![GitHub Stars](https://img.shields.io/github/stars/8thwall/8thwall?style=social&color=white)](https://github.com/8thwall/8thwall/stargazers)  
  **The open-source WebAR standard.** MIT-licensed framework and core modules, released after the hosted platform retired in February 2026 . **Components**: XR Engine (Image Targets, Face Effects, Sky Effects), Desktop app (visual editor for 3D/AR), Image Target Processor CLI, and XR Extras . **Critical caveat**: **SLAM is distributed as a binary-only engine**—not open source—under a limited-use license permitting commercial use . The rest of the framework is fully open and community-driven . Best for developers wanting a proven WebAR engine with broad 3D framework integrations (A-Frame, Three.js, Babylon.js, PlayCanvas) without vendor lock-in .

- **[MindAR](https://github.com/hiukim/mind-ar-js)** [![GitHub Stars](https://img.shields.io/github/stars/hiukim/mind-ar-js?style=social&color=white)](https://github.com/hiukim/mind-ar-js/stargazers)  
  **The pure-JavaScript tracking library.** Image tracking and face tracking written end-to-end in JavaScript, using WebGL and Web Workers for performance . **Key advantage**: no native dependencies, no binary components—runs entirely in the browser. **A-Frame integration**: create an image-tracking app in ~10 lines of code . **Companion tools**: MindAR Studio (drag-and-drop face tracking, free to self-host) and Pictarize (hosted image-tracking platform) . **Status**: actively maintained by an individual developer seeking community contributions for computer vision improvements . Best for developers wanting a fully open, dependency-light WebAR library for image and face tracking.

- **[ViroReact](https://github.com/ReactVision/viro)** [![GitHub Stars](https://img.shields.io/github/stars/ReactVision/viro?style=social&color=white)](https://github.com/ReactVision/viro/stargazers)  
  **The React Native AR/VR library.** MIT-licensed, ~1,828 stars, actively maintained (last push September 2026) . Builds AR and VR experiences using React Native and Expo across iOS and Android . Best for mobile developers already in the React Native ecosystem wanting native AR capabilities without writing platform-specific code.

- **[HERA](https://github.com/ChloeArbona/hera)** [![GitHub Stars](https://img.shields.io/github/stars/ChloeArbona/hera?style=social&color=white)](https://github.com/ChloeArbona/hera/stargazers)  
  **The no-code WebXR authoring framework.** Published in IEEE and HAL (2026), HERA is entirely web-based with no installation required . **Components**: Authoring Editor (place and edit 3D assets, images, text in an integrated 3D interface) and XR Viewer (view projects in AR or VR on any WebXR-compatible device) . **New in this version**: multi-user experience sharing—a master user controls a scene while multiple clients view simultaneously via QR code, with bandwidth as the only limit on participant count . Best for educators, curators, and non-technical creators wanting no-code AR/VR authoring with shared presentation capabilities.

- **[encantar.js](https://github.com/alemart/encantar-js)** [![GitHub Stars](https://img.shields.io/github/stars/alemart/encantar-js?style=social&color=white)](https://github.com/alemart/encantar-js/stargazers)  
  **The GPU-accelerated WebAR library.** Works on iOS, Android, and desktops **without requiring WebXR**—uses custom computer vision trackers . **Features**: image tracking (natural feature tracking without manual training), pointer tracking, and compatibility with any 3D engine (A-Frame, Babylon.js, Three.js) . **Licensing**: GPL-3.0 with optional terms for proprietary use. Best for developers wanting high-performance WebAR with broad device compatibility and no WebXR dependency.

- **[LUTE (LoGaCulture Unity Toolkit/Engine)](https://github.com/LoGaCulture/LUTE)** [![GitHub Stars](https://img.shields.io/github/stars/LoGaCulture/LUTE?style=social&color=white)](https://github.com/LoGaCulture/LUTE/stargazers)  
  **The locative game authoring toolkit.** MIT-licensed Unity plugin with a visual flow engine for building mixed reality games tied to real-world locations . **Features**: node-based hypertextual structure for game flow, "Orders" for modular content (3D, video, text, AR), and support for game mechanics like inventories and dialogue . **Research-backed**: developed by Bournemouth University and University of Southampton, used in cultural heritage projects (Avebury Stone Circle) . Best for designers building location-based AR experiences who want a Unity-based visual authoring tool with extensible code access.

### Additional Strong Open-Source Options

- **spARcl (Open AR Cloud)** — Peer-to-peer multi-user AR with GeoPose-based content sharing and CRDT persistence . Best for location-based collaborative AR experiments.
- **AR.js** — Marker-based and location-based AR for the web, often paired with A-Frame. Best for simple marker-tracking experiences.
- **artoolkitX** — Cross-platform marker-tracking SDK with experimental web support via Emscripten . Best for native mobile/desktop AR requiring robust marker tracking.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- **8th Wall's SLAM is not open source**: the framework is MIT-licensed, but SLAM (world tracking) ships as a binary-only engine under a limited-use license. Commercial use is permitted, but the tracking core cannot be inspected or modified .
- **WebXR support varies by device**: HERA and encantar.js have different compatibility profiles—HERA requires WebXR, encantar.js works without it . Verify target device support before committing.
- **Open-source AR authoring is still maturing**: MindAR is maintained by an individual developer seeking community help ; HERA and LUTE are research projects. Evaluate project sustainability alongside features.

---

**Made for AR creators, WebAR developers, and organizations building immersive experiences.**  
Let's make augmented reality authoring more open, accessible, and self-hostable.
