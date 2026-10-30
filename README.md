# Sealos landing page

Responsive React + Vite implementation based on the supplied Figma CSS export. Uses locally bundled Geist fonts and Lucide icons.

## Development

Requires Node.js 22.12+ (validated on Node.js 24).

```sh
cd /workspace/sealos.io-landing-page-1
npm ci --cache /workspace/.npm-cache --no-audit --no-fund
npm run dev -- --port 5173
```

```sh
npm run build
npm run preview -- --port 4173
```

## Implementation

- Hero, workflow cards, comparison table, stack canvas, operations dashboard, deployment capabilities, FAQ, credit CTA, and footer.
- Interactive stack tabs, canvas service selection, logs/metrics tabs, FAQ, mobile navigation, page search, and a three-step product tour.
- Dashboard content and deployment approvals are client-side demonstrations, with no cloud operations or backend integration.
- Download links lead to the upstream Sealos releases page. Verify official product destinations before publication.
- The CSS export references images that were not supplied. Product screenshots, background glass artwork, brand marks, and the gift illustration are represented by recreated components, icons, and CSS. A source screenshot and exported assets are needed for visual fidelity review.
- FAQ answers beyond the first item were written from the supplied feature descriptions because the export contains only their questions. Review product claims and welcome-credit terms before publication.
- The demo CTA opens an interactive tour; no original demo video was supplied.

## Validation

Production build passed. Chromium smoke checks passed for section rendering, stack switching, metrics, FAQ, search, modal tour, sample approval, and mobile navigation. No horizontal page overflow at 390, 768, 1024, and 1440 pixels; no runtime page errors during the smoke checks. Original Figma visuals could not be compared because access was unavailable.
