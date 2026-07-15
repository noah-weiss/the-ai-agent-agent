# DESIGN.md — The AI Agent Agent

Portable design tokens for theaiagentagent.com and brand assets.

## Identity

| Token | Value |
|-------|--------|
| Brand name | The AI Agent Agent |
| Domain | theaiagentagent.com |
| Short | AI Agent Agent |
| Monogram | AA |
| Tagline | Results-driven agent. One session. One change. |
| Promise | I make AI your secret weapon. |

## Metaphor

LA talent agent for AI. Not a studio. Not a big agency. One agent who gets you agentic and ships results.

## Color

| Token | Hex | Use |
|-------|-----|-----|
| `--bg` | `#0C0C0C` | Page background, dark fields |
| `--bg-elevated` | `#141414` | Cards, panels |
| `--fg` | `#F4F1EA` | Primary text (warm off-white) |
| `--muted` | `#A39E94` | Secondary text |
| `--line` | `#2A2A2A` | Borders, rules |
| `--accent` | `#C4A574` | Gold — sparingly (eyebrows, numbers, focus) |
| `--accent-soft` | `#8A734F` | Dim gold for subtle marks |
| `--on-light` | `#0C0C0C` | Text on light fields |
| `--paper` | `#F4F1EA` | Light mode / print reverse |
| `--ink` | `#0C0C0C` | Print primary |

Rules:
- Dark is default.
- Gold is garnish, not wallpaper.
- Never pure pure-white `#FFFFFF` as body text on dark (too cold).
- Never neon AI purple/cyan.

## Type

| Role | Family | Fallback | Notes |
|------|--------|----------|-------|
| Display | Cormorant Garamond | Georgia, serif | Headlines, wordmark energy |
| Body | IBM Plex Sans | system-ui, sans-serif | UI, body, UI buttons |
| Mono (rare) | IBM Plex Mono | ui-monospace | Session codes, technical footnotes only |

Scale (web):
- Display XL: clamp(2.6rem, 7.5vw, 4.6rem) / 0.98 lh / -0.02 tracking
- H2: clamp(1.8rem, 4vw, 2.35rem)
- Body: 1.05rem / 1.55
- Small: 0.9rem
- Eyebrow: 0.72rem / 0.14em tracking / uppercase / accent

## Spacing

Base unit: 4px  
Section vertical: 3.25–4.5rem  
Card pad: 1.25–1.4rem  
Max content width: 880px  
Hero max pitch width: 36rem

## Logo system

1. **Monogram AA** — primary mark for avatars, favicon, app icons
2. **Wordmark** — “The AI Agent Agent” in display serif
3. **Lockup** — monogram + wordmark + optional tagline
4. **Domain line** — theaiagentagent.com in body sans, muted

Clear space: minimum monogram height of padding around mark.  
Minimum monogram size: 24px digital, 0.35" print.  
Do not stretch. Do not outline in rainbow. Do not put on busy photo without scrim.

## Motion / tone (non-visual)

- Fast responses (operational brand)
- Short lines on the page
- Results over theater
- Hospitality under the hood: the excess that didn’t have to happen

## Do not

- Gradient mesh AI clichés
- Robot mascots
- Stock handshake photos
- “Powered by AI” badges
- Em dashes in copy
- Cheerful startup pastels
