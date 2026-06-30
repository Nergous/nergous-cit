# Changelog

All notable changes to the nergous-cit design system are documented here.
The project loosely follows [Semantic Versioning](https://semver.org/).

## v1.0.0 — 2026-06-30

Initial release as a standalone repository (snapshot-distribution model).

First public cut of the nergous-cit Vue 3 design system, extracted from the
`laravel-template-admin` project:

- Themeable & density-aware design tokens (`styles/tokens.css`).
- 40 components across primitives, forms, data-display, feedback, overlays and
  navigation (including the admin-shell set: `NSidebar`, `NTopbar`, `NDataTable`,
  `NCommandPalette`, `NWizard`, `NAnchoredForm`).
- Composables: `useTheme`, `useToast`, `useScrollSpy`.
- Locale-agnostic formatting helpers (`createFormat`, `toDate`).
- Bundled Manrope + JetBrains Mono subsets.
