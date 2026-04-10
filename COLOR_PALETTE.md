# Eleven Dev — Color Palette

## Core Colors

| Role | Hex | RGB | Tailwind Class | Usage |
|------|-----|-----|----------------|-------|
| Background | `#03091a` | `3, 9, 26` | `bg-[#03091a]` | Page background, nav blur base |
| White | `#ffffff` | `255, 255, 255` | `text-white` | Headings, body text, buttons |

## Brand — Blue

| Role | Hex | RGB | Tailwind Class | Usage |
|------|-----|-----|----------------|-------|
| Blue 600 | `#2563eb` | `37, 99, 235` | `bg-blue-600` | Primary buttons, CTA backgrounds |
| Blue 500 | `#3b82f6` | `59, 130, 246` | `bg-blue-500` | Button hover, glow effects, grid pattern, orbs |
| Blue 400 | `#60a5fa` | `96, 165, 250` | `text-blue-400` | Section labels, icons, gradient start, stat highlights |
| Blue 300 | `#93c5fd` | `147, 197, 253` | `text-blue-300` | Badge text, nav links, list item text |
| Blue 200 | `#bfdbfe` | `191, 219, 254` | — | — |
| Blue 100 | `#dbeafe` | `219, 234, 254` | — | Body/paragraph text (at reduced opacity) |

## Brand — Violet

| Role | Hex | RGB | Tailwind Class | Usage |
|------|-----|-----|----------------|-------|
| Violet 500 | `#8b5cf6` | `139, 92, 246` | — | Featured card bg/border, orb, section glow |
| Violet 400 | `#a78bfa` | `167, 139, 250` | — | Section labels, icons, code syntax, gradient, stat text |
| Violet 300 | `#c4b5fd` | `196, 181, 253` | — | Badge text ("Core Specialty"), list items |

## Brand — Cyan

| Role | Hex | RGB | Tailwind Class | Usage |
|------|-----|-----|----------------|-------|
| Cyan 400 | `#22d3ee` | `34, 211, 238` | — | Agentic section icons, list dots, stat text, process step |
| Cyan 300 | `#67e8f9` | `103, 232, 249` | — | Gradient endpoint, agentic list text |
| Light Blue | `#7dd3fc` | `125, 211, 252` | — | Code block string literals |

## Code Block — Syntax Highlighting

| Role | Hex | RGB | Usage |
|------|-----|-----|-------|
| Keywords | `#a78bfa` | `167, 139, 250` | `from`, `import`, `await`, `True` |
| Functions / Modules | `#60a5fa` | `96, 165, 250` | `eleven_dev`, `Agent`, `run` |
| Parameters | `#fbbf24` | `251, 191, 36` | `model`, `tools`, `memory` |
| Strings | `#7dd3fc` | `125, 211, 252` | String literals |
| Operators / Punctuation | `rgba(255,255,255,0.35)` | — | `=`, `,`, `[`, `]` |
| Identifiers | `rgba(255,255,255,0.8)` | — | Variable names |
| Comments | `rgba(255,255,255,0.3)` | — | `# comments` |

## Terminal Chrome (Code Card)

| Role | Hex | Usage |
|------|-----|-------|
| Close button | `#ff5f57` | Red dot |
| Minimize button | `#febc2e` | Yellow dot |
| Maximize button | `#3b82f6` | Blue dot (matches brand) |

## Gradients

| Name | CSS | Usage |
|------|-----|-------|
| Text Gradient | `linear-gradient(135deg, #60a5fa 0%, #a78bfa 50%, #67e8f9 100%)` | Hero headline, 404 heading |
| Text Gradient Violet | `linear-gradient(135deg, #a78bfa 0%, #60a5fa 100%)` | AI section subheading |
| Shimmer Line | `linear-gradient(90deg, transparent, rgba(59,130,246,0.55), rgba(139,92,246,0.55), transparent)` | Contact card top border |
| Violet Card Top | `linear-gradient(90deg, transparent, rgba(139,92,246,0.6), transparent)` | AI/ML featured card top edge |

## Opacity Patterns

These base colors are used throughout at varying opacities for surfaces, borders, and muted text.

### White Surfaces & Borders
| Pattern | Usage |
|---------|-------|
| `rgba(255,255,255,0.02)` | Process step card backgrounds |
| `rgba(255,255,255,0.03)` | Glass card bg, code card bg |
| `rgba(255,255,255,0.05)` | Nav border, card hover bg, section dividers |
| `rgba(255,255,255,0.06)` | Process step card borders |
| `rgba(255,255,255,0.08)` | Glass card border |
| `rgba(255,255,255,0.1)` | Ghost button border |
| `rgba(255,255,255,0.2)` | Scroll hint |
| `rgba(255,255,255,0.25)` | Copyright text |

### Blue at Opacity (base `#3b82f6` / `59,130,246`)
| Pattern | Usage |
|---------|-------|
| `rgba(59,130,246,0.04)` | Grid pattern lines |
| `rgba(59,130,246,0.08)` | Agent status block bg |
| `rgba(59,130,246,0.1)` | Badge bg, glow shadow |
| `rgba(59,130,246,0.15)` | Icon container bg, contact card bg, process steps |
| `rgba(59,130,246,0.18)` | Hero orb, agent status border |
| `rgba(59,130,246,0.2)` | Badge border, contact icon border |
| `rgba(59,130,246,0.25)` | Glass card hover border |
| `rgba(59,130,246,0.3)` | Button glow shadow |
| `rgba(59,130,246,0.45)` | Button glow hover |
| `rgba(59,130,246,0.55)` | Shimmer line |

### Violet at Opacity (base `#8b5cf6` / `139,92,246`)
| Pattern | Usage |
|---------|-------|
| `rgba(139,92,246,0.06)` | AI section radial glow |
| `rgba(139,92,246,0.07)` | Violet card bg |
| `rgba(139,92,246,0.1)` | Violet card hover bg |
| `rgba(139,92,246,0.15)` | Checkmark icon bg, process step, orb, code card glow |
| `rgba(139,92,246,0.2)` | Violet card border, "Core Specialty" badge bg, code card border |
| `rgba(139,92,246,0.55)` | Shimmer line |
| `rgba(139,92,246,0.6)` | Featured card top edge |

### Cyan at Opacity (base `#22d3ee` / `34,211,238`)
| Pattern | Usage |
|---------|-------|
| `rgba(34,211,238,0.1)` | Agentic icon bg, process step 03 |

### Blue Text at Opacity
| Pattern | Usage |
|---------|-------|
| `rgba(219,234,254,0.4)` | Stat subtitles |
| `rgba(219,234,254,0.5)` | Body paragraphs, descriptions |
| `rgba(219,234,254,0.55)` | Hero paragraph, contact paragraph |
| `rgba(147,197,253,0.4)` | Footer nav links |
| `rgba(147,197,253,0.65)` | Software dev list items |
| `rgba(147,197,253,0.7)` | Nav links |
| `rgba(196,181,253,0.7)` | AI/ML list items |
| `rgba(103,232,249,0.7)` | Agentic list items |

## Typography

| Font | Weights | Usage |
|------|---------|-------|
| Space Grotesk | 500, 600, 700, 800 | Headings (h1–h4) |
| Inter | 400, 500, 600, 700 | Body text, buttons, labels |
| SF Mono / Fira Code | — | Code block (monospace) |
