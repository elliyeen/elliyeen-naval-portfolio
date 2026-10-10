# Elliyeen — Naval Engineering Portfolio

**Bring us the problem. We'll engineer the outcome.**

A minimalist, interactive portfolio presenting public AI engineering and cybersecurity projects, designed for a 10-second first impression and deeper technical review.

## Live website
After enabling GitHub Pages: https://elliyeen.github.io/elliyeen-naval-portfolio/

## Features
- Interactive surface-ship and submarine views, with keyboard arrow-key navigation
- Responsive Apple-inspired dark interface
- Links to public CAC/PIV/PKI and AI career agent repositories
- Accessible navigation, reduced-motion support, and no external runtime dependencies
- Static deployment via GitHub Pages

## Tech stack
HTML5, CSS3, vanilla JavaScript, inline SVG, GitHub Pages.

## Architecture and trade-offs
This project deliberately avoids a large frontend framework or 3D engine. Static HTML and SVG are fast, easy to maintain, and reduce dependency risk. The illustrations are stylized, not accurate depictions of specific military platforms. Project cards link to actual public repositories; they do not imply operational deployment, production certification, or completed government delivery.

## Run locally
```bash
git clone https://github.com/elliyeen/elliyeen-naval-portfolio.git
cd elliyeen-naval-portfolio
python3 -m http.server 8000
```
Open http://localhost:8000.

## Manual acceptance checks
1. Both scene tabs switch correctly by mouse, Enter/Space, and left/right arrow keys.
2. All project links open the intended public repository.
3. Navigation works on mobile and desktop.
4. Keyboard focus remains visible; reduced-motion preference is respected.
5. Pages serves the site over HTTPS after deployment.

## Deployment
In **Settings → Pages**, select **Deploy from a branch**, branch **main**, folder **/(root)**, and Save. The static `index.html` needs no build step. GitHub Pages publishing may take several minutes.

## Roadmap
- Replace illustrations with approved, optimized cinematic visual assets.
- Add an actual recorded demo and architectural diagrams.
- Add automated browser accessibility checks and link tests.
- Curate verified project case studies with decisions, evidence, and setup instructions.

## Security
Do not commit secrets, personal credentials, client-confidential architecture, or unapproved government/defense information.
