# Nebulla - Responsive UI Implementation

Student Assignment for **UpCurvv** – HTML & CSS Responsive Web Design.

---

## 📌 Project Overview
**Nebulla** is a modern, responsive website built from scratch using semantic HTML5 and clean Vanilla CSS. The layout recreates the project showcase landing page from the reference UI design ([Uizard Preview](https://app.uizard.io/templates/yxnWe9j4EXHP45E0Q6qV/preview)) with a focus on fluid adaptability across mobile, tablet, and desktop devices.

---

## 🚀 Key Features Implemented

1. **Semantic HTML5 Architecture**:
   - Structured with `<header>`, `<nav>`, `<main>`, `<section>`, and `<footer>`.
   - Descriptive `alt` attributes on all images for accessibility.
   - Clean hierarchy with `<h1>`, `<h2>`, `<h3>` headings.

2. **Full Responsive Design**:
   - **Mobile-first approach & custom media queries**:
     - **Mobile (< 576px)**: Single-column stack, centered pure-Flexbox adaptive navigation, optimized typography and touch-friendly buttons.
     - **Tablet (576px – 991px)**: Flexible multi-column layouts, adjusted image dimensions and content containers.
     - **Desktop (≥ 992px)**: Side-by-side content alignments, expanded header navigation, and generous spacing.
     - **Large Desktop (≥ 1200px)**: Wide max-width container with centered layout.
   - **Zero Horizontal Overflow**: Built with `box-sizing: border-box`, fluid `%`, `rem`, `vw` units, and responsive image scaling (`max-width: 100%`).

3. **Core Sections Recreated**:
   - **Header & Navigation**: Brand logo, navigation menu, and action buttons cleanly arranged via responsive CSS Flexbox.
   - **Hero Section**: Headline, trial badge, double CTA buttons, and 3D hero illustration.
   - **Trusted Companies**: Logo bar featuring industry leaders (Google, Microsoft, Slack, Instagram, Apple).
   - **Alternating Feature Cards**:
     - *Introducing Good Solution*
     - *SmartSave (Cloud Data Security)*
     - *CostSaver (Operations & Analytics)*
   - **Step-by-Step Onboarding**: 3-step structured guidance card with illustration.
   - **Customer Testimonials**: 3 elevated customer quote cards with 5-star ratings.
   - **Call-to-Action (Get Started)**: Prominent bottom CTA block.
   - **Footer**: 4-column categorical layout for brand overview, pages, social, and legal links.

4. **Additional Multi-Page Views**:
   - `index.html` (Home)
   - `pricing.html` (3-tier Pricing Plans & Feature Comparisons)
   - `about.html` (Company Mission & Team Profiles)
   - `contact.html` (Get in Touch Form & Direct Channels)

---

## 📁 Project Directory Structure
```text
P-Nebula/
│
├── index.html            # Main Landing Page
├── pricing.html          # Pricing Plans Page
├── about.html            # About Us & Team Page
├── contact.html          # Contact Page
├── README.md             # Project Documentation & Summary
│
├── Styles/
│   ├── styles.css        # Global design system, components & media queries
│   ├── pricing.css       # Pricing-specific layout styles
│   ├── about.css         # About page styles
│   └── contact.css       # Contact page styles
│
└── Assets/
    └── Images/
        ├── Cover-Images/ # 3D section visuals (Cv-1.png to Cv-8.png)
        ├── icons/        # Brand and UI icons (google, microsoft, slack, etc.)
        └── profiles/     # Team member profile pictures
```

---

## 📱 Testing Checklist

- [x] **375px – Mobile**: Single-column vertical layout, compact navigation, readable fonts.
- [x] **425px – Large Mobile**: Fluid image scaling, touchable tap targets.
- [x] **768px – Tablet**: Responsive navigation menu toggle, balanced 1-2 column cards.
- [x] **1024px – Laptop / Small Desktop**: Side-by-side hero and alternating features.
- [x] **1440px – Large Desktop**: Max-width centered container (`1240px`).
- [x] **No Horizontal Scrollbar**: Strict overflow prevention on all screen sizes.
- [x] **Hover & Focus States**: Buttons and navigation links feature smooth feedback transitions.

---

## 🔗 Links & Submissions
- **GitHub Repository**: *(Add your GitHub repo link here)*
- **Live Deployment Link**: *(Add your Netlify / Vercel / GitHub Pages link here)*

---
*Created as part of the UpCurvv Responsive Web Design Assignment.*
