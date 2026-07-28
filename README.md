# Choshim Wei · AI Native iOS Engineer

Personal portfolio and product website for **Choshim Wei**—AI Native iOS Engineer, Product Builder, and System Architect.

The homepage presents engineering experience across Apple platforms, professional lighting systems, connected-device protocols, AI-native development workflows, open source, and independent products.

## Homepage

`index.html` is a responsive, single-page portfolio containing:

- Hero and system architecture overview
- Engineering experience metrics
- Apple Platform, Connected Systems, and AI Native Engineering domains
- Featured professional, open-source, and personal projects
- AI-assisted software production workflow
- About and contact sections

The visual system uses a dark, glass-inspired interface with responsive desktop and mobile layouts.

## Products

### NoctiBeat

HealthKit-based sleep intelligence and recovery insights.

- Website: `/apps/noctibeat/index.html`
- Privacy: `/apps/noctibeat/privacy.html`
- App Store: https://apps.apple.com/cn/app/%E5%A4%9C%E5%BE%8B/id6758320663

### Equation Studio

Interactive 2D and 3D mathematics visualization, currently stored under the existing `formulavis` path.

- Website: `/apps/formulavis/index.html`
- Privacy: `/apps/formulavis/privacy.html`
- Formula library: `/apps/formulavis/data/formula_library.json`

## Repository Structure

```text
.
├── index.html                 # Personal portfolio homepage
├── app-ads.txt                # App advertising declaration
└── apps/
    ├── noctibeat/             # NoctiBeat website and privacy policy
    └── formulavis/            # Equation Studio website, privacy policy, and data
```

## Local Preview

The site is static and can be opened directly or served locally:

```bash
python3 -m http.server 4173
```

Then visit `http://127.0.0.1:4173/`.

## Deployment

The `main` branch is published through GitHub Pages at:

https://choshimwy.github.io/

## Contact

- Email: choshim.wei@gmail.com
- GitHub: https://github.com/ChoshimWy
