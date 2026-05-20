# BVH Enterprises LLC – Website

Professional technology services website for BVH Enterprises LLC.

## Project Structure

```
bvh-final/
├── index.html          ← Single-file website (logo embedded as base64)
├── README.md
├── .gitignore
└── assets/
    ├── video/
    │   └── hero-bg.mp4     ← Hero background video (~21MB)
    └── images/
        └── bvh-logo-transparent.png  ← Logo with transparent background
```

## Features

- Full-screen video hero background
- BVH logo with transparent background (black removed)
- Animated floating logo in hero section
- Auto-scrolling services carousel
- Services, About, Mission/Vision, Why Us, Testimonials, Contact, Map sections
- Mobile-responsive with hamburger nav
- Scroll-triggered fade-in animations
- Contact form with success feedback
- Google Maps embed for Richmond, VA office

## GitHub Deployment

### GitHub Pages
1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Source: `main` branch / root
4. Live at: `https://<username>.github.io/<repo-name>/`

> **Note:** The video file is ~21MB — within GitHub's 100MB file limit.
> For faster global delivery, consider uploading the video to a CDN and
> updating the `src` in `index.html` (search for `hero-bg.mp4`).

### Local Preview
```bash
npx serve .
# or
python3 -m http.server 8080
```

## Customisation

| What | Where |
|------|-------|
| Logo | Embedded base64 in `index.html` → search `LOGO_B64` |
| Video | `assets/video/hero-bg.mp4` |
| Content | All in `index.html` |
| Colors | CSS variables at top of `<style>` block |

---

© 2025 BVH Enterprises LLC · Richmond, VA · NAICS 541512
