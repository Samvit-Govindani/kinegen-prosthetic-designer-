# kinegen-prosthetic-designer-
Interactive 3D C-curve prosthetic foot designer with toy gait animation and stress visualization (Three.js + GSAP, single HTML).
# KineGen — Dynamic Prosthetic Foot Designer

Interactive 3D designer that visualizes a C-shaped energy-storing prosthetic foot.
Tweak **C-curve height**, **heel stiffness**, **toe-off length**, and **material** to see
a toy **gait cycle** and a colorized **stress map**. Metrics shown (energy return, peak
stress, weight, symmetry) are illustrative only.

**Tech:** Three.js (r128), GSAP, Tailwind — no build step (CDNs).  
**Use:** Educational / demo; **not** an engineering analysis tool.

---

## Features
- Real-time geometry rebuild as you change parameters.
- Heel-strike → mid-stance → toe-off animation with stress heat map.
- Lightweight “FEA-like” vertex color field (HSL blue→red).
- Toy performance metrics for quick what-if feedback.
- Single HTML file; deployable to GitHub Pages.

---

## Quick start
Open `index.html` in a modern browser (Chrome/Edge/Firefox).  
If your browser blocks local scripts, run a tiny server:

```bash
python -m http.server
# then open http://localhost:8000
