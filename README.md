# Brishty Roy — Digital Marketing Portfolio Website

A premium, fully responsive portfolio website for **Brishty Roy**, Google Ads & Digital Marketing Specialist.

---

## Features

- Deep purple + pink luxury agency design
- Fully responsive (mobile, tablet, desktop)
- Smooth scroll navigation with sticky navbar
- Animated fade-in effects on scroll
- Interactive FAQ accordion
- Case study cards with real campaign metrics
- Screenshot gallery with lightbox
- Contact form (links to Google Form)
- Mobile hamburger menu with drawer
- Animated stat counters
- No frameworks — pure HTML, CSS, JavaScript

---

## Folder Structure

```
brishty-portfolio-website/
│
├── index.html          # Main HTML file — all sections
├── style.css           # All styles (dark purple/pink theme)
├── script.js           # Interactivity (nav, accordion, lightbox, etc.)
├── README.md           # This file
│
└── images/
    ├── My Photo.png    # Profile photo
    ├── img2.png        # Google Analytics Certification
    ├── img3.png        # Google Ads Search Certification
    ├── img4.png        # HubSpot Digital Marketing Certification
    ├── img5.png        # HubSpot Content Marketing Certification
    ├── cimg6.png       # Google Ads screenshot
    ├── cimg7.png       # Google Ads screenshot
    ├── cimg8.png       # Google Ads screenshot
    ├── cimg9.png       # Google Ads screenshot
    ├── cimg10.png      # Google Ads screenshot
    ├── cimg11.png      # Google Ads screenshot
    ├── cimg12.png      # Google Ads screenshot
    ├── cimg13.png      # Google Ads screenshot
    ├── ads1.png        # Additional ads screenshot
    ├── ads2.png        # Additional ads screenshot
    ├── ads3.png        # Additional ads screenshot
    ├── ads4.png        # Additional ads screenshot
    ├── ads5.png        # Additional ads screenshot
    └── ads6.png        # Additional ads screenshot
```

---

## How to Use

### Local Use
1. Download and extract the ZIP file
2. Open `index.html` in any web browser — no server required
3. Everything works offline (except Google Fonts, which require an internet connection)

### GitHub Pages Hosting
1. Create a new GitHub repository
2. Upload all files maintaining the folder structure
3. Go to Settings → Pages → Source: `main` branch, root folder
4. Your site will be live at `https://yourusername.github.io/repo-name`

### Any Web Host (cPanel, Hostinger, Namecheap, etc.)
1. Log into your hosting control panel
2. Open File Manager → public_html
3. Upload all files (keeping the `images/` folder intact)
4. Visit your domain — the site is live

---

## Customization

### Update Contact Links
In `index.html`, search and replace:
- `https://calendly.com/roybrishty/30min` → your Calendly link
- `https://forms.gle/D5kyevyQ6TCuFk7x9` → your Google Form link
- `roybrishty823@gmail.com` → your email
- `https://www.linkedin.com/in/brishty-roy-211b41205/` → your LinkedIn
- `https://t.me/broy9965` → your Telegram

### Change Colors
In `style.css`, edit the `:root` variables:
```css
:root {
  --bg: #0B0620;           /* Main background */
  --bg-secondary: #140A2E; /* Section backgrounds */
  --accent-pink: #FF4FD8;  /* Primary accent */
  --accent-purple: #7C3AED;/* Secondary accent */
}
```

### Replace Profile Photo
Replace `images/My Photo.png` with your own photo (keep the same filename, or update the `src` in `index.html`).

---

## Pages / Sections

| Section        | ID               | Description                          |
|---------------|------------------|--------------------------------------|
| Hero          | `#home`          | Headline, photo, CTAs, trust badges  |
| About         | `#about`         | Bio, stats, experience               |
| Certifications| `#certifications`| Google & HubSpot certificates        |
| Services      | `#services`      | 8 service cards with icons           |
| Industries    | `#industries`    | Target industries + video callout    |
| Case Studies  | `#portfolio`     | 5 campaign results + gallery         |
| Process       | `#process`       | 3-step workflow                      |
| Testimonials  | `#testimonials`  | Client reviews                       |
| FAQ           | `#faq`           | Accordion Q&A                        |
| Contact       | `#contact`       | Form + contact details               |

---

## Browser Support

Compatible with all modern browsers:
- Chrome / Edge / Brave
- Firefox
- Safari (macOS & iOS)
- Mobile browsers (Android, iOS)

---

## Credits

- **Design & Development**: Built for Brishty Roy
- **Fonts**: Inter by Google Fonts
- **Icons**: Unicode/Emoji (no dependencies)
- **Contact Form**: Google Forms integration

---

&copy; 2026 Brishty Roy. All rights reserved.
