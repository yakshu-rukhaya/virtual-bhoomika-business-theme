# Virtual Bhoomika Business Theme

A lightweight, CSS-first green-and-white business theme for ERPNext/Frappe v15. It styles the existing Desk interface for a professional business environment without replacing ERPNext functionality or requiring a JavaScript build pipeline.

## Branding

- Primary green: `#00BF63`
- Deep green: `#008F4C`
- Soft green: `#EAF9F1`
- White surfaces and charcoal text
- Accessible focus indicators and restrained status colours

## Includes

- ERPNext Desk navigation, sidebar, cards, list views and form controls
- Buttons, links, tabs, badges and status indicators
- Business-oriented visual styling for analytics, operations, marketing, finance, taxation, compliance, branding and technology
- A sample Business Hub module folder for future workspace expansion

## Compatibility

Designed for Frappe Framework / ERPNext v15. It uses `app_include_css` and a static stylesheet; no Node packages, custom esbuild entrypoints, or runtime dependencies are required.

## Installation

1. Create a new **empty GitHub repository** named `virtual-bhoomika-business-theme`.
2. Upload the contents of this repository (the files inside this folder, not the enclosing ZIP folder) to its default branch.
3. Add the repository to Frappe Cloud as a custom app and build it on a Frappe v15 site.
4. Install the app on a test site first.
5. After installation, hard-refresh the browser to reload assets.

## Important

This is a visual theme, not an implementation of accounting, tax, compliance, marketing automation, or analytics features. Those business functions must be configured or developed separately in ERPNext. Test on a staging site before production deployment.
