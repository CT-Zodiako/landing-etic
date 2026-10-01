# Astro migration

## Goal
Move the existing self-contained ETIC landing into a maintainable Astro project while preserving its visual design and interactions.

## Tasks
- [x] Create Astro project configuration and package scripts.
- [x] Move the landing markup into an Astro page with local styles/scripts/assets as needed.
- [x] Verify build output and key landing interactions.

## Acceptance criteria
- `npm run build` succeeds.
- The root page renders the existing ETIC landing content.
- Responsive navigation, modules, animations, and contact behavior remain available.

## Non-goals
- No backend or CMS implementation yet.
- No visual redesign in this migration.
