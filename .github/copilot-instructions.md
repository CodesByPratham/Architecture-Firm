# Copilot Instructions for Architect MVP

## Project Overview
This workspace is a small static website MVP for an architectural firm. The two main landing pages are:
- `home-branding-agency.html`
- `home-design-agency.html`

The site uses existing CSS and page structure to define the visual identity. When making changes, the priority is to reuse the existing CSS rather than creating new design systems.

## Important files
- `home-branding-agency.html`
- `home-design-agency.html`
- `css/style.css`
- `css/responsive.css`
- `css/theme-vendors.min.css`
- `css/font-icons.min.css`

## How to help
- Use the two landing pages as primary templates for layout, spacing, typography, and page patterns.
- Reuse CSS classes from `css/style.css` and `css/responsive.css` wherever possible.
- Keep the navigation/header structure simple and consistent across pages.
- Preserve the existing responsive behavior and mobile menu styling.
- Avoid adding new frontend frameworks, libraries, or duplicate CSS files.

## When to ask for clarification
- If a requested change requires a new page type or a major layout redesign.
- If the CSS needed for a change does not already exist and must be added.
- If the user wants a visual style that conflicts with the current branding or layout patterns.

## Example prompts
- "Update `home-design-agency.html` to use the same single-level navbar as `home-branding-agency.html`."
- "Reuse the existing card/grid CSS from `home-branding-agency.html` in a new services section."
- "Keep existing button and heading styles when adjusting this landing page content."
