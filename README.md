# 💊 Meddy AI – Digital Health Companion

**Meddy AI** is an interactive, multi-product digital health companion built for SAHPRA-compliant Patient Information Leaflets (PIL). It provides digital, easy-to-understand medication guides for caregivers and animated, child-friendly educational content for pediatric healthcare.

---

## ✨ Features

- 📱 **Multi-Product Support**: Easily switch between medication profiles with dedicated dosing calculators, instructions, and warnings:
  - **Panado® Paediatric Syrup** *(Paracetamol)*
  - **Allergex® Tablets** *(Chlorphenamine Maleate)*
  - **Adco Nebrafen Inhalant** *(Fenoterol & Ipratropium Bromide)*
- 👨‍👩‍👧 **Caregiver View**:
  - Step-by-step medication guides (Overview, Dosing, Safety Warnings, Storage).
  - Interactive **Dose Calculator** based on age and weight guidelines.
  - SAHPRA Patient Information Leaflet (PIL) verified information.
- 🎈 **Child Zone**:
  - Animated character avatar with natural floating & blinking animations.
  - Curated, safe educational YouTube videos explaining how medicine works, why we sneeze, and how lungs function.
- 📦 **Dynamic Packaging & QR Code Generator**:
  - Live QR Code generator integrated with [QuickChart API](https://quickchart.io).
  - Test scannable packaging QR codes using query string routing (`?product=PANADO`, `?product=ALLERGEX`, `?product=NEBRAFEN`).
- 💬 **Ask Meddy Assistant**:
  - Natural Q&A keyword matching for fast answers regarding dosage, safety warnings, and side effects.
- 🌐 **Multilingual Ready**: UI layout designed for quick language switching (English, isiZulu, Sesotho).

---

## 🛠️ Tech Stack

- **HTML5 & CSS3**: Modern glassmorphism UI built with CSS custom properties (CSS variables), flexbox layout, and CSS keyframe animations.
- **JavaScript (Vanilla ES6+)**: Responsive state management, query parameter routing, dynamic DOM rendering, and integrated dosage calculators.
- **Google Fonts**: [Plus Jakarta Sans](https://fonts.google.com/specimen/Plus+Jakarta+Sans) for high readability across mobile devices.
- **QuickChart API**: Dynamic real-time QR code generation.

---

## 🚀 Live Demo & QR Scanning Workflow

### 1. Run / Host the Application
You can open `index.html` directly in any web browser or deploy it via GitHub Pages:
```bash
https://<your-username>.github.io/<repository-name>/
