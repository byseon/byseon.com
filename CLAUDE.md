# byseon.com

Personal homepage for SEON. Static site hosted on GitHub Pages with Cloudflare DNS.

## Stack

- Static HTML + CSS only. No JavaScript unless absolutely necessary.
- No build tools, no frameworks, no bundlers.
- Hosted via GitHub Pages (`byseon/byseon.com` repo, `main` branch).
- Domain: `byseon.com` through Cloudflare (A records + CNAME for www).

## Files

```
index.html          — single page, semantic HTML
styles.css          — all styles, CSS custom properties
favicon.svg         — SVG favicon, letter "S"
og.png              — OG image for social sharing (1200x630)
CNAME               — GitHub Pages custom domain
robots.txt          — crawl rules
sitemap.xml         — sitemap
github-profile-README.md — source for github.com/byseon/byseon README
```

## Design system

- Background: `#0a0a0b` (warm charcoal, not pure black)
- Text: `#e8e6e3` (warm off-white)
- Muted: `#9a9691`
- Accent: `#d4a574` (bronze)
- Accent hover: `#e8c9a0`
- Serif (hero): Iowan Old Style / Palatino Linotype / serif
- Sans (body): system font stack (-apple-system, BlinkMacSystemFont, etc.)
- Max content width: 42rem
- Generous whitespace. Quiet confidence.

## Writing tone

Short. Sharp. No exaggeration. No corporate stiffness. No startup hype.
Calm, intelligent, human. Credible.

## Key phrases (shared across homepage + GitHub profile)

- "I build systems for speech, intelligence, and human communication."
- "Pronunciation, ASR, voice agents, applied ML."
- "I write, record, and release music, and document moments through photography."

## Rules

- Do not add JavaScript unless there is no CSS-only alternative.
- Do not add placeholder or dead links. Only use real URLs.
- Do not mention unreleased product names.
- Do not add external font imports. Use system fonts only.
- Keep the page a single HTML file. No multi-page routing.
- When updating the GitHub profile README, also update `github-profile-README.md` here and push to `byseon/byseon` repo.

## Deploy

Push to `main`. GitHub Pages auto-deploys. Changes go live within ~2 minutes.
