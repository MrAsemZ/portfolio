# My Portfolio

A personal developer portfolio site for **A'sem Al-Zaghal** — software engineer based in Amman, Jordan.

**[Live site](https://mrasemz.github.io/portfolio/)**


## What this is

A one-page portfolio: home, about, selected work, and contact. It introduces who I am, shows the projects I've built end to end, and gives a way to get in touch or download my résumé.

## Why it was made

To have a single place that represents my work properly — instead of pointing people to scattered GitHub repos or a plain résumé. It also doubles as practice: designing a real interface in Figma first, then building it from scratch in plain HTML/CSS with out using frameworks, to get the fundamentals right before relying on tools that do it for me.

## How it was made

- **Designed first, built second.** The layout, spacing, and color system were planned in Figma before any code was written.
- **Pure HTML/CSS.** No frameworks, no build step! just HTML and hand-written CSS, styled with CSS variables-style consistency (dark theme, `Space Grotesk` + `JetBrains Mono`).
- **No JavaScript for interactivity.** The one interactive piece — the journey map in the About section — is done with the radio input + label + `:checked` sibling-selector trick, so clicking a pin reveals its info card with zero JS.

## File structure

```
/
├── index.html          → the page itself: all sections/markup
├── style.css            → all styling for the page
├── README.md            → this file
├── docs/                 → downloadable CV (PDF), linked from the Contact section
└── documentation/        → Figma wireframe/design reference for this project
```

- `index.html` and `style.css` are the actual site — everything visible at the live link.
- `docs/` holds the résumé PDF that the "Download résumé" button links to.
- `documentation/` holds the design reference (Figma export/wireframe) this build was based on.

**[Figma design](https://www.figma.com/site/RBrcVXvkh8pw2eKaE2Tz9g/My-Portfolio?node-id=0-1&p=f&t=ovhYNfONCckyBIZw-0)**
