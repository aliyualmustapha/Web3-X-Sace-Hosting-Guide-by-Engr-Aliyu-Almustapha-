<p align="center">
  <img src="assets/trustchain-academy-logo.png" alt="TrustChain Academy logo" width="160">
</p>

# The Ultimate Guide to Web3 X Space Hosting

**From First Space to Professional Hosting, Moderation, Community Building & Web3 Communication**

A practical handbook for Web3 hosts, moderators, speakers, community managers, founders, creators, ambassadors and ecosystem builders who want to run better conversations on X Spaces. Published by TrustChain Academy.

<p align="center">
  <a href="THE-ULTIMATE-GUIDE-TO-WEB3-X-SPACE-HOSTING.pdf"><img src="assets/cover.png" alt="Cover of The Ultimate Guide to Web3 X Space Hosting" width="300"></a>
</p>

---

## About

Every week, thousands of Web3 conversations happen live on X Spaces. In each of them, a host decides who speaks, which questions are asked, and whether a misleading claim is challenged or left to spread.

This handbook was created to give that role real training. It takes readers from “what is a Space?” to planning, opening, moderating and closing a professional Web3 Space, handling difficult moments, protecting listeners from scams and misinformation, and turning each Space into lasting value.

It assumes no prior knowledge. Statements are labelled as **Fact**, **Best Practice**, **Recommendation** or **Opinion**. Platform details were checked against X’s official Help Center in October 2026.

- **Format:** PDF, 27 pages
- **Edition:** First edition, October 2026

## What it covers

| Area | Includes |
|---|---|
| Planning | The 5P Framework, purpose briefs, formats, agendas |
| Preparation | Speaker selection and briefing, technical checks, contingency |
| Questioning | Eight question types, the Question Ladder, weak vs professional questions |
| Moderation | The 3S Framework, the ACT technique, transitions, time management |
| Etiquette | Standards for hosts, co-hosts, speakers, listeners and project teams |
| Audience management | Collecting questions, bringing listeners on stage, quiet and crowded rooms |
| Web3 safety | Phishing, impersonation, fake giveaways, wallet safety, responsible claims |
| Difficult situations | The CALM response and scripts for fourteen situations |
| Promotion | Announcements, reminders and a promotional timeline |
| Post-Space follow-up | Closing scripts, thank-yous, recaps and content repurposing |
| Performance measurement | Reach, depth, value and community metrics |
| Professional growth | Reputation, relationships and a hosting portfolio |

It also includes printable checklists, templates and a self-assessment.

## Who it is for

- Beginners hosting their first Space
- Experienced X Space hosts and moderators
- Speakers and project representatives
- Community managers and ambassadors
- Web3 founders, creators, educators and ecosystem builders

## Author

**Engr. Aliyu Almustapha**
Researcher • Web3 Educator • Ecosystem Builder & Strategist
Co-founder & Chief Operating Officer, TrustChain Academy

## Resources

| Resource | Link |
|---|---|
| Website | `https://YOUR-GITHUB-USERNAME.github.io/web3-x-space-hosting-guide/` *(replace after publishing; see below)* |
| PDF | [THE-ULTIMATE-GUIDE-TO-WEB3-X-SPACE-HOSTING.pdf](THE-ULTIMATE-GUIDE-TO-WEB3-X-SPACE-HOSTING.pdf) |
| GitHub repository | `https://github.com/YOUR-GITHUB-USERNAME/web3-x-space-hosting-guide` *(replace after publishing)* |
| TrustChain Academy | *Add the official TrustChain Academy website when available.* |

Author and academy social profiles have intentionally not been added. Add them here only using verified official links.

## How to use

- **Read online:** open the website and choose *Read the Guide*. The PDF opens in your browser’s built-in viewer.
- **Download:** choose *Download PDF* on the website, or download the PDF file directly from this repository.
- **Use the toolkit:** Chapter 14 contains checklists and templates designed to be copied and reused before, during and after every Space.

The PDF is the complete, authoritative publication. The website introduces it and links to it.

---

## Publishing this site on GitHub Pages

