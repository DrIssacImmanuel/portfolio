# CLAUDE.md: portfolio (public)

Dr. Issac Immanuel's public portfolio site, served by GitHub Pages at **issacimmanuel.in**.

**Everything in this repo is public, including this file.** Never add private notes, skill gaps, unfinished work or personal identifiers.

## Site
- A static site: `index.html` holds the markup, styles and script in one file. There is no build step.
- `CNAME` (issacimmanuel.in) and `.nojekyll` are required for hosting. Don't delete or rename them.
- Fonts are self-hosted in `fonts/` (Anton, Inter, IBM Plex Mono) with their licence files. Keep the licences, and don't add remote font or CDN dependencies.
- Check changes in a browser at desktop and mobile widths before committing.

## Skills and certificates section (planned)
- The content comes **only** from the owner's private records: projects marked portfolio-ready, and certificates with an issuer verification link. Sources and working notes stay out of this repo.
- Prefer a verification link over hosting a certificate PDF. Before publishing any PDF, check it for registration numbers, date of birth or other identifiers.
- Use the proof's portfolio blurb as the starting copy.
- **Online courses** sit in the Credentials section's "Online courses" list, ordered most relevant first, not by date. Only the first 5 show; the rest fold into a "Show all" button automatically (`data-cap` on the `<dl>`). Each entry links to the issuer's verify page.
- **Courses and projects point to each other.** When a project goes on the site, name the courses that fed into it; when a course supports a published project, link to that project from the course row.

## Commits
Every commit ends with `Co-Authored-By: Claude <noreply@anthropic.com>`.
