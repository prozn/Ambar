# Copilot Instructions For This Repository

## Overview

This project is a two-page static website for Ambar Fogue's teaching services. It is designed for GitHub Pages hosting with a custom domain and currently uses plain HTML, CSS, and static assets only.

## Repo Facts

- `index.html` contains the homepage structure and site copy.
- `cv.html` contains the curriculum vitae page.
- `styles.css` contains the visual system, layout, and responsive behavior.
- `assets/` contains the logo placeholder and other static assets.
- The site is aimed at parents of young children, especially under 7.
- The design direction is fun, playful, light, and professional.

## Editing Guidance

- Keep changes minimal and local to the requested behavior.
- Maintain semantic HTML and preserve HTML validity.
- Keep the site framework-free unless the user explicitly requests a different stack.
- Preserve relative paths for GitHub Pages compatibility.
- Use email as the only contact method unless the user says otherwise.
- Keep the services section as the main body focus.
- Keep service cards as full pastel panels with no numeric badges.
- Keep the approach cards in a single row on larger screens and stacked on smaller screens.
- Keep the CV as a proper HTML page, not a downloadable PDF, unless the user explicitly changes direction.

## Content Guidance

- Prefer calm, parent-facing copy.
- Use wording that feels warm, experienced, and trustworthy.
- Avoid generic marketing language when a specific educational tone is more appropriate.
- Preserve existing content decisions unless the user asks to change them.

## Validation Guidance

- After editing HTML, run `npx html-validate index.html cv.html; Write-Output "exit:$LASTEXITCODE"`.
- After layout changes, verify the result still works at mobile widths.
- Do not introduce invalid ARIA attributes or unnecessary decorative markup.