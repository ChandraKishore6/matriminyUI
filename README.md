# Matrimony SaaS Premium UX/UI System

A Figma-ready design prototype for a multi-tenant matrimony SaaS platform serving users, bureau admins, and master admins.

## Deliverables included

- Desktop, tablet, and mobile layout specifications.
- Design system: colors, typography, components, and UI states.
- Component library examples: buttons, inputs, dropdowns, cards, tables, navigation, filters, alerts, modals/action panels, tabs-ready navigation patterns, and profile cards.
- Production-grade UX flows for all requested screens.
- Clickable HTML prototype connecting landing, registration, login, user dashboards, bureau admin, and master admin flows.
- Figma handoff guidance: use the sections as frames, convert repeated UI blocks into components, and map CSS custom properties to Figma color/text variables.

## Figma build notes

1. Create Figma pages named `Foundations`, `Components`, `User`, `Bureau Admin`, `Master Admin`, and `Prototype`.
2. Use the CSS variables in `styles.css` as color tokens.
3. Import the screen sections from `index.html` as design references or recreate them with Auto Layout using the documented spacing and component hierarchy.
4. Connect prototype hotspots in this order: Landing → Registration Wizard → Login → User Dashboard → Matches Listing → Match Details → Bureau Admin Pending Profiles → Profile Review → Master Admin Dashboard → Bureau Approval → Approved Bureaus.

## Local preview

Open `index.html` in a browser, or run:

```bash
python3 -m http.server 4173
```

Then visit `http://localhost:4173`.
