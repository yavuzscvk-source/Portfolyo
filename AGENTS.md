# AGENTS.md — Portfolyo

## Project context
A collection of static demo websites for small businesses. The current top-level pages include `index.html`, `kafe.html`, `guzellik.html`, and `oto-servis.html`. Existing project guidance is also in `CLAUDE.md`.

## Working rules
- Communicate with the user in Turkish; timezone is Europe/Istanbul.
- Keep this project static and lightweight unless the user explicitly requests a framework or build system.
- Before editing, inspect the relevant HTML page and reuse its existing design language, responsive layout, typography, and interaction patterns.
- Maintain mobile responsiveness, semantic HTML, accessible labels, useful alt text, and working navigation.
- Avoid adding dependencies, trackers, external assets, or forms that do not work without explicit need.
- Do not copy business-specific content from one demo to another unless it is intentionally shared; keep each demo internally consistent.
- Never add secrets, private contact data, or credentials. Do not overwrite unrelated content.
- Do not claim browser testing or accessibility checks were completed unless actually performed.

## Validation
- Check HTML structure, links, image paths, metadata, and responsive behavior in the modified page.
- If browser tooling is unavailable, say that validation was by source inspection only.
- Review the final diff before committing.
