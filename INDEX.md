# 30-Day HTML PLAN

**Goal:** Take you from zero HTML knowledge to confident, production-ready HTML skills in 30 days. By the end you'll build a polished personal portfolio site, understand semantic markup, accessibility basics, responsive layout foundations, and be ready to plug HTML into CSS/JS or frameworks.


---

## How to use this plan
1. Do the *concept* section first (read/watch + examples).  
2. Complete the *practice* exercises that follow.  
3. Every Sunday (Day 7, 14, 21, 28) complete the *weekly mini-project* to cement learning.  
4. Build the **Final Project** during Days 25–30: a responsive personal portfolio site.

**Suggested resources:** MDN Web Docs, freeCodeCamp, HTML Living Standard, and small YouTube tutorial snippets. (Pick one primary resource to avoid confusion.)

---

### Week 1 — Foundations (Days 1–7)

**Day 1 — What is HTML & Setup**
- Concept: Purpose of HTML, browsers, how HTML fits with CSS & JS, basic file setup, `.html` files.
- Practice: Create `index.html`, add `<!doctype html>`, `<html>`, `<head>`, `<body>`. Open in browser.
- Quick task: Add page title and a visible H1.

**Day 2 — Text content & headings**
- Concept: Paragraphs, headings (`h1`–`h6`), line breaks, semantic grouping (`main`, `section`, `article`).
- Practice: Create a short article with headings and paragraphs.
- Task: Convert one paragraph into two using `<br>` vs separate `<p>`.

**Day 3 — Links & Images**
- Concept: Anchor tags `<a>`, `href`, target, rel attributes; `<img>` `src`, `alt`, sizing, lazy-loading basics.
- Practice: Add external links, anchor to sections, and images with alt text.
- Task: Create a navigation bar using anchors.

**Day 4 — Lists, Tables & Forms (part 1)**
- Concept: Ordered (`<ol>`), unordered (`<ul>`), description lists (`<dl>`); tables basics (`<table>`, `<tr>`, `<td>`, `<th>`).
- Practice: Create both types of lists and a small data table.

**Day 5 — Forms (part 2)**
- Concept: Form elements: `<form>`, `<input>`, `type` variants, `<label>`, `<textarea>`, `<select>`, buttons, `name` & `value`.
- Practice: Build a contact form with validation attributes (`required`, `pattern`).

**Day 6 — Semantic HTML & Document structure**
- Concept: Semantic tags: `<header>`, `<footer>`, `<nav>`, `<aside>`, `<main>`, `<figure>`, `<figcaption>`; why they matter for SEO & accessibility.
- Practice: Rebuild your `index.html` using semantic structure.

**Day 7 — Weekly Mini-Project: Simple Article Site**
- Build a 3–page static site (Home, Blog, Contact) using semantic markup and navigation. Use images and links.

---

### Week 2 — Intermediate HTML & Accessibility (Days 8–14)

**Day 8 — Media: Audio & Video**
- Concept: `<audio>`, `<video>`, attributes (controls, autoplay, loop), subtitles/captions (VTT and `<track>`).
- Practice: Embed a video with captions and an audio clip.

**Day 9 — HTML5 APIs (Intro)**
- Concept: Data attributes (`data-*`), `contenteditable`, `draggable`, `picture` element for responsive images.
- Practice: Create an image responsive switch with `<picture>` + `srcset`.

**Day 10 — Accessibility (a11y) fundamentals**
- Concept: `alt` text, `aria-*` roles and attributes, tab order, semantic forms, labels, landmarks.
- Practice: Audit your mini-site for accessibility issues and fix them.

**Day 11 — Metadata, SEO basics & Open Graph**
- Concept: `<meta>` tags, page description, viewport, charset, canonical, Open Graph and Twitter Card basics.
- Practice: Add metadata to `index.html` for SEO and social sharing.

**Day 12 — Microdata & structured data (Schema.org intro)**
- Concept: JSON-LD vs microdata for rich snippets.
- Practice: Add basic JSON-LD for a Person or Organization to your site.

