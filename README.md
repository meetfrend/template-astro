# Astro starter

The base for new [Frend](https://github.com/meetfrend) content sites: Astro, TypeScript, Tailwind CSS v4, MDX and shadcn/ui as React islands.

```bash
pnpm install
pnpm dev
```

| Script | What it does |
| --- | --- |
| `pnpm dev` | Dev server with hot reload |
| `pnpm build` | Typecheck and build static HTML into `dist/` |
| `pnpm typecheck` | `astro check` |
| `pnpm lint` | oxlint |

Pages live in `src/pages`, layouts in `src/layouts`. Theme tokens live in `src/styles/global.css`. `@/` points to `src/`. Add components with `pnpm dlx shadcn@latest add <name>`.
