# InAmigos Foundation - NGO Awareness Webpage

Welcome to the official repository for the **InAmigos Foundation** awareness, outreach, and volunteering platform. 

InAmigos Foundation is a Section 8 youth-led non-profit organization registered under the Companies Act 2013 in India, dedicated to driving bottom-up grassroots sustainable development, humanitarian relief, environmental conservation, and animal welfare.

This repository hosts a high-performance, lightweight, and visual landing webpage optimized for trust verification, public engagement, and volunteer recruitment.

---

## 🎨 Key Features & Interactive Sections

The interface is built using standard, modern **pure HTML5 and CSS3** standards to deliver a premium, responsive user experience with zero external script overhead:

1. **Ambient Moving CSS Mesh Hero**:
   * A slow, ambient-moving radial gradient keyframe background that creates a fluid visual environment at the top of the portal.
   * Prominent CTAs (`Volunteer With Us`, `Explore Projects`) featuring animated border shimmer sheens on hover.

2. **Flagship Initiatives with Visual Headers**:
   * Elegant flexbox-wrap cards grid featuring the 6 primary ground initiatives (Project Seva, Bachpanshala, Udaan, Prakriti, Jeev, and Vikas).
   * Fully integrated ground action slideshow images matching each card's focus area.
   * Floating, high-contrast action icons offset cleanly over the card borders to create depth.
   * Smooth hover transitions scaling images (`1.08x`) and lifting cards (`-10px`) dynamically.

3. **Field Work Action Gallery**:
   * A responsive 4-column ground action gallery grid located above the FAQs.
   * Embedded high-resolution images showcasing real ground-action drives in slums, outdoor tutoring, and community planting.
   * Interactive linear-gradient overlay cards that slide upwards on hover (`opacity: 1`, `transform: translateY(0)`) revealing details about the project drive.

4. **Pure CSS Floating Label Form**:
   * Interactive volunteer form utilizing `:placeholder-shown`, `:focus-within`, and `:valid` selectors to float, shrink, and transition input labels over input borders seamlessly when focused or filled.
   * Premium glassmorphism container backdrop filters with smooth green validation border glow outlines.

5. **Pure HTML/CSS FAQ Accordion**:
   * A Frequently Asked Questions section built using native HTML5 `<details>` and `<summary>` elements.
   * Custom stylized expanding accordion cards featuring smooth toggle-rotating indicators (`la-plus` icons).
   * Complete accessibility with zero-JavaScript interactive open/close animations.

6. **Trust Accreditations & Analytics**:
   * Dynamic glassmorphic statistics dashboard detailing historical impact metrics (meals served, children taught, tree saplings planted, etc.).
   * Verified credentials showcase: **80G Registered** (Tax-Exempt Donations), **ISO 9001:2015 Quality Certified**, and **NITI Aayog Darpan** registered.

---

## 🛠️ Tech Stack & Design System

* **Core Structure**: Semantic HTML5 (strict outline hierarchy with nested `<section>` and `<article>` boundaries).
* **Styling**: Modern Vanilla CSS3 (utilizing custom variables, performance transitions, custom keyframes, and modern pseudo-classes).
* **Iconography**: Line Awesome & Brand Vector Icons for high DPI responsive, vector graphics.
* **Palette Tokens**:
  * `--primary`: `#00cc83` (InAmigos Vibrant Green)
  * `--primary-dark`: `#009962` (Hover Green)
  * `--secondary`: `#222740` (Dark Slate Navy)
  * `--bg-light`: `#fafaf9` (Soft Warm Creamy White)
  * `--text-dark`: `#1e1f26` (Deep Charcoal)
  * `--text-muted`: `#6b7280` (Neutral Muted Gray)

---

## 📂 Project Directory Structure

```text
├── assets/                  # Directory for local image and logo graphic assets
│   └── README.md
├── index.html               # Main webpage structure, forms, gallery, and interactive FAQs
├── style.css                # Premium design system, responsive breakpoints, mesh gradient, and glassmorphism
└── README.md                # Project documentation and interactive guide (This file)
```

---

## 🚀 Running the Project Locally

Since the platform is built purely using standard browser technologies, there are zero build pipelines, packaging scripts, or dependency installations required.

### Option 1: Direct File Running
Double-click `index.html` inside your file browser to open the webpage directly in Google Chrome, Safari, Firefox, or any compliant modern browser.

### Option 2: Local Development Server
If using VS Code or similar IDEs, run the project using local dev servers like **Live Server** or run simple terminal servers from the project root:

```bash
# Python 3
python -m http.server 8000

# Node.js (npx)
npx serve .
```
Access the local environment instantly via your browser at `http://localhost:8000` or `http://localhost:3000`.

---

## 🔍 Accessibility & SEO Standards

* **SEO Meta Declarations**: Contains unique titles, search descriptions, viewport scales, and keyword index maps inside the header.
* **A11y Conformance**: Standard label-input connection mappings to ensure compatibility with screen-readers.
* **Fluid Layouts**: Media queries stack columns seamlessly at tablet (`991px`) and mobile (`576px`) viewports to ensure clean readability on mobile screens.
* **Symmetrical Spacing**: Symmetrical top/bottom section gutters (`padding: 100px 5%` and padding pads between sections) to preserve generous, responsive breathing space.
