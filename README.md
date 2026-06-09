# HubSpot Theme Boilerplate

A starter HubSpot theme boilerplate with a simple layout, global partials, and a sample custom module.

## Included structure

- `theme.json` — theme configuration
- `templates/` — page templates
- `partials/` — global header/footer
- `css/` — stylesheet
- `js/` — site JavaScript
- `modules/` — sample custom HubL module

## Getting started

1. Install HubSpot CLI (optional):
   ```bash
   npm install -g @hubspot/cli
   ```

2. Install local dependencies:
   ```bash
   npm install
   ```

3. Use the HubSpot CLI to upload or watch the theme:
   ```bash
   hs watch --portal=<PORTAL_ID> --theme-path=./
   ```

## Notes

- Replace `PORTAL_ID` with your HubSpot account portal ID.
- Customize templates, modules, styles, and scripts as needed.
