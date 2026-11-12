# Crown & Comb — Luxury Salon & Spa Website

<div align="center">
  <img src="images/logo.svg" alt="Crown & Comb Logo" width="220" />
  <p><strong>A modern, responsive, and elegant website for a premier beauty salon and luxury spa.</strong></p>

  [![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
  [![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
  [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
  [![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white)](https://jquery.com/)
  [![Font Awesome](https://img.shields.io/badge/Font_Awesome-528DD7?style=for-the-badge&logo=font-awesome&logoColor=white)](https://fontawesome.com/)
</div>

---

## 📖 Overview

**Crown & Comb** is a fully responsive, visually captivating landing page designed specifically for high-end beauty salons, aesthetic clinics, and day spas. Crafted with a delicate blush-pink and rose gold aesthetic, the website provides a seamless user experience across all devices—from mobile phones to wide desktop monitors.

The site highlights premium services, expert staff, curated beauty treatments, recent blog articles, and direct appointment booking channels.

---

## ✨ Features & Sections

- **Crown & Comb Brand Identity**: Bespoke SVG crown-and-comb crest logo with elegant typography and custom Google Fonts (`Playfair Display` & `Lato`).
- **Interactive Sticky Header**: 
  - Dynamic navigation bar with modern frosted-glass backdrop blur (`backdrop-filter`).
  - Instant one-tap phone dialing (`tel:`) and location links in the header.
- **Hero & Slider Banner**:
  - High-impact promotional banner with call-to-action buttons for appointments and consultations.
- **Certified Specialists & Doctors**:
  - Profile cards spotlighting dermatologists and skin aesthetic doctors.
- **Service Catalog**:
  - Clean 6-card interactive grid showcasing:
    - Eyebrow Shaping & Tinting
    - Facial Treatments
    - Haircut & Styling
    - Hair Removal & Waxing
    - Skin Rejuvenation
    - Luxury Spa Treatments
- **Team Showcase**:
  - Split-column layout featuring hair stylists, makeup artists, cosmetic surgeons, and nail artists with social media handles and zoom-on-hover effects.
- **Latest Blog Posts**:
  - Curated beauty and skincare guides with publication timestamps.
- **Footer & Alternative Contact Details**:
  - Comprehensive contact section featuring updated alternative details.
  - Newsletter subscription form for VIP offers and beauty tips.
  - Social media channel links (Facebook, Twitter/X, Instagram, Pinterest).
- **Smooth Scroll-To-Top**:
  - Animated floating action button powered by jQuery that activates when scrolling down.

---

## 📞 Contact Details

| Contact Channel | Details |
| :--- | :--- |
| **Brand Name** | **Crown & Comb** |
| **Primary Phone** | [+1 (212) 555-0198](tel:+12125550198) |
| **Alternative Phone** | [+1 (212) 555-0144](tel:+12125550144) |
| **Address** | 128 Crown Street, Suite 400, New York, NY 10012 |
| **General Inquiry Email** | [info@crownandcomb.com](mailto:info@crownandcomb.com) |
| **Appointments Email** | [appointments@crownandcomb.com](mailto:appointments@crownandcomb.com) |

---

## 📁 Project Structure

```text
Crown-and-comb/
├── images/                           # Visual assets & photography
│   ├── blog-1.jpg                    # Skincare blog image
│   ├── blog-2.jpg                    # Dermatology advice image
│   ├── blog-3.jpg                    # Nail design blog image
│   ├── bottom-img.jpg                # Lower banner background
│   ├── Cosmetic-Surgeon.jpg          # Specialist profile photo
│   ├── Eyebrow-shaping-and-tinting.png # Service vector icon
│   ├── Facial-treatments.png         # Service vector icon
│   ├── Hair-removal.png              # Service vector icon
│   ├── Hair-specialist.jpg           # Team member photo
│   ├── Haircut-and-styling.png       # Service vector icon
│   ├── head-img.jpg                  # Hero banner background
│   ├── logo.svg                      # Crown & Comb vector logo
│   ├── Makeup-artist.jpg             # Team member photo
│   ├── mid-img.jpg                   # Mid-page banner image
│   ├── Nail-Artist.jpg               # Team member photo
│   ├── person-1.png                  # Doctor avatar
│   ├── person-2.png                  # Doctor avatar
│   ├── person-3.png                  # Doctor avatar
│   ├── service-img-[1-6].jpg         # Treatment gallery images
│   ├── skin-rejuvenation.png         # Service vector icon
│   └── Spa-treatments.png            # Service vector icon
├── index.html                        # Main website markup
├── jqury.min.js                      # jQuery library (v3.x)
├── style.css                         # Primary stylesheet (layout, header, footer)
├── style2.css                        # Secondary stylesheet (services, team cards)
├── README.md                         # Project documentation
└── view.md                           # Original design preview notes
```

---

## 🛠️ Technology Stack

- **HTML5**: Clean, semantic markup with accessible tags and meta tags for responsive viewport scaling.
- **CSS3**:
  - Flexbox and custom column-based grid systems.
  - CSS variables for spacing and color consistency.
  - Backdrop filters for frosted-glass effects.
  - Media queries targeting mobile (480px), tablet (768px), desktop (960px, 1200px).
- **JavaScript & jQuery**:
  - Sticky header toggle on scroll (`> 60px`).
  - Dynamic scroll-to-top trigger (`> 300px`) with smooth animated scrolling.
- **Web Fonts & Icons**:
  - [Google Fonts](https://fonts.google.com/): *Playfair Display* (luxury serif) & *Lato* (body sans-serif).
  - [Font Awesome 6](https://fontawesome.com/): Vector icons for phone, map, mail, search, and social media.

---

## 🚀 Getting Started

No build tools or package managers are required to run this project.

### 1. Clone the repository
```bash
git clone https://github.com/your-username/Crown-and-comb.git
cd Crown-and-comb
```

### 2. Run locally
- **Option A**: Double click `index.html` to open it in your default web browser.
- **Option B**: Use VS Code's **Live Server** extension (right-click `index.html` > *Open with Live Server*).
- **Option C**: Use Python's built-in HTTP server:
  ```bash
  python -m http.server 8000
  ```
  Then navigate to `http://localhost:8000` in your browser.

---

## 🎨 Customization Guide

- **Updating Contact Information**:
  - Edit the phone numbers, address, and email addresses in the `<div class="main-info">` and `<footer class="main-footer">` sections in `index.html`.
- **Modifying Services or Pricing**:
  - Find `.services-container` in `index.html` to add, remove, or modify services and icons.
- **Updating Brand Logo**:
  - Replace or adjust `images/logo.svg` to fit custom branding or color themes.

---

## 📱 Responsive Breakpoints

| Device | Viewport Width | Layout Adjustment |
| :--- | :--- | :--- |
| **Mobile** | `< 480px` | Single-column services, stacked member cards |
| **Tablet** | `481px - 768px` | 2-column services, adaptive header contacts |
| **Desktop** | `769px - 1199px` | 3-column services, side-by-side team cards |
| **Large Screens** | `≥ 1200px` | Full container layout with max-width 1200px |

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

