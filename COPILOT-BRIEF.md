# GitHub Copilot implementation brief

Build and refine this React + TypeScript landing page for Nigiri.Finance. The project already contains the complete first implementation and local assets.

## Product direction

Nigiri is a curated private-markets platform focused on real assets and private companies in Latin America. The experience should feel editorial, selective and quietly exclusive—not like a crypto exchange, trading dashboard or generic SaaS marketplace.

## Non-negotiable design rules

- Preserve identical content, opportunity imagery and structure in light and dark mode.
- Theme switching may change only colors, borders, shadows and image treatment.
- Maintain 35–45% negative space in major desktop sections.
- Show only two featured opportunities on the homepage.
- Use one dominant visual idea per viewport and no consecutive dense grids.
- Keep particles and decorative glow extremely restrained.
- Avoid invented investment returns, regulatory claims, scarcity or status labels.
- All navigation, buttons and theme controls must remain keyboard-accessible.
- Preserve the user's theme choice in localStorage and respect system preference initially.
- Keep responsive layouts clean at 1440px, 1024px, 768px and 390px.

## Page order

1. Header
2. Discovery-led hero and featured Pacific Boutique Hotel dossier
3. Two featured opportunities
4. Why Latin America editorial thesis
5. Selected / Structured / Monitored
6. Discover / Understand / Invest / Track
7. More, Together philosophy moment
8. Request Access CTA
9. Footer and risk disclosure

## Content and compliance

All project names, locations, statuses, investment structures and legal links are illustrative until Nigiri approves them. Do not add financial performance claims. Replace placeholder hash links with real routes before production.

## Assets

- `public/assets/pitaya-farm.png`
- `public/assets/pacific-hotel.png`
- `public/assets/latin-america-agave.png`
- `public/assets/nigiri-mascot.png`
- `public/reference/homepage-light.png`
- `public/reference/homepage-dark.png`

Use the reference images for direction only; implement the page with semantic HTML and CSS rather than embedding a screenshot.

## Suggested Copilot prompt

> Review `COPILOT-BRIEF.md`, `src/main.tsx`, and `src/styles.css`. Preserve the visual direction and content rules. Improve the implementation in small, reviewable changes. Keep TypeScript strict, avoid unnecessary dependencies, preserve accessibility and responsive behavior, and never invent investment data or compliance claims. Before changing a section, explain which design rule the change supports.
