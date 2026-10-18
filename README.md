# Muhammad Azhan — Portfolio

Personal portfolio of **Muhammad Azhan**, a second-year student and Web Developer | Full Stack Developer.

- Live site: https://muhammadazhan.dpdns.org
- Repository: https://github.com/Azhan787/Muhammad-Azhan-Portfolio

## Contact
| | |
|---|---|
| GitHub | https://github.com/Azhan787 |
| LinkedIn | https://www.linkedin.com/in/muhammad-azhan-54724537a |
| Email | itxazhan32@gmail.com |
| WhatsApp | +92 370 136 6877 (https://wa.me/923701366877) |

## Tech
HTML5, CSS3, and vanilla JavaScript. No frameworks, no build step, no npm dependencies. Fonts (Sora, Plus Jakarta Sans, JetBrains Mono) load from Google Fonts.

## Features
- White + yellow theme by default, with an optional charcoal + yellow night mode (the choice is saved in `localStorage`; the OS preference no longer overrides it).
- CV download: buttons in the header, hero, mobile menu, footer and a dedicated CV section with a preview image. File: `Muhammad_Azhan_CV.pdf` (set in `CONFIG.cvFilename` in `script.js`).
- Motion: hero name rises word by word on load, scrolling skills ticker, headline highlighter sweep, scroll-reveal for sections and cards, scroll progress bar, and a CV card that tilts toward the pointer. All of it is switched off when the visitor prefers reduced motion.
- Projects loaded from `https://api.github.com/users/Azhan787/repos`, with search, language filters, sorting, and a 15-minute cache. If the API fails or is rate-limited, a fallback entry for this portfolio repository is shown.
- Live-preview modal for projects that have a homepage URL.
- Contact form via FormSubmit. FormSubmit requires a one-time email activation the first time a message is sent. If direct delivery fails, the form opens a pre-filled Gmail/email draft.
- Responsive layout and reduced-motion support.

## Files
`index.html`, `style.css`, `script.js`, `A.png` (portrait), `Muhammad_Azhan_CV.pdf`, `cv-preview.png` (image shown in the CV section), `logo.svg`, `monogram.svg`, `favicon.svg`, `avatar.svg`.

## Run and deploy
Open `index.html` in a browser, or serve the folder with any static host (GitHub Pages, Netlify, Vercel).

## To add later
- **Updating the CV:** replace `Muhammad_Azhan_CV.pdf` and regenerate `cv-preview.png` (a PNG of page 1, about 910 x 1287 px). If you rename the PDF, change `CONFIG.cvFilename` in `script.js` and the `href` / `download` values in `index.html`.
- **Social preview tags:** check the `og:` and `twitter:` meta tags in `index.html` before sharing the link.
- **Education, experience, projects:** add sections only with verified details.

## Attribution
This project was customized from an existing portfolio associated with **Zainab Naseer**. The structure and some code come from that work; branding, content, and the MA logo were replaced. I have not verified the original source's license, so no license is claimed here. Check the original repository before reusing or redistributing.
# pOrtfoLiO-
