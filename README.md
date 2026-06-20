# GoVibe — Landing Page

Self-contained landing-page mockup for **GoVibe** (AI-native CoDev platform).

- **Live preview:** deploys to Vercel from `main`
- **Source mockup:** authored from the GoVibe Mission Control repo (`docs/design/LANDING-GoVibe-Mockup.html`)
- **Single file:** `index.html` carries all CSS + JS inline (no build step)

## What's inside

A single static HTML page with:

- Cinematic hero — WebGL depth-scan canvas, cursor-follow glow, trapezoid logo notch
- Sticky mini-header + scroll progress + edge-anchored progressive scroll-blur
- Slim bottom system dock with live MCP status indicator
- 16 section copy outline (hero → trust → metrics → approach → capabilities → cards → use cases → governance → testimonial → pricing toggle → FAQ → integrations → CTA → footer)
- Scroll-progress reveal (continuous opacity + translateY mapped per element)
- 3D tilt + spotlight on cards · magnetic CTAs · marquee trust strip · count-up metrics · word-stagger reveal on headlines · per-section ambient tint
- `prefers-reduced-motion` guards on every motion layer

## Local preview

```bash
npx serve .
# or simply open index.html in a browser
```

## Deploy

```bash
vercel --prod
```
