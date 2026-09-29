# Portfolio visual system

The README uses GitHub's native typography, headings, links and expandable details. No external fonts, status widgets, scripts or page CSS are required.

The header SVGs use an opaque charcoal surface (#191f24), near-white headings (#f2f5f5), neutral body text (#c4ced0) and a muted teal accent (#87cec4). All meaningful SVG text has greater than 7:1 contrast against the surface. The same opaque palette works in GitHub's light and dark themes. SVGs include a title and description; image elements have alternative text, and essential information also appears as Markdown.

The 960 × 224 desktop header switches to a 480 × 224 composition below a 480px viewport using GitHub-supported picture markup. Images use fluid widths and preserve their aspect ratio. Project README headers share this palette and composition. Keep descriptive copy and source links outside the image so it remains useful if images fail to load.

## Screenshot provenance

Screenshots are unmodified copies of existing public repository assets, not generated product mockups. They are kept locally to avoid dependence on external image hosts. Each README caption states its context and limitations.

- ModelPort: docs/screenshots/library.png at commit 146e557 in [AlBrmagawi/modelport](https://github.com/AlBrmagawi/modelport/tree/146e557).
- FirmwareLens: docs/screenshots/dashboard.png at commit df3a388 in [AlBrmagawi/FirmLens](https://github.com/AlBrmagawi/FirmLens/tree/df3a388).

Only public code, repository assets and the owner's supplied education/certifications inform the profile. Amerna is credited as the home of the earlier notebook contribution; no current employment title is asserted.

## Original rendered review

Snapshots captured on 2026-09-29 from actual public GitHub pages, before this portfolio moved to the standalone MohamedAbdelgalil repository:

- Profile: [desktop, light theme](previews/profile-desktop-light.png) · [mobile, dark theme](previews/profile-mobile-dark.png).
- ModelPort README: [before](previews/modelport-before.png) · [after](previews/modelport-after.png).
- FirmwareLens README: [before](previews/firmlens-before.png) · [after](previews/firmlens-after.png).

The profile and both project documentation branches were checked in Chromium at 1440, 390 and 320px in light and dark themes: 18 combinations. Images and internal anchors resolved; no page or README overflow occurred, including with screenshot disclosures expanded. All six SVGs parsed without clipped text or external resources. Header text contrast ratios are 15.17:1 (heading), 10.36:1 (body) and 9.23:1 (accent).

Automated WCAG A/AA checks found no violations in the profile README. Project READMEs retain GitHub's existing keyboard-focus warning for horizontally scrollable code blocks; the same warning appears on their original READMEs. Physical-device, screen-reader and Safari/Firefox checks were not performed. LinkedIn blocks automated retrieval (HTTP 999); its URL matches the owner's supplied address.

These are point-in-time captures, not live widgets. Project "after" images show the documentation pull request branches. The profile captures document the previous profile layout; this repository now presents the portfolio on its own repository page.
