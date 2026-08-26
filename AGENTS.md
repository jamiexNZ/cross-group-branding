# Cross Group build instructions

Apply these rules to every interface, document and piece of copy created from this repository.

## Brand

- Cross Group is a New Zealand accounting and business advisory firm.
- The positioning line is "Not your usual accountants".
- The tone is practical, commercially aware, technology-forward and human.
- Use New Zealand/British English and sentence case.
- Write in short, conversational, direct sentences. Avoid hype, jargon and vague AI claims.

## Visual system

- Use Cross Group Navy `#001641` as the dominant colour.
- Use Cross Group Rust `#D75532` sparingly for accents, icons, rules and large key figures.
- Use white `#FFFFFF` for content surfaces and text on Navy.
- Use `#F7F8FA` for the application background, `#D9DEE7` for borders and `#5B6472` for secondary text.
- Preferred font: Sinkin Sans. Safe fallback: Verdana, then Geneva, sans-serif.
- Do not fetch, invent or embed font files unless approved licensed files are supplied.
- Do not use gradients, glassmorphism, heavy shadows, random accent colours or decorative clutter.

## Logos

- Use the SVG files in `assets/logos`.
- Primary: white or very light backgrounds.
- Reversed: Navy or dark backgrounds.
- Greyscale: white backgrounds where colour is unavailable.
- White: photographs where Rust would clash.
- Never stretch, recolour, crop, distort, redraw or add effects to a logo.
- Preserve the aspect ratio and clear space. Do not replace the logo with styled text.

## Interface rules

- Use generous whitespace, a restrained 8px spacing rhythm, approximately 1200px maximum content width and 10px radii.
- Primary buttons are Navy with white text. Secondary buttons are white with Navy text and border.
- Do not use white text on Rust for ordinary-sized text or Rust body text on white.
- Give every form control a visible label, useful validation and a keyboard-visible focus state.
- Make touch targets at least 44px high.
- Design mobile-first and verify layouts at 320px wide.
- Aim for WCAG 2.2 AA. Never use colour as the only status signal.
- Include loading, empty, success and error states for data-driven features.
- Use NZD by default and New Zealand date formats. State the period and calculation basis for financial figures.

## Engineering

- Reuse `tokens/design-tokens.css` or map the same values into the existing theme.
- Prefer TypeScript with strict typing and reusable accessible components.
- Keep business logic separate from display components.
- Preserve existing working behaviour when applying brand changes.
- Never place secrets, credentials or client data in frontend code or this public repository.
- For personal or financial data, define authentication, permissions, audit history, retention and backups before implementation.

Before finishing, compare the result with `brand/brand-guide.md` and check colour accuracy, typography, logo choice, contrast, responsive layout, keyboard use and all important states.
