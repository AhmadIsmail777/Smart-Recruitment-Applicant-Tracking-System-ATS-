# AHMAD.OS

Interactive React portfolio for Ahmad Ismail. Content is deliberately separated from UI.

## Run it

1. Install dependencies: `npm install`
2. Start locally: `npm run dev`
3. Create a production build: `npm run build`

## Update your information

All content lives in `src/data/`; the interface imports those files.

- `profile.js` — name, role, bio, education, email, social links. Add GitHub/LinkedIn URLs only when ready.
- `projects.js` — add one project object per project; optional GitHub/live links can be added to each object later.
- `skills.js` — tech tree categories and manually managed levels.
- `system.js` — current build status, certifications, achievements, and version history.
- `theme.js` — central visual colour tokens (ready to expand into CSS variables).

No personal information, work history, awards, links, or metrics have been invented. The GitHub integration remains an explicit extension point until a username is configured.

## Exploration

- The boot choice is remembered locally. Clear site storage to see it again.
- Open applications from the desktop icons.
- Use the Terminal for `help`, `whoami`, `projects`, `skills`, `sudo hire-ahmad`, and more.
- Press `Ctrl + Shift + E` for the developer configuration hint.

## Notes

The architecture is optimized for a small static portfolio. An LLM can later replace the deterministic `AHMAD.AI` response logic without exposing any API keys in the browser.
