# Arjun Mehta — Portfolio Template

A dark-themed, animated one-page portfolio built with plain HTML, CSS and
JavaScript (no build step, no framework required).

## What's inside
- `index.html` — page structure and content
- `css/style.css` — dark theme, layout, all animations/effects
- `js/script.js` — cursor glow, hero particle network, scroll reveals, mobile menu

## Effects included
- Ambient particle network in the hero (canvas, connects nearby dots with lines)
- Soft glow that follows your cursor
- Infinite scrolling skills marquee
- Glitch-flicker effect on project titles on hover
- Scroll-triggered fade/slide-in reveals for every section
- Animated gradient blobs in the contact section
- Subtle film-grain texture overlay
- Mobile-friendly slide-in menu

## How to use it
1. Unzip the folder.
2. Open `index.html` directly in a browser — that's it, no server needed.
3. To publish it, drag the folder into a static host (Netlify, Vercel,
   GitHub Pages, Cloudflare Pages all work with zero config).

## How to customize it for yourself
- **Name & copy:** search `index.html` for "Arjun Mehta" and the project/
  experience text, and swap in your own.
- **Photo:** replace the `src` on the `<img>` inside `.about-image` with
  your own headshot.
- **Project images:** replace the `picsum.photos` URLs inside each
  `.project-media img` with screenshots of your own work (same folder,
  e.g. `images/project1.jpg`, then update the `src`).
- **Colors:** all colors are CSS variables at the top of `css/style.css`
  under `:root` — change `--accent` and `--accent-2` to restyle the whole
  site in one place.
- **Fonts:** swap the Google Fonts `<link>` in `index.html` and the
  `--font-display` / `--font-body` variables in the CSS.
- **Sections:** each section (`about`, `work`, `experience`, `contact`) is
  a self-contained `<section>` — duplicate a `.project` block to add more
  work, or a `.timeline-item` to add more experience.

## Notes
- Images currently load from `picsum.photos` and `i.pravatar.cc` as
  placeholders — swap these for real images before publishing.
- Animations respect `prefers-reduced-motion` for accessibility.
