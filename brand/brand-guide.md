# Cross Group digital brand guide

## Brand idea

Cross Group combines solid accounting judgement with practical advice and modern technology. The digital experience should communicate that there are capable people behind the system.

The useful tension in the brand is:

- Professional, but not stiff.
- Innovative, but not gimmicky.
- Direct, but not blunt.
- Friendly, but not fluffy.
- Commercially ambitious, but grounded in what will work.

The core positioning line is **Not your usual accountants**.

## Approved colours

| Colour | HEX | RGB | Primary use |
|---|---|---|---|
| Cross Group Navy | `#001641` | 0, 22, 65 | Navigation, headings, primary actions and structural areas |
| Cross Group Rust | `#D75532` | 215, 85, 50 | Accents, key numbers, icons and highlights |
| White | `#FFFFFF` | 255, 255, 255 | Content surfaces and text on Navy |

Recommended functional neutrals for digital interfaces:

| Token | HEX | Use |
|---|---|---|
| Background | `#F7F8FA` | Application background |
| Surface | `#FFFFFF` | Cards, modals and forms |
| Border | `#D9DEE7` | Dividers and field borders |
| Muted text | `#5B6472` | Secondary labels and help text |
| Focus ring | `#7F9BCB` | Keyboard focus indicator around Navy controls |

Navy and white have excellent contrast. Rust and white do not meet the preferred contrast for ordinary-sized text, so Rust should be treated as an accent rather than the default button background or body-text colour.

## Typography

- Main headings: Sinkin Sans 700 Bold.
- Other headings: Sinkin Sans 500 Medium.
- Body: Sinkin Sans 400 Regular.
- Web-safe fallback: Verdana.

Recommended CSS stack:

```css
font-family: "Sinkin Sans", Verdana, Geneva, sans-serif;
```

Font files are deliberately not included. Only add Sinkin Sans if Cross Group has a suitable web licence and the approved files are supplied.

## Logo rules

| Variant | Use |
|---|---|
| Primary | White or very light backgrounds |
| Reversed | Navy, dark backgrounds or dark photographs |
| Greyscale | White backgrounds where colour is unavailable |
| White | Photographs where Rust would clash |

Do not stretch, recolour, crop, distort, redraw or add effects to the logo. Preserve its aspect ratio and allow clear space around it.

## Interface direction

### Overall look

- Clean, modern and businesslike.
- White cards on a light neutral background.
- Strong Navy navigation and headings.
- Rust used in controlled flashes.
- Restrained borders, shadows and movement.
- Comfortable spacing and clear hierarchy.

### Buttons

- Primary: Navy background, white text.
- Secondary: white background, Navy text, Navy border.
- Text action: Navy text with a clear hover and focus treatment.
- Rust: reserve for an icon, accent line or prominent large number.

### Forms

- Put visible labels above fields.
- Use short examples and useful help text.
- Explain how figures are calculated.
- Place error text next to the relevant field.
- Use at least 44px-high controls for touch.

### Dashboards and financial information

- Lead with the decision the user needs to make, not a wall of charts.
- Use one primary number per summary card.
- Right-align amounts in tables.
- Show the period, currency and basis of calculation.
- Use NZD by default and New Zealand date formats.
- Explain unusual figures in plain language.

### Imagery and icons

- Prefer authentic New Zealand businesses and people over generic corporate stock photography.
- Use a consistent, simple icon family.
- Avoid novelty illustrations unless the project has a clear reason for them.
- Do not use random gradients or colourful technology imagery.

## Writing style

Use short, natural sentences and practical language. Be warm, direct and commercially aware. Help the user understand what happens next.

Good examples:

- `See what this process is really costing.`
- `Add the hours your team normally spends on this job.`
- `You could free up about 14 hours each month.`
- `Review the numbers before sending them to your adviser.`

Avoid:

- `Unlock transformational synergies through our innovative AI ecosystem.`
- Vague claims that AI will solve everything.
- Formal greetings and filler.
- American spelling.
- Excessive exclamation marks.

## Final review checklist

- The logo variant suits its background.
- Navy and Rust match the approved HEX values exactly.
- Rust is used as an accent and not for small text on white.
- Typography uses Sinkin Sans or the approved Verdana fallback.
- The interface works at 320px mobile width.
- Forms have visible labels and keyboard focus states.
- Loading, empty, success and error states exist where required.
- Financial figures show currency, period and calculation basis.
- Copy sounds practical, human and distinctly Cross Group.
- No gradients, decorative clutter or invented logo treatments have slipped in.

