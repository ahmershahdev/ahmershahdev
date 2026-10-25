# AGENTS.md

GitHub profile repository of Syed Ahmer Shah (`github.com/ahmershahdev`). `README.md` is the
profile page; GitHub Pages serves the repository from `master` at
<https://ahmershahdev.github.io/ahmershahdev/>. Owner: <https://ahmershah.dev>,
support@ahmershah.dev.

## Source of truth

The portfolio ([ahmershah.dev](https://ahmershah.dev), private repo `ahmershahdev/ahmershah.dev`)
owns every fact. This repository copies it; it never invents numbers.

| Here | Comes from |
|---|---|
| Projects (order, titles, highlights, stack badges) | `src/content/projects.ts` on the portfolio |
| Certificates and skill levels | `src/content/certificates.ts`, `skills.ts` |
| `llms.txt`, `llms-full.txt` | copied unchanged from the live site's `/llms.txt` and `/llms-full.txt` |
| Palette | portfolio brand: `#0b0d11`, `#4cc22e`, `#1e4fd8` |
| `assets/projects/*.webp` | a 1280 x 720 WebP screenshot per project, named after the project slug |

When a project, certificate or count changes on the portfolio, update every place here in the same
commit: the typing line, the intro sentence, the badge row (platforms, certificates, articles), the
Selected work section and both llms files.

## Rules

- Projects are numbered `01 ·` to `NN ·` in portfolio order, each with a screenshot, a bold one-line
  pitch, three or four highlights, stack badges and case study and source links.
- Badge logos: Shields.io `logo=` names; when one is missing, a base64 SVG data URI.
- Every image has a descriptive `alt`.
- `googlefd88f5d13cd71b69.html` is the Google Search Console verification file: never delete it.
- No emojis. Commit messages describe what changed on the profile.

## Status

Last updated: 2026-10-25. Six projects: MarketClock, HolidayOps, Zovita+, BookMyMovie, GleanGrid,
Commerza (all 2026). 13 certificates, LeetCode 676 solved. No releases or wiki: this is a profile
page, not software.
