# Cross Group branding

The shared digital brand package for Cross Group websites, calculators and applications. It gives Lovable, Codex and other development tools one reliable source for colours, typography, logo use, interface styling and writing tone.

## Quick start

### Lovable

1. Open **Settings > Knowledge** in your Lovable workspace.
2. Paste the full contents of [`lovable/workspace-knowledge.txt`](lovable/workspace-knowledge.txt) into Workspace knowledge.
3. Start a project in Plan mode with [`lovable/project-starter-prompt.txt`](lovable/project-starter-prompt.txt), replacing the bracketed sections.
4. Upload the appropriate SVG from [`assets/logos`](assets/logos).
5. Ask Lovable to use [`tokens/design-tokens.css`](tokens/design-tokens.css), or map the same values into the project's existing theme.
6. Before publishing, review the result against [`brand/brand-guide.md`](brand/brand-guide.md).

### Codex and other coding agents

Copy [`AGENTS.md`](AGENTS.md) into the root of the project, or point the agent to this repository. The file contains the non-negotiable brand, accessibility and implementation rules.

## Core brand

| Item | Standard |
|---|---|
| Navy | `#001641` |
| Rust | `#D75532` |
| White | `#FFFFFF` |
| Preferred font | Sinkin Sans |
| Fallback font | Verdana |
| Positioning line | Not your usual accountants |
| Language | New Zealand/British English |

Use Rust as an accent. Use Navy with white text for primary buttons and strong structural areas.

## Logo choice

- `cross-group-logo-primary.svg`: white or very light backgrounds.
- `cross-group-logo-reversed.svg`: Navy, dark backgrounds or dark photographs.
- `cross-group-logo-greyscale.svg`: white backgrounds where colour is unavailable.
- `cross-group-logo-white.svg`: photographs where Rust would clash.

Never stretch, recolour, crop, distort, recreate or add effects to the logos.

## Repository structure

- `AGENTS.md`: instructions for coding agents.
- `assets/logos`: web-ready SVG logo variants.
- `brand/brand-guide.md`: detailed brand and writing guidance.
- `examples/ui-preview.html`: standalone visual example.
- `lovable/workspace-knowledge.txt`: text for Lovable Workspace knowledge.
- `lovable/project-starter-prompt.txt`: reusable Lovable project brief.
- `tokens/design-tokens.css`: CSS variables and basic component rules.
- `tokens/design-tokens.json`: machine-readable design values.

The approved Navy, Rust, typography and logo rules are official Cross Group standards. Spacing, radii, shadows and functional colours are restrained digital extensions for application design.

## Public repository note

This repository contains public-safe web assets and guidance only. Approved source PDFs and licensed font files are intentionally excluded. Keep credentials, client information and other confidential material out of the repository.
