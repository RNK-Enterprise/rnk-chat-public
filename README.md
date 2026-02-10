RNK™ Chat Window
RNK Chat is an advanced, system-agnostic chat window module for Foundry VTT that provides:

Resizable, draggable chat window
Advanced filtering and message type toggles
Multiple themes and per-user zoom controls
Auto-pruning of old messages and configurable max message retention
Installation

Option 1 — Foundry Package Manifest:

Add the following manifest URL to Foundry's module management: https://r2.foundryvtt.com/packages-public/rnk-chat/module.json
Install and enable the module, then configure settings in the Module Settings panel.
Option 2 — Manual install:

Download the latest release ZIP and extract into your Foundry Data/modules/rnk-chat directory.
Restart Foundry, enable the module, and configure settings.
Usage

Open the RNK Chat window from the Modules UI or by using the configured hotkey. The window is resizable and remembers position and size per client.
Use the header controls to select themes, zoom, and toggle filters.
Settings exposed in Foundry:
defaultWidth / defaultHeight — default window size
inactiveOpacity — opacity when not focused
zoomLevel — default message zoom
maxMessages — maximum stored messages
theme — selected theme
Development

Run tests: npm run test
Linting: npm run lint
Build & packaging helper: scripts/package-release.ps1
Manifest validator: node scripts/validate-manifest.js
Releases & Changelog See RELEASE.md for release notes and the GitHub Releases page for downloadable assets.

Compatibility Foundry VTT compatibility: 11–13 (verified on 12).

License MIT — see LICENSE.

My Story

I am a Game Master (GM) who has always been passionate about tabletop role-playing games. My journey into development began unexpectedly after a career as a truck driver came to an end due to health challenges. In 2021, I suffered several strokes that forced me off the road, leaving me with limited mobility and energy for outings that would otherwise exhaust me for days.

What started as simple curiosity about what a macro could do in Foundry Virtual Tabletop quickly evolved into a full-fledged passion for development. My first major creation was a 3D animated cube with 41 lines of code, which became the foundation of the RNK brand. As a self-taught developer working from my garage, I approach every project with meticulous research and innovative thinking. I refuse to settle for anything less than excellence, pushing myself to create modules that not only function flawlessly but also enhance the gaming experience for fellow GMs and players.

This work keeps me engaged and my mind active during a time when physical limitations restrict my activities. I am engaged to the love of my life, Ms. Lisa, and without her unwavering support, I wouldn't be able to bring anything that I do to the community. It is with her support and encouragement that I have excelled to become what I am today.

I will continue creating and innovating until boredom sets in or health prevents it—whatever comes first. Eventually, I will be looking for someone to take over these modules, someone with the drive and tenacity that I wake up with every day. In the meantime, I am open to collaborations if the project peaks my interest. My modules are born from this dedication, crafted with the same care and precision that defined my driving career, now channeled into the digital realm of virtual tabletop gaming.

Thank you for supporting my creations and sharing in this journey.

For collaborations or inquiries:
Email: Asgardinnovations@protonmail.com
Discord: Odinn1982
Location: Eastern US

As always, love and respect from the RNK Enterprise, Odinn

For issues or feature requests, open an issue on GitHub: https://github.com/RNK-Enterprise/rnk-chat/issues
