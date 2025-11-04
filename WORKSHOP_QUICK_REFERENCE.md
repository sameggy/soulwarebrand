# The Workshop: Quick Reference Guide

**Brand Direction**: Artisan Craft Meets Digital Precision

---

## At a Glance

### Brand Essence
Boutique digital studio that treats code as craft and designs as blueprints. Every pixel placed with artisan care, every interaction engineered with digital precision.

### Tagline
**"Craft × Code"**

### Voice in Three Words
Confident · Precise · Warm

---

## Colors

### Primary Palette

| Color Name | Hex | RGB | Usage |
|------------|-----|-----|-------|
| **Foundry Charcoal** | `#2B2D2F` | 43, 45, 47 | Primary backgrounds, text (60%) |
| **Brass Patina** | `#D4AF37` | 212, 175, 55 | Accent, highlights, CTAs (20%) |
| **Blueprint Blue** | `#4A90E2` | 74, 144, 226 | Technical elements, links (10%) |
| **Workshop White** | `#F8F9FA` | 248, 249, 250 | Negative space, light backgrounds (10%) |

### Supporting Colors

| Color Name | Hex | RGB | Usage |
|------------|-----|-----|-------|
| **Oxidized Copper** | `#6B4423` | 107, 68, 35 | Warmth, heritage |
| **Steel Gray** | `#71797E` | 113, 121, 126 | Secondary text, borders |
| **Sawdust Cream** | `#E8DCC4` | 232, 220, 196 | Warm backgrounds |
| **Oil Black** | `#1A1A1A` | 26, 26, 26 | Maximum contrast |

### CSS Variables

```css
:root {
  --foundry-charcoal: #2B2D2F;
  --brass-patina: #D4AF37;
  --blueprint-blue: #4A90E2;
  --workshop-white: #F8F9FA;
  --steel-gray: #71797E;
}
```

---

## Typography

### Font Stack

1. **IBM Plex Mono** - Headings, technical content
   - Weights: 300, 400, 500, 600
   - `font-family: 'IBM Plex Mono', 'Courier New', monospace;`

2. **Inter** - Body copy, UI elements
   - Weights: 400, 500, 600
   - `font-family: 'Inter', sans-serif;`

3. **Playfair Display** - Special headlines (sparingly)
   - Weights: 400, 600, 700
   - `font-family: 'Playfair Display', Georgia, serif;`

### Type Scale (Desktop)

```
Hero: 72px / Playfair Display Bold
H1: 48px / IBM Plex Mono SemiBold
H2: 36px / IBM Plex Mono SemiBold
H3: 24px / IBM Plex Mono Medium
Body: 16px / Inter Regular
Small: 14px / Inter Regular
```

---

## Logo & Mark

**Primary Logo**: "The Workshop Anvil"
- Minimalist anvil shape from geometric lines
- Negative space forms "W"
- Blueprint grid on top surface

**Wordmark**: "THE WORKSHOP" in IBM Plex Mono Medium
- Letter spacing: +0.05em

---

## Design Principles

### Grid System
- **8-point grid**: All spacing in multiples of 8px
- **Columns**: 12 (desktop), 8 (tablet), 4 (mobile)
- **Max width**: 1280px

### Corner Radius
```css
--radius-minimal: 2px;   /* Most UI */
--radius-small: 4px;     /* Cards */
--radius-medium: 8px;    /* Larger components */
```

### Shadows
```css
/* Card elevation */
box-shadow: 0 2px 4px rgba(26, 26, 26, 0.08),
            0 4px 8px rgba(26, 26, 26, 0.08);

/* Brass glow */
box-shadow: 0 0 20px rgba(212, 175, 55, 0.3);
```

---

## Visual Elements

### Icons
- **Style**: Outlined, geometric
- **Stroke**: 2px
- **Grid**: 24×24px
- **Themes**: Tools, materials, processes

### Photography
- **Subject**: Hands, tools, materials, workspaces
- **Treatment**: Warm shadows, cool highlights
- **Lighting**: Directional, workshop-style
- **Composition**: Rule of thirds, selective focus

### Patterns
- **Blueprint Grid**: 20×20px, Brass @ 10% opacity
- **Textures**: Brushed metal, wood grain, leather (5-15% opacity)

---

## Animation

### Timing
```css
--ease-workshop: cubic-bezier(0.4, 0.0, 0.2, 1);
--duration-fast: 200ms;
--duration-normal: 300ms;
```

### Types
- **Assembly**: Elements build from components
- **Precision Snap**: Lock into grid positions
- **Blueprint Draw**: Stroke animation reveals

---

## Brand Voice

