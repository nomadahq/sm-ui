# Brand Packages — Usage Guide

Each product directory contains the complete brand package:

    icon.svg / icon-inverted.svg          — vector source
    icon-512.png / icon-512-inverted.png  — Slack, social
    icon-192.png / icon-180.png           — PWA, Apple touch
    favicon-32.png                        — marketing sites
    favicon-32-admin.png                  — ALL portals (inverted/high-contrast)
    favicon.ico / favicon-admin.ico       — ICO format
    favicon.svg / favicon-admin.svg       — SVG format
    horizontal-{name}.png                 — lockup, light bg (SSO + nav)
    horizontal-{name}-dark.png            — lockup, dark bg
    horizontal-{name}-inverted.png        — lockup, inverted
    horizontal-{name}-inverted-dark.png   — lockup, inverted + dark bg
    og-{name}.png / og-{name}-inverted.png — social sharing
    brand.json                            — colors, CSS vars, font config

## Key rules

1. ALL portals use `favicon-32-admin.png` as their favicon (inverted/high-contrast)
2. Marketing sites (sprintmode.ai) use `favicon-32.png` (normal)
3. SSO login pages use `horizontal-{name}.png` at height="32" via <picture>
4. Never render icon + text separately — always use the pre-built lockup PNG
5. Dark mode: <picture> with -dark.png source for prefers-color-scheme: dark

Full guide with per-product file paths: docs/ui/brand-usage.md
