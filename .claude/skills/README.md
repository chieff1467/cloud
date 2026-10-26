# Project skills: web development

Claude Code loads these automatically in sessions opened on this repo. They are **copies**, not links,
so they work without initializing the submodules in `claude-skills/`.

| Skill | Source | What it's for |
|---|---|---|
| frontend-design | anthropics/skills | Visual direction, typography, non-generic UI |
| webapp-testing | anthropics/skills | Playwright (Python): screenshots, console logs, UI checks against a local server |
| senior-frontend | alirezarezvani/claude-skills | React / Next.js / TypeScript / Tailwind: scaffolding, components, bundle analysis |
| api-design-reviewer | alirezarezvani/claude-skills | REST API linting, breaking-change detection, scorecard |
| web-asset-generator | alonw0/web-asset-generator | Favicons, PWA icons, Open Graph images |
| brainstorming | obra/superpowers | Agree on a design before building |
| test-driven-development | obra/superpowers | Write the failing test first |
| systematic-debugging | obra/superpowers | Find the root cause before fixing |
| verification-before-completion | obra/superpowers | Run the checks before claiming done |

## Local changes vs upstream
- `superpowers:` prefixes removed from cross-references between included skills.
- `brainstorming`: the hand-off to `superpowers:writing-plans` (not included) now says to write an
  implementation plan / use plan mode.
- `test-driven-development/writing-good-tests.md`: the `writing-skills` reference points to obra/superpowers.
- Upstream `LICENSE` files copied into skills that didn't carry one.

## Updating
`git submodule update --remote --depth 1`, then re-copy the folder from `claude-skills/` and re-apply the changes above.