The site is plain HTML, CSS and JavaScript. It needs no build step, database, server, API keys or paid hosting.

### 1. Create the repository

1. Sign in to GitHub and select **New repository**.
2. Name it `web3-x-space-hosting-guide` (recommended, so the links below match).
3. Set visibility to **Public**. (GitHub Pages is available for public repositories on GitHub Free.)
4. Select **Create repository**.

### 2. Upload the files

1. On the new repository page, select **uploading an existing file** (or **Add file → Upload files**).
2. Drag in **everything inside this folder**, including the `assets`, `css` and `js` folders, the PDF, `index.html`, `README.md`, `LICENSE` and `.nojekyll`.
   `index.html` must sit at the top level of the repository, not inside another folder.
   Some operating systems hide files beginning with a dot. If `.nojekyll` is missing, the site still works; it only tells GitHub to skip unnecessary processing.
3. Select **Commit changes**.

### 3. Turn on GitHub Pages

1. In the repository, open **Settings**.
2. In the sidebar, under **Code and automation**, select **Pages**.
3. Under **Build and deployment → Source**, choose **Deploy from a branch**.
4. Under **Branch**, choose **main** and the **/ (root)** folder, then select **Save**.
5. Wait a minute or two, then refresh the page. GitHub shows the live address at the top of the Pages settings, usually:
   `https://YOUR-GITHUB-USERNAME.github.io/web3-x-space-hosting-guide/`

### 4. Before you publish: replace the placeholders

Social platforms need full web addresses to show a preview image. Open `index.html` and replace every occurrence of:

```
https://YOUR-GITHUB-USERNAME.github.io/web3-x-space-hosting-guide/
```

with your real GitHub Pages address (keep the trailing `/`). There are five occurrences: the canonical link, `og:url`, `og:image` and `twitter:image`, plus the path inside the deployment note comment. Also replace the address in the **Resources** table of this README.

The **View on GitHub** button detects the repository automatically when the site runs on `github.io`. If you later use a custom domain, update its address in `index.html` too (search for `data-github-link`).

Optional: in **Settings → General → Social preview**, upload `assets/social-preview.png` so the repository itself also has a branded preview.

### 5. Check the live site

- Open the site on a phone and a computer.
- Select **Read the Guide** and **Download PDF**; both should open the handbook.
- Paste the site address into a post draft on X or LinkedIn to confirm the preview image appears. Some platforms cache previews, so a new image can take time to show.

### Updating the handbook later

Upload a new PDF with exactly the same filename, `THE-ULTIMATE-GUIDE-TO-WEB3-X-SPACE-HOSTING.pdf`, and commit. The website links update automatically. If the page count or edition changes, update the caption under the cover in `index.html`.

---

## Project structure

```
web3-x-space-hosting-guide/
├── index.html                                   Landing page
├── THE-ULTIMATE-GUIDE-TO-WEB3-X-SPACE-HOSTING.pdf  The handbook
├── README.md
├── LICENSE                                      Licence status
├── .nojekyll                                    Serve files as-is on GitHub Pages
├── css/style.css
├── js/script.js                                 Menu, GitHub link, sharing (optional)
└── assets/
    ├── trustchain-academy-logo.png / .webp
    ├── cover.png / .webp                        Rendered from page 1 of the PDF
    ├── social-preview.png                       1200 × 630 sharing image
    ├── favicon.png, favicon-32.png, favicon-180.png
    ├── pages/                                   Sample page previews
    └── fonts/                                   Self-hosted Montserrat, Inter, Source Serif 4 (SIL Open Font License)
```

No analytics, tracking scripts or third-party requests are included.

## License

**License: To be determined.**

No licence has yet been granted for the handbook, website text or brand assets. See [LICENSE](LICENSE) for the current status and a recommendation. The TrustChain Academy name and logo are not covered by any future content licence unless stated explicitly.

The bundled fonts are distributed under the SIL Open Font License 1.1 by their respective authors.

---

*X and X Spaces are trademarks of X Corp. This is an independent educational publication, not affiliated with or endorsed by X Corp. Nothing in the guide is financial, legal or investment advice.*
