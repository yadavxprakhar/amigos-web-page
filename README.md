# InAmigos Foundation - NGO Awareness Webpage

Welcome to the official repository for the **InAmigos Foundation** awareness and volunteering platform. 

InAmigos Foundation is a Section 8 youth-led non-profit organization registered under the Companies Act 2013 in India, dedicated to driving grassroots sustainable development, humanitarian aid, and animal welfare.

This project delivers a premium, highly responsive, and lightweight landing webpage optimized for community outreach, trust verification, and volunteer recruitment.

---

## 🎨 Key Features & Sections

The page is designed with modern premium web aesthetics (glassmorphic overlays, vibrant harmony palettes, and fluid spring-like micro-interactions) and includes:

1. **Vibrant Hero Portal**: High-impact load-in animated headings introducing the youth-led movement with intuitive calls-to-action (CTAs).
2. **About Section**: Detailed grassroots mission, core philosophy card, and highly visual official trust credentials:
   * **80G Registered** (Tax-Exempt Donations)
   * **ISO 9001:2015 Certified**
   * **NITI Aayog Darpan** Registered
3. **The 6 Flagship Projects**: An elegant flexbox-wrap cards grid highlighting:
   * **Project Seva**: Community kitchens & food relief drives.
   * **Project Bachpanshala**: Child literacy & slum elementary education.
   * **Project Udaan**: Women empowerment, hygiene awareness, & vocational training.
   * **Project Prakriti**: Large-scale urban tree plantations & cleanups.
   * **Project Jeev**: Stray animal rescue, water bowls, and veterinary aid.
   * **Project Vikas**: Community infrastructure & rural medical camps.
4. **Social Impact Metrics Grid**: Interactive statistics dashboard using dynamic gradient-filled counters and animated icons detailing historical metrics (50k+ meals served, 5k+ children taught, etc.).
5. **Interactive Volunteer Form**: Form-input grid featuring custom focus glow borders, matching label accessibility structures, and asynchronous inline form-submit success alerts.
6. **Minimal Responsive Footer**: Shorter vertical footprint holding concise branded copy, sitemaps, active email/phone channels, unified social media links, and a functional newsletter subscription element.

---

## 🛠️ Tech Stack & Design System

* **Core Structure**: Semantic HTML5 (strict outline hierarchy with nested `<section>` and `<article>` boundaries).
* **Styling**: Vanilla CSS3 (utilizing modern CSS Custom Properties, smooth transitions, and fluid scaling).
* **Typography**: Modern typography loaded via Google Fonts:
  * Headers: `Outfit`, sans-serif (Bold, premium weights)
  * Body text: `Inter`, sans-serif (Clean, readable leading ratios)
* **Iconography**: Line Awesome & Brand Vector Icons for high DPI responsive graphics.
* **Palette Tokens**:
  * `--primary`: `#00cc83` (InAmigos Vibrant Green)
  * `--secondary`: `#222740` (Dark Slate Navy)
  * `--bg-light`: `#fafaf9` (Soft Creamy White)
  * `--text-dark`: `#1e1f26` (Charcoal)

---

## 📂 Project Directory Structure

```text
├── assets/                  # Directory for local image, icon, and logo resources
│   └── README.md
├── index.html               # Main webpage structure and client-side interactions
├── style.css                # Premium design system, responsive breakpoints, and animations
└── README.md                # Project overview and installation instructions (This file)
```

---

## 🚀 Running the Project Locally

Since the platform is built purely using standard semantic browser technologies, there are zero build pipelines or dependency installations required.

### Option 1: Direct File Running
Double-click `index.html` inside your file browser to open the webpage directly in Google Chrome, Safari, Firefox, or any compliant modern browser.

### Option 2: Local Development Server (Recommended)
If using VS Code or similar IDEs, run the project utilizing local servers like **Live Server** or run simple terminal servers from the project root:

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
* **A11y Conformance**: All inputs are strictly associated with corresponding label elements using direct ID targets for screen-reader readability.
* **Fluid Layouts**: Media queries stack columns seamlessly at tablet (`991px`) and mobile (`576px`) viewports to ensure high mobile touch-target accessibility (`min-height: 48px`).
