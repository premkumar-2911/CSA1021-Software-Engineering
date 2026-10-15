# PREOX GO

A polished, responsive bus-ticket booking prototype built for a Software Engineering laboratory assignment. It demonstrates a complete client-side journey from route search through a printable booking confirmation.

## Features

- Responsive premium travel-tech homepage
- Route search with date, passenger, and swap controls
- Client-side bus type, departure, and price filters
- Interactive seat map with live fare calculation
- Validated passenger form with in-session demo data only
- Generated booking reference and printable digital ticket
- Accessible focus states, semantic labels, reduced-motion support, and mobile layouts

## Run locally

Requirements: Node.js 22 and pnpm 10 (see `.mise.toml`).

```bash
pnpm install
pnpm dev
```

Create a production build with:

```bash
pnpm build
```

## Technology

React 19, TypeScript, Vite 8, and Tailwind CSS 4. The experience uses CSS animations rather than an additional animation dependency.

## Important

PREOX GO is a demonstration prototype. It does not connect to a backend, process payments, send personal data, or create real bus reservations. The hero photograph is provided by [Juan Encalada on Unsplash](https://unsplash.com/@juanencalada).
