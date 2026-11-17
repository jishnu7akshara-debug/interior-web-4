# Interior Website 3 — Aangan Interiors

Light, modern, rounded interior design studio website. Single page, no build step, works offline.

## Open it
Double-click `index.html` (Chrome / Edge). Every photo, video and font loads from this folder.

## Folder
```
index.html        the whole site (HTML + CSS + JS)
fonts/            Bricolage Grotesque + Plus Jakarta Sans (local copies, fonts.css)
images/           26 photos (Pexels) + 5 video poster frames
videos/
  hero.mp4        hero – warm bedroom suite (1080p)
  loft.mp4        films – light-filled loft
  study.mp4       films – the study
  evening.mp4     films – city-light suite
  pendants.mp4    contact section background
```

## Sections
Floating pill nav · hero with inline photo pills + live video card · style marquee · about (word-by-word reveal, fanning photo stack) ·
services tabs (auto-rotating) · drag carousel of design styles (3D tilt) · filterable project gallery + lightbox ·
live film bento (click to play full screen) · 4-step process (scroll-filled timeline) · FAQ accordion · video-backed contact form · footer.

## Deploy
Upload the whole folder as-is (Netlify drag-and-drop, Vercel, cPanel, Hostinger). Keep `fonts/`, `images/`, `videos/` beside `index.html`.

## Replace before launch
- Phone number +91 98450 00000 is a sample — replace with the real one (contact section)
- Project names are sample Bengaluru names — rename to real client projects
- Stock photos → client's own project photos (keep file names or update `src`)
- Connect the form (`#enquiry` submit handler at the bottom of `index.html`) to Formspree / your backend

## Licenses
Photos: Pexels License · Videos: Mixkit Free License · Fonts: SIL Open Font License — all free for commercial use.
