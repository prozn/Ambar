# AGENTS.md

This repository contains a two-page static website for Ambar Fogue's teaching services.

## Project Snapshot

- Hosting target: GitHub Pages with a custom domain
- Stack: plain HTML, CSS, and static assets
- Main files: `index.html`, `cv.html`, `styles.css`, `assets/`
- Audience: parents seeking support for children under 7
- Tone: playful, light, warm, and professional, with a cleaner contemporary school-brand presentation

## Working Rules For Agents

- Keep the project build-free unless the user explicitly asks for tooling.
- Preserve GitHub Pages compatibility and use only relative paths for assets and links.
- Prefer semantic HTML and accessible markup.
- Keep `index.html` valid under `html-validate`.
- Make focused edits and avoid broad visual rewrites unless requested.
- Do not add JavaScript unless there is a clear user-facing need.

## Current Site Structure

- The homepage hero section contains the logo, centred brand name, CV link, email contact, intro copy, and CTAs.
- The services section is the main body content.
- Service cards use restrained coloured header accents and do not display numeric labels.
- The approach section contains three cards in a single row on larger screens.
- Contact is email-only.
- There is no bottom contact section.
- The CV is a dedicated second page at `cv.html`, not a PDF download.
- The CV page uses a compact Back to Home utility link above the header and does not show the email address.

## Content And Design Constraints

- Keep the voice parent-facing and grounded in trust, warmth, and child development.
- Preserve the playful-professional balance while keeping the current cleaner, more structured option 3 presentation.
- Do not reintroduce phone numbers unless the user asks.
- Do not reintroduce removed sections or labels unless requested.
- Prefer small, legible content blocks and mobile-safe spacing.

## Common Edit Targets

- Update homepage content in `index.html`.
- Update CV content in `cv.html`.
- Update visual design and responsive layout in `styles.css`.
- Update live assets in `assets/` when replacements are provided.
- Add `CNAME` only when the final custom domain is known.

## Validation

- Run `npx html-validate index.html cv.html; Write-Output "exit:$LASTEXITCODE"` after HTML changes.
- Check responsive layout after structural or spacing updates.
- Keep assets and links relative for static hosting.

## Avoid

- Adding frameworks, package tooling, or build pipelines without explicit approval
- Adding backend forms, analytics, or booking systems without a request
- Converting the site to a multi-page structure unless the scope changes