# Pet Care Plus

A warm, friendly Astro website for a fictional pet care company offering dog walking,
grooming, boarding, pet sitting, and puppy training.

## Start locally

Use Node.js 22.23.4 or newer and pnpm 12.18.0.

```bash
pnpm install
pnpm dev
```

Open the local address printed by Astro.

```bash
pnpm check
pnpm build
pnpm preview
```

## Pages

| Route | Source |
| --- | --- |
| `/` | Home and pet care overview |
| `/ecommerce/` | Pet essentials shop and shopping bag |
| `/portfolio/` | Pet care services and filters |
| `/dashboard/` | Business overview retained for internal use |

The shared page shell lives in `src/Starter.astro`. Page-specific content lives under
`src/components/`, and theme behavior is controlled by `src/scripts/theme.ts`.

## Themes

The header includes Harbor, Studio, Paper, Field, Glass, Santi020k, and the Pet Care Plus theme.
Harbor is the default. The theme control supports light and dark modes, and preferences persist
when browser storage is available.