### DO Say
✓ Build, craft, forge, assemble
✓ Precise, meticulous, intentional
✓ Foundation, structure, blueprint
✓ Active voice, specific details

### DON'T Say
✗ Disruptive, revolutionary, game-changing
✗ Very, really, amazing, incredible
✗ Leverage, synergy, paradigm
✗ Passive voice, vague claims

### Example Sentences
- "We build digital products with the precision of master craftspeople."
- "Every line of code is placed with intention."
- "Like a carpenter choosing the right joint, we select the right technology."

---

## Messaging Pillars

1. **Craft Meets Code**: Artisan attention to every line
2. **Precision Engineering**: Deliberate, exact, intentional
3. **Built to Last**: Foundations for future growth
4. **Human-Centered**: Technology serves people

---

## Button Styles

### Primary Button
```css
background: linear-gradient(135deg, #D4AF37, #B8860B);
color: #2B2D2F;
font: 500 16px 'IBM Plex Mono';
padding: 12px 32px;
border-radius: 2px;
```

### Secondary Button
```css
background: transparent;
color: #D4AF37;
border: 2px solid #D4AF37;
padding: 12px 32px;
border-radius: 2px;
```

---

## Common Components

### Card
```css
background: rgba(248, 249, 250, 0.05);
border: 1px solid rgba(113, 121, 126, 0.2);
border-radius: 4px;
padding: 32px;
```

### Input Field
```css
border: 1px solid rgba(113, 121, 126, 0.6);
border-radius: 2px;
padding: 12px 16px;
font: 400 16px 'Inter';

&:focus {
  border: 2px solid #4A90E2;
}
```

---

## Dos and Don'ts

### Visual Design

**DO**:
✓ Use 8-point grid for all layouts
✓ Combine craft imagery with technical precision
✓ Keep compositions clean but characterful
✓ Use textures subtly (5-15% opacity)
✓ Maintain typography hierarchy
✓ Use brass accents sparingly

**DON'T**:
✗ Use rounded, soft shapes
✗ Overuse textures or patterns
✗ Mix warm/cool carelessly
✗ Use script or decorative fonts
✗ Create cluttered layouts
✗ Ignore the grid system

---

## Contact Info Template

```
[Name]
[Title] | The Workshop

[Email] | [Phone]
Craft × Code
```

---

## File Organization

```
THE_WORKSHOP_BRANDING_UNIVERSE.md - Complete brand strategy
WORKSHOP_COLOR_SYSTEM.md - Color specifications
WORKSHOP_DESIGN_ELEMENTS.md - Typography, icons, layout
WORKSHOP_BRAND_VOICE.md - Writing guidelines
WORKSHOP_QUICK_REFERENCE.md - This file
```

---

## Implementation Checklist

Start here for new projects:

- [ ] Set up color variables
- [ ] Import font families (IBM Plex Mono, Inter)
- [ ] Establish 8-point grid system
- [ ] Create base component styles
- [ ] Define shadow system
- [ ] Set up animation timing functions
- [ ] Create icon library
- [ ] Establish typography scale
- [ ] Define spacing system
- [ ] Create pattern/texture assets

---

## Quick Decision Guide

**"Should I use this color?"**
→ Does it fit the primary or supporting palette? Is it WCAG AA compliant?

**"Is this typography hierarchy correct?"**
→ Are you using IBM Plex Mono for headings, Inter for body?

**"Is this spacing right?"**
→ Is it a multiple of 8px?

**"Does this animation feel right?"**
→ Is it 200-400ms with cubic-bezier(0.4, 0.0, 0.2, 1)?

**"Is this copy on-brand?"**
→ Is it confident, precise, and warm? Does it avoid buzzwords?

**"Should I add this texture?"**
→ Is it at 5-15% opacity? Does it enhance without overwhelming?

---

## Brand in One Sentence

**"The Workshop builds digital products with the meticulous care of master craftspeople and the precision of modern engineers—where every pixel is intentional and every interaction is engineered to last."**

---

## Resources

### Fonts
- IBM Plex Mono: https://fonts.google.com/specimen/IBM+Plex+Mono
- Inter: https://fonts.google.com/specimen/Inter
- Playfair Display: https://fonts.google.com/specimen/Playfair+Display

### Color Tools
- Contrast Checker: https://webaim.org/resources/contrastchecker/
- Color Palette: Coolors, Adobe Color

### Design Tools
- Figma (design system)
- 8-point Grid plugin
- Icon libraries (Feather, Heroicons - as reference)

---

**Version**: 1.0
**Last Updated**: November 4, 2025

*Keep this reference handy. When in doubt, check here first.*
