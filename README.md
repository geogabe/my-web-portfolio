# Geoffroy G. — Portfolio

Personal portfolio website for Geoffroy Gaborieau — Product Designer, Creative Director, and Data Visualization specialist with 21+ years of experience.

**Live at:** [geogabe.github.io/my-web-portfolio](https://geogabe.github.io/my-web-portfolio) *(once deployed)*

---

## Structure

```
/
├── index.html          # Homepage — masonry grid of case studies
├── about.html          # Bio, skills, career timeline
├── contact.html        # Contact links
├── styles.css          # Full design system
├── images/             # Project screenshots, thumbnails, videos
├── js/
│   └── masonry.pkgd.js # Masonry layout library
└── pages/
    ├── amplify.html
    ├── amplify-mobile.html
    ├── appex.html
    ├── datadna.html
    ├── dewa.html
    ├── evr.html
    ├── mudano.html
    ├── oilandgas.html
    ├── quo.html
    ├── supportview.html
    ├── vantage.html
    └── pdf/            # Case study PDFs + CV
```

## Case Studies

| Project | Category |
|---|---|
| Nexthink Amplify | IT Support · Browser Extension |
| Nexthink Amplify Mobile | IT Support · Mobile |
| Nexthink Application Experience | IT Support · Platform |
| Nexthink Support View | IT Support · Platform |
| DEWA | Decision Tool · Energy & Utilities |
| EVR | IT Security |
| QUO | Trading · Wealth Management |
| Sharktower (Mudano) | Delivery Management |
| DataDNA | Analytics Platform |
| Teradata Vantage | Data Analytics |
| Oil & Gas Supply Chain | Logistics |

## Tech

Pure HTML, CSS and vanilla JavaScript — no framework, no build step. Masonry grid layout via [Masonry.js](https://masonry.desandro.com/).

## Running locally

```bash
npx serve .
```

Then open [http://localhost:3000](http://localhost:3000).

## To do

- [ ] Update email in `contact.html`
- [ ] Update LinkedIn URL in `contact.html`
- [ ] Deploy (GitHub Pages, Netlify, or Vercel)
