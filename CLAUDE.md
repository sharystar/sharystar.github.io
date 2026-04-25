# sharystar.github.io — Project Log

## Overview
Personal academic homepage for 陈淳琳 (Chan Shun-lam), PhD candidate at Tsinghua University.
Deployed at: https://sharystar.github.io

## Tech Stack
- Pure HTML / CSS / JavaScript — no build step required
- Hosted on GitHub Pages (main branch)
- Fonts: Google Fonts (Lora + Inter)

## Project Structure
```
sharystar.github.io/
├── index.html      # Single-page academic website (all sections)
├── .gitignore      # Excludes .secrets and system files
├── .secrets        # GitHub token (git-ignored, never committed)
└── CLAUDE.md       # This file
```

## Sections Implemented
1. **Hero** — Name, affiliation, CTA buttons, animated avatar
2. **About (关于我)** — Bio + 4 feature cards
3. **Education (教育背景)** — Harvard GSE visiting scholar, Tsinghua PhD/Master, BNU Bachelor
4. **Research Interests (研究兴趣)** — 6 topic cards
5. **Publications (发表论文)** — Tabbed view (All / Journal / Conference), 12 entries
6. **Research Projects (参与过的研究项目)** — 10 project cards with roles
7. **Contact (联系方式)** — Email, phone, address, GitHub

## Design
- Color palette: warm orange (#C8622A) + brown (#3D200E, #6B3F2A) on cream (#FEF9F5)
- Typography: Lora (headings/serif) + Inter (body)
- Interactions: scroll-reveal animations, hover lift on cards, sticky nav with active tracking, tab filter for publications, mobile hamburger menu
- Fully responsive (mobile-first at 540px / 720px breakpoints)

## Content Notes
- Harvard GSE visiting scholar added per user instruction (not in original resume)
- AIED 2025 paper and ISSBD 2025 poster added as placeholders — **titles need to be filled in by author**
- Author name highlighted in bold/orange in all publication entries

## Deployment
- Remote: https://github.com/sharystar/sharystar.github.io
- Branch: main
- Push command: `git push https://<TOKEN>@github.com/sharystar/sharystar.github.io.git main`

## Changelog
| Date       | Change |
|------------|--------|
| 2026-04-24 | Initial build — all sections, responsive design, pushed to GitHub Pages |
