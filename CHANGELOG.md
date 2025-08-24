# 📌 Changelog – Your English Teacher Website

This document tracks all major changes, improvements, and fixes made during the development of the website.  
It covers everything from the initial setup to the current state of the project.  

---

## 🚀 Initial Setup
- Project bootstrapped with **HTML + TailwindCSS**.
- Created a **single-page structure** for homepage with sections:
  - Hero / Presentation
  - Formations
  - Parcours en entreprise
  - Certifications
  - Témoignages
  - Contact form
- Added **basic responsive design**.

---

## 🎨 Images & Visuals
- Selected and added **custom HD, watermark-free JPGs** for:
  - Progression
  - Remote teaching (without "e-learning" implication)
  - Parcours en entreprise
  - Certifications (QUALIOPI)
- Added **consistent sizing & rounded corners** for images.
- Replaced **generic icons** with relevant, professional-looking visuals.
- **New:** Replaced the placeholder in the homepage hero section with a **real classroom image**:
  - Added background frame effect using Tailwind (`p-4`, `bg-slate-800`, `rounded-2xl`).
  - Ensured responsive sizing with `object-contain` to avoid cropping.
  - Balanced padding for a **framed visual effect** across devices.

---

## 👩‍🏫 Organisme Section
- Created a **dedicated “Organisme” section** to introduce Kamilia Favre:
  - Bio text imported from the old website.
  - Instructor picture placeholder (`<img>` tag ready).
  - Added **LinkedIn link** (later replaced text with LinkedIn logo SVG).
  - Added **contact email and phone number**.

---

## 📊 Statistics Section
- Added **dynamic statistics cards** with these values:
  - Taux de satisfaction des stagiaires → 100%
  - Taux de retour des enquêtes → 100%
  - Nombre de stagiaires → +500
  - Taux d’interruption en cours de prestation → 0%
  - Taux et cause des abandons → 0%
  - Taux d’insertion dans l’emploi → 45%

---

## ♿ Handicap Section
- Added a **dedicated accessibility section**:
  - Text about accessibility for people with disabilities.
  - Information on questionnaires & partner networks.
  - Emphasis: “Formation accessible aux personnes handicapées”.

---

## 📑 Footer
- Updated footer to include:
  - **Full professional details** of Kamilia Favre:
    ```
    Kamilia Favre
    Service de formation professionnelle en langue anglaise
    Déclaration d'activité enregistrée sous le numéro 52 72 02354 72 auprès du préfet de la région des Pays-de-la-Loire (DREETS)
    Numéro SIRET : 51769619100033
    ```
  - Followed by: `© 2025 Your English Teacher. Tous droits réservés.`
- Maintained footer links (Formations, CPF, Témoignages, Certification, Contact).

---

## 📜 Legal Information Center
- Created **separate “Centre d’informations” page** with tabbed navigation.
- Tabs include:
  - CGV
  - Mentions légales
  - Politique de confidentialité
  - Certificats QUALIOPI
- Styled with **pill-style animated tabs** (white active background, white text inactive).
- Added **ripple effect & white underline animation** for professional look.
- Added **Back button** at top → returns user to homepage.
- Mentions légales include:
  - SIRET
  - Déclaration d’activité
  - Contact info
  - Responsable de la publication
  - Hébergement (placeholder)
  - Adresse postale (placeholder)
- CGV section:
  - Full detailed text structured with headings & bullet lists.
- Politique de confidentialité section:
  - Structured list of data collected, usage, duration, rights.
- Certificats QUALIOPI section:
  - Embedded 3 PDFs:
    - QUALIOPI2021 (04/09/2021)
    - QUALIOPI2023 (20/04/2023)
    - QUALIOPI2024 (20/09/2024)
  - Removed download/print/toolbar from embedded viewer.
  - Clickable links to open full PDFs.

---

## 🔗 Navigation & Linking
- Added **legal tab button in navigation bar** → links to new legal page.
- Internal links corrected:
  - Formations
  - Entreprise
  - Certifications
  - Témoignages
  - Contact
- Fixed blank-page issue when clicking on homepage nav items (anchors restored).
- **New:** Témoignages moved to its **own page** for better separation, with **10 additional testimonials** added for credibility.

---

## 🎯 SEO & Marketing Improvements
- Began SEO & visibility enhancements:
  - Added `<meta name="description">`.
  - Structured headings (`<h1>`, `<h2>`).
  - Planned sitemap & robots.txt.
- Marketing focus updates:
  - Highlight **remote teaching (WhatsApp)**.
  - Emphasized **customized, 100% tailored training**.
  - No “e-learning” implied → focus on **human, live, adapted coaching**.
  - Added preparation for **exam certifications**.
- **New:** Homepage headline reworked:
  - Added **anglais courant**, **anglais professionnel**, **tous niveaux**, **remise à niveau** to better reflect training scope.

---

## 🛠️ UI / UX Enhancements
- Redesigned tabs with:
  - Capsule borders
  - White text default
  - White underline animation for selected
  - Ripple click effect
- Created **consistent professional styling** across all pages.
- Fixed issue with invisible tab buttons when active.
- Fixed **FAQ card spacing & alignment** in the Formations CPF page.
- **New:** Removed gradient effect from Témoignages page → now matches the style of other pages.

---

✅ Current status:  
- Homepage fully built with sections (Formations, Entreprise, Certifications, Témoignages, Contact).  
- Separate **legal information center** with 4 subsections.  
- Footer updated with professional details.  
- Remote training & accessibility highlighted.  
- SEO groundwork in place.  
- Témoignages now standalone with extra testimonials for credibility.  
- Image & visuals updated for a **professional frame effect** in the hero section.  

---

👉 Next Steps (not yet implemented, but planned):  
- Add **structured data / schema.org** for Google.  
- Configure **sitemap.xml** and **robots.txt**.  
- Add **Open Graph & Twitter Card metadata** for social media.  
- Optimize **images with alt text** for SEO.  
- Publish site on **Netlify or GitHub Pages** (free option).  