**Day 13 — Progressive Enhancement & graceful degradation**
- Concept: Build HTML that works without JS; use proper fallbacks.
- Practice: Create a small widget that works without JS (e.g., a mailto contact link) and then enhance with JS later.

**Day 14 — Weekly Mini-Project: Media-rich Blog Post**
- Build a long-form blog post HTML page containing headings, figures, embedded video, captions, and JSON-LD.

---

### Week 3 — Practical HTML Patterns (Days 15–21)

**Day 15 — Forms deep dive: accessibility & UX**
- Concept: Fieldsets, legends, accessible labels, error messages, input types for mobile (`email`, `tel`, `number`).
- Practice: Improve your contact form with grouped fields and accessible errors.

**Day 16 — File semantics & downloads**
- Concept: `download` attribute on anchors, mime-types, semantic use of file links.
- Practice: Add a resume download link and ensure correct `download` behavior.

**Day 17 — HTML patterns for components**
- Concept: Cards, modals (structure only), lists of items, progressive enhancement patterns.
- Practice: Create a reusable card list of projects using semantic markup.

**Day 18 — Internationalization basics**
- Concept: `lang` attribute, direction (`dir="rtl"`), Unicode, encoding pitfalls.
- Practice: Create a small bilingual snippet and set `lang` properly.

**Day 19 — Performance-minded HTML**
- Concept: Preload, prefetch, async/defer for scripts, `loading="lazy"` for images, minimizing critical HTML.
- Practice: Add `loading="lazy"` to images and add a link rel=preload example for fonts.

**Day 20 — Embedding third-party widgets**
- Concept: Safe ways to embed maps, social embeds, and iframes; `sandbox` attribute on iframes.
- Practice: Embed a map or a tweet safely using an iframe with sandbox.

**Day 21 — Weekly Mini-Project: Component Library (HTML only)**
- Create a small HTML-only component library (cards, form snippet, gallery markup). Document how to reuse components.

---

### Week 4 — Advanced Topics & Final Project (Days 22–30)

**Day 22 — HTML for Modern Layouts (prep for CSS)**
- Concept: Placeholders for CSS grid & flex layout: good markup for responsive layouts, container structure.
- Practice: Mark up a 3-column layout and a single-column mobile layout (no CSS required; just semantic structure).

**Day 23 — Progressive Web App (PWA) basics - manifest & service worker (HTML entry points)**
- Concept: `manifest.json` link in HTML, `theme-color`, service worker registration basics (registering from HTML/JS).
- Practice: Add a `manifest.json` link and meta tags to your site.

**Day 24 — Security basics for HTML authors**
- Concept: XSS vectors, CSP basics (meta tags vs headers), `rel="noopener noreferrer"` for external links.
- Practice: Add `rel` attributes and a simple `<meta http-equiv="Content-Security-Policy">` example.

**Day 25 — Build start: Final Project scaffolding**
- Task: Create folder for Final Project: `index.html`, `about.html`, `projects.html`, `contact.html`, `assets/`.
- Plan your portfolio content and wireframe in HTML (structure only).

**Day 26 — Implement content: semantic pages**
- Task: Add all content HTML: hero section, about, project list markup, contact form (no CSS yet).

**Day 27 — Accessibility & metadata polish**
- Task: Add `aria` attributes, landmark roles, meta tags, SEO descriptions for each page.

**Day 28 — Add interactivity-ready hooks**
- Task: Add `data-*` attributes where UI JS will attach, create obvious IDs for anchors and nav linking.

**Day 29 — Testing & validation**
- Task: Run HTML through W3C validator, perform keyboard-only navigation check, mobile viewport check.
- Fix any markup issues.

**Day 30 — Finalize & Deploy (lightweight)**
- Task: Final review. Add `favicon`, `manifest.json` link, and prepare a README.
- Deploy static site to GitHub Pages or Netlify (HTML-only deploy steps). Celebrate.

---

