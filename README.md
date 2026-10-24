# Awesome-Augmented-Reality-AR-Authoring

## Top Augmented Reality (AR) Authoring Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on WebAR Authoring, Markerless Tracking & Self-Hosted XR Frameworks*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Augmented Reality (AR) Authoring**. These tools enable creators and developers to build AR experiences—placing 3D content in the real world through image tracking, face effects, or surface detection—ranging from no-code visual editors to code-first libraries that run entirely in the browser.



**Examples** include Adobe Aero, 8th Wall, ZapWorks, Unity MARS, Blippar, PTC Vuforia Studio, Spark AR, Lens Studio, Wikitude, and Overly App (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, avoiding per-view SaaS pricing, and controlling the AR pipeline. The open-source landscape shifted dramatically in **February 2026** when **8th Wall**—formerly a paid WebAR platform—went fully open source . The current landscape is anchored by **8th Wall** (MIT-licensed framework with SLAM binary), **MindAR** (pure-JavaScript image and face tracking), **ViroReact** (React Native AR/VR library), and **HERA** (no-code WebXR authoring), with **encantar.js** providing GPU-accelerated image tracking and **LUTE** serving locative game authoring within Unity.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## Sector Overview & Market Dynamics

The global Augmented Reality (AR) software and authoring tools market is estimated at roughly $120–$170 billion across broader AR/XR sectors, with dedicated creation software expanding at a CAGR exceeding 30–40%. While underlying spatial operating systems and hardware runtimes are tightly concentrated among big tech oligopolies (Apple, Google, Meta), the AR authoring tool and SaaS layer remains **moderately fragmented**, populated by specialized enterprise CAD/IoT solution vendors, no-code WebAR marketing suites, and real-time 3D engine ecosystems competing across distinct vertical niches.


## SaaS/Hosted Platforms



| Product | Company Size (Market Cap / Valuation / Revenue) | Description | Pricing | Free Tier Limit |
| :--- | :--- | :--- | :--- | :--- |
| **[Spark AR (Meta)](https://spark.meta.com/)** | **~$1.65 Trillion Market Cap** (Meta Platforms, Inc., FY25 Revenue ~$160B+) | AR effects authoring for Instagram and Facebook. *(Note: Discontinued January 14, 2025; third-party publishing sunset)*. | **Free** to use. | **Fully free** (Unlimited non-commercial creation; third-party distribution closed January 2025). |
| **[Adobe Aero](https://www.adobe.com/products/aero.html)** | **~$105 Billion Market Cap** (Adobe Inc., FY25 Revenue ~$21.4B) | Visual no-code AR authoring tool for creating and viewing interactive AR experiences across iOS, macOS, and Windows. | **Free** standalone desktop/mobile app (Paid Creative Cloud All Apps plans start at **$54.99/mo**). | **Free plan** included with free Adobe ID; limited to **2 GB cloud asset storage**. |
| **[PTC Vuforia Studio](https://www.ptc.com/en/products/vuforia/vuforia-studio)** | **~$22.6 Billion Market Cap** (PTC Inc., FY25 Revenue ~$2.74B) | Enterprise AR authoring suite integrating industrial 3D CAD and live ThingWorx IoT telemetry for frontline worker workflows. | Custom quote-based enterprise licensing (typically estimated around **$2,000–$4,000/creator/year**). | **30-day free trial** with access to local authoring and Experience Service publishing; local authoring remains post-trial but hosting/sharing expires. |
| **[Unity MARS](https://unity.com/products/mars)** | **~$18.5 Billion Market Cap** (Unity Software Inc., FY25 Revenue ~$1.85B) | AR authoring extension within Unity with proxy-based workflow for spatial simulation. *(Deprecated in Unity 6.1; support ended Unity 6.3 in favor of AR Foundation)*. | Bundled with Unity Pro (**$210/month** or **$2,310/year**; MARS standalone historically $50/mo). | **45-day free trial** of MARS (Unity Personal has no permanent free MARS license; trial grants 45 days full feature access). |
| **[Lens Studio (Snap)](https://lensstudio.snapchat.com/)** | **~$10.7 Billion Market Cap** (Snap Inc., FY25 Revenue ~$5.3B) | Professional AR lens creation suite for Snapchat, Spectacles, and web distribution via Camera Kit. | **Free** to download and use. | **Fully free** (Unlimited AR lens authoring and testing; Camera Kit web SDK includes free monthly active user tiers). |
| **[8th Wall (Legacy Hosted Platform)](https://8thwall.org)** | **~$3.5 Billion Parent Valuation** (Acquired by Niantic; platform retired post-2025 spin-off) | Historically the benchmark commercial WebAR SaaS hosting platform. Hosted service retired February 28, 2026. | **Discontinued as paid SaaS** (Core engine open-sourced under MIT with SLAM binary). | Discontinued as paid SaaS; open-source engine is free to self-host without fees. |
| **[Blippar (Blippbuilder)](https://blippbuilder.blippar.com)** | **~$25M–$50M Valuation** (Post-restructuring; estimated ~$6M–$8M ARR; raised $130M+ historically) | No-code drag-and-drop WebAR creation tool and developer WebAR SDK for browser-based image, surface, and face tracking. | Starts at **£7.99/month (~$10/mo)** for Creative Plan; Pro at £39/month. | **Free Starter plan** with unlimited drafting and testing in editor; public live publishing requires paid plan or 1-month WebAR SDK trial (100 views). |
| **[ZapWorks](https://zap.works/)** | **~$3.75M Total Funding** (Zappar Ltd.; estimated ~$5M–$15M annual revenue) | Complete WebAR and native XR creation ecosystem featuring Designer (no-code), Mattercraft, and Universal AR SDKs. | Starts at **$12.99/month** (or $64.99/year) for Developer tier; Pro commercial plan at **$315/month**. | **14-day free trial** with full feature access for evaluation; trial projects unpublish after 14 days without a paid plan. |
| **[MyWebAR](https://mywebar.com)** | **~$3M Venture Funding** (DEVAR Entertainment; estimated ~$4.2M–$10M ARR) | Browser-based visual no-code WebAR authoring tool for surface tracking, QR targets, and face filters. | Starts at **$39/month** ($25/mo billed annually) for Pro tier with commercial rights. | **Free Creator plan forever** limited to **500 views/year**, **5 active projects**, **100 MB cloud storage**, non-commercial use, and platform watermark. |
| **[echo3D](https://www.echo3d.com/)** | **~$25M–$50M Valuation** ($10.6M total funding backed by Qualcomm Ventures; ~$1M–$2M ARR) | Cloud 3D digital asset management (DAM) and backend CMS platform for WebAR and 3D cross-platform streaming. | Starts at **$99/month** for Pro tier (includes 100 credits/mo, advanced compression, team sharing). | **Free plan forever** limited to **10 credits/month** (100 API calls, 1 GB storage, 250 MB bandwidth) and max **25 MB** per 3D file. |
| **[Onirix](https://www.onirix.com)** | **~$1.9M ARR** (Acquired March 2026 by INVELON; raised €700K seed) | Web-based AR scene creator and spatial computing platform offering marker, surface, and image tracking. | Starts at **€45/month (~$49/mo)** billed annually (or €90/month billed monthly) for Starter tier. | **Free plan** limited to **200 AR views/month**, **up to 5 projects**, max 5 scenes per project, and mandatory Onirix watermark. |
| **[Overly App](https://overlyapp.com/)** | **Bootstrapped / Indie SaaS** (Estimated <$1M ARR) | Self-service no-code WebAR builder and marker tracking platform for interactive print and 3D product visualizations. | Starts at **€19.99/month (~$22/mo)** per experience (or €11.99/mo per experience billed annually). | **Free trial** to build and preview AR experiences on mobile; Shopify integration tier offers **2 experiences and 50 views/month**.



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
