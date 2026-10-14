# Astro project

- Pages are `.astro` (or `.md`/`.mdx`) files in `src/pages`; the file path is the route. Shared chrome goes in `src/layouts/Layout.astro`.
- Ship HTML, not JavaScript. Write sections as `.astro` components. Use a React component only where something must be interactive, and hydrate it with the lightest directive that works (`client:visible` or `client:idle` before `client:load`). shadcn/ui components are React: static ones render to HTML without a directive.
- Long-form content (posts, docs, changelogs) belongs in a content collection under `src/content` with a schema in `src/content.config.ts`, not in hard-coded arrays.
- Theme tokens are CSS variables in `src/styles/global.css`; build from them.
- Docs: https://docs.astro.build (routing, components, framework components, content collections, styling).
