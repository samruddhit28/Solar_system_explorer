# Solar_system_explorer
An interactive, 3D‑styled Solar System interface built with pure HTML and CSS. It features a left-side planet selector, animated planet textures, orbit trajectories, and labeled moons, all powered by CSS transforms, transitions, and keyframes — no JavaScript required.

Features
Pure CSS 3D feel using perspective, translateZ, and rotateX for depth and layering.

Click-to-focus planet navigation via radio inputs and labels acting as a control panel.

Animated planet “spin” effect with background-position keyframes for subtle motion.

Moon previews and dashed orbit trajectories for major moons of Earth, Mars, Jupiter, Saturn, Uranus, and Neptune.

Responsive overlay and panel layout with a clean, minimalist typography (Montserrat).

Tech stack
HTML5 for structure and content.

CSS3 for layout, animation, and interactivity (transforms, transitions, keyframes).

No JavaScript dependencies.

Getting started
Clone the repo.

Open solar.html in any modern browser.

Use the left menu to pick a planet; the scene focuses and reveals its description, moons, and orbits.

Project structure
solar.html — Page markup, planet descriptions, and control inputs/labels.

solar.css — Core styles: 3D scene, animations, planet/ moon skins, orbits, panel UI.

Notes and limitations
External textures are loaded from third‑party URLs; an active internet connection is required to see planet and moon textures.

All interactivity is driven by CSS state selectors tied to radio inputs.

Some vendor-prefixed properties are included for broader browser support.

Credits
This project references publicly available texture images from NASA/JPL and community sources (e.g., Solar System Scope, DeviantArt assets, and image archives) as linked in the CSS background URLs within solar.css. Replace or self‑host textures as needed to meet licensing or offline requirements.

