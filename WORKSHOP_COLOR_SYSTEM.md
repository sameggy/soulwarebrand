# The Workshop: Color System & Visual Specifications

## Primary Color Palette

### Foundry Charcoal
**The Foundation Color**

```
HEX: #2B2D2F
RGB: 43, 45, 47
HSL: 210°, 4%, 18%
CMYK: 72, 66, 62, 73

Pantone Equivalent: Black 7 C
```

**Usage**:
- Primary backgrounds (dark mode)
- Large text blocks
- Headers and navigation bars
- Card backgrounds
- Footer sections

**Accessibility**:
- WCAG AAA with Workshop White (#F8F9FA)
- Contrast ratio: 15.8:1

---

### Brass Patina
**The Signature Accent**

```
Primary Brass:
HEX: #D4AF37
RGB: 212, 175, 55
HSL: 46°, 65%, 52%
CMYK: 18, 26, 87, 3

Pantone Equivalent: 7551 C
```

```
Deep Brass:
HEX: #B8860B
RGB: 184, 134, 11
HSL: 43°, 89%, 38%
CMYK: 25, 39, 100, 13

Pantone Equivalent: 125 C
```

**Usage**:
- Call-to-action buttons
- Interactive elements
- Accent lines and borders
- Icon highlights
- Hover states
- Navigation active states

**Accessibility**:
- Use Deep Brass (#B8860B) on light backgrounds
- Use Primary Brass (#D4AF37) on dark backgrounds
- Contrast ratio with Foundry Charcoal: 5.2:1 (AA compliant)

---

### Blueprint Blue
**The Technical Color**

```
HEX: #4A90E2
RGB: 74, 144, 226
HSL: 212°, 73%, 59%
CMYK: 67, 36, 0, 0

Pantone Equivalent: 2171 C
```

**Usage**:
- Links and hyperlinks
- Technical documentation highlights
- Data visualization
- Progress indicators
- Information badges
- Secondary interactive elements

**Accessibility**:
- Contrast ratio with Foundry Charcoal: 4.7:1 (AA compliant)
- Contrast ratio with Workshop White: 3.1:1 (use cautiously)

---

### Workshop White
**The Clean Canvas**

```
HEX: #F8F9FA
RGB: 248, 249, 250
HSL: 210°, 17%, 98%
CMYK: 1, 0, 0, 2

Pantone Equivalent: Cool Gray 1 C
```

**Usage**:
- Primary backgrounds (light mode)
- Negative space
- Text on dark backgrounds
- Card surfaces
- Clean sections

**Accessibility**:
- WCAG AAA with Foundry Charcoal
- WCAG AAA with Oil Black

---

## Supporting Color Palette

### Oxidized Copper
**Warmth & Heritage**

```
HEX: #6B4423
RGB: 107, 68, 35
HSL: 28°, 51%, 28%
CMYK: 42, 63, 84, 51

Pantone Equivalent: 1615 C
```

**Usage**:
- Warm accent areas
- Heritage content sections
- Error states (softened)
- Craft-focused imagery overlays

---

### Steel Gray
**Industrial Strength**

```
HEX: #71797E
RGB: 113, 121, 126
HSL: 203°, 5%, 47%
CMYK: 54, 43, 39, 18

Pantone Equivalent: Cool Gray 9 C
```

**Usage**:
- Secondary text (60% opacity)
- Borders and dividers
- Disabled states
- Subtle backgrounds
- Placeholder text

**Accessibility**:
- Contrast ratio with Workshop White: 4.6:1 (AA compliant)

---

### Sawdust Cream
**Organic Warmth**

```
HEX: #E8DCC4
RGB: 232, 220, 196
HSL: 40°, 44%, 84%
CMYK: 8, 11, 22, 0

Pantone Equivalent: 7527 C
```

**Usage**:
- Warm light backgrounds
- Vintage paper textures
- Section backgrounds
- Callout boxes
- Testimonial backgrounds

---

### Oil Black
**Premium Depth**

```
HEX: #1A1A1A
RGB: 26, 26, 26
HSL: 0°, 0%, 10%
CMYK: 73, 68, 66, 82

Pantone Equivalent: Black 6 C
```

**Usage**:
- Premium section backgrounds
- Maximum contrast text
- Hero sections
- High-end product showcases
- Overlay backgrounds

---

## Color Combinations

### Primary Combinations

**Combination 1: Forge & Brass**
```
Background: Foundry Charcoal (#2B2D2F)
Accent: Brass Patina (#D4AF37)
Text: Workshop White (#F8F9FA)

Use Case: Primary branding, hero sections, CTAs
```

**Combination 2: Clean Workshop**
```
Background: Workshop White (#F8F9FA)
Accent: Deep Brass (#B8860B)
Text: Foundry Charcoal (#2B2D2F)

Use Case: Content areas, forms, light sections
```

**Combination 3: Blueprint Technical**
```
Background: Foundry Charcoal (#2B2D2F)
Primary: Blueprint Blue (#4A90E2)
Secondary: Brass Patina (#D4AF37)
Text: Workshop White (#F8F9FA)

Use Case: Technical documentation, data displays
```

**Combination 4: Warm Heritage**
```
Background: Sawdust Cream (#E8DCC4)
Accent: Oxidized Copper (#6B4423)
Text: Oil Black (#1A1A1A)

Use Case: About sections, storytelling, heritage content
```

---

## Gradient Specifications

### Brass Gradient
**Metallic Depth**

```
Linear Gradient (135deg):
#D4AF37 0%
#B8860B 100%

Use Case: Buttons, premium accents, badges
```

### Charcoal Gradient
**Subtle Depth**

```
Linear Gradient (180deg):
#2B2D2F 0%
#1A1A1A 100%

Use Case: Backgrounds, headers, sections
```

### Blueprint Gradient
**Technical Glow**

```
Radial Gradient:
#4A90E2 0%
rgba(74, 144, 226, 0) 70%

Use Case: Hover effects, focus states, glows
```

---

## Opacity Scale

### Standard Opacity Values
```
100% - Primary elements
90% - Secondary elements
75% - De-emphasized content
60% - Tertiary text
40% - Disabled states
20% - Hover overlays
10% - Subtle backgrounds
5% - Texture overlays
```

---

## Color Usage Matrix

| Element Type | Light Mode | Dark Mode |
|-------------|------------|-----------|
| **Page Background** | Workshop White | Foundry Charcoal |
| **Card Background** | #FFFFFF | #323437 |
| **Primary Text** | Foundry Charcoal | Workshop White |
| **Secondary Text** | Steel Gray | Steel Gray @90% |
| **Accent** | Deep Brass | Brass Patina |
| **Links** | Blueprint Blue | Blueprint Blue |
| **Borders** | Steel Gray @40% | Steel Gray @60% |
| **Hover Background** | Brass @10% | Brass @15% |
| **Active State** | Brass Patina | Brass Patina |
| **Disabled** | Steel Gray @40% | Steel Gray @40% |

---

## Semantic Colors

### Success
```
Primary: #2D7A4F (Deep Forest Green)
Background: rgba(45, 122, 79, 0.1)
Text: Pair with Workshop White on dark, Foundry Charcoal on light
```

### Warning
```
Primary: #C87E22 (Burnished Orange)
Background: rgba(200, 126, 34, 0.1)
Text: Pair with Workshop White on dark, Foundry Charcoal on light
```

### Error
```
Primary: #A64435 (Rust Red)
Background: rgba(166, 68, 53, 0.1)
Text: Pair with Workshop White on dark, Foundry Charcoal on light
```

### Info
```
Primary: Blueprint Blue (#4A90E2)
Background: rgba(74, 144, 226, 0.1)
Text: Pair with Workshop White on dark, Foundry Charcoal on light
```

---

## Color Accessibility Guidelines

### Text Contrast Requirements

**Large Text (18px+ or 14px+ bold)**:
- Minimum contrast ratio: 3:1 (AA)
- Recommended: 4.5:1 (AAA)

**Normal Text**:
- Minimum contrast ratio: 4.5:1 (AA)
- Recommended: 7:1 (AAA)

**Interactive Elements**:
- Minimum contrast ratio: 3:1
- Additional visual indicators required (not color alone)

### Approved Text Combinations

✅ **AAA Compliant**:
- Workshop White on Foundry Charcoal (15.8:1)
- Workshop White on Oil Black (17.4:1)
- Foundry Charcoal on Workshop White (15.8:1)
- Oil Black on Workshop White (17.4:1)

✅ **AA Compliant**:
- Brass Patina on Foundry Charcoal (5.2:1)
- Deep Brass on Workshop White (4.8:1)
- Blueprint Blue on Foundry Charcoal (4.7:1)
- Steel Gray on Workshop White (4.6:1)

⚠️ **Use with Caution**:
- Blueprint Blue on Workshop White (3.1:1) - Large text only
- Brass Patina on Sawdust Cream (2.8:1) - Decorative only

---

## Color in Context

### Desktop Applications
- **Preference**: Dark mode (Foundry Charcoal base)
- **Accent Ratio**: 10-15% Brass, 5% Blueprint
- **White Space**: Generous negative space

### Mobile Applications
- **Flexibility**: Support both light and dark modes
- **Touch Targets**: Brass accents for interactive elements
- **Readability**: Higher contrast for outdoor use

### Print Materials
- **Primary**: Use Pantone equivalents
- **Finish**: Consider metallic brass foil stamping
- **Paper**: Textured, premium stock

### Web Applications
- **Loading**: System preference detection
- **Toggle**: Easy dark/light mode switching
- **Consistency**: Maintain brand colors across themes

---

## Color Psychology & Messaging

### Foundry Charcoal
- **Psychology**: Sophistication, strength, timelessness
- **Message**: "Built to last"

### Brass Patina
- **Psychology**: Craftsmanship, value, warmth
- **Message**: "Handcrafted quality"

### Blueprint Blue
- **Psychology**: Precision, trust, intelligence
- **Message**: "Engineered excellence"

### Workshop White
- **Psychology**: Clarity, simplicity, possibility
- **Message**: "Clean slate, clear vision"

---

## Implementation Code

### CSS Custom Properties

```css
:root {
  /* Primary Colors */
  --foundry-charcoal: #2B2D2F;
  --brass-patina: #D4AF37;
  --deep-brass: #B8860B;
  --blueprint-blue: #4A90E2;
  --workshop-white: #F8F9FA;

  /* Supporting Colors */
  --oxidized-copper: #6B4423;
  --steel-gray: #71797E;
  --sawdust-cream: #E8DCC4;
  --oil-black: #1A1A1A;

  /* Semantic Colors */
  --success: #2D7A4F;
  --warning: #C87E22;
  --error: #A64435;
  --info: var(--blueprint-blue);

  /* Gradients */
  --gradient-brass: linear-gradient(135deg, #D4AF37 0%, #B8860B 100%);
  --gradient-charcoal: linear-gradient(180deg, #2B2D2F 0%, #1A1A1A 100%);
  --gradient-blueprint: radial-gradient(circle, #4A90E2 0%, rgba(74, 144, 226, 0) 70%);
}
```

### Tailwind Configuration

```javascript
module.exports = {
  theme: {
    extend: {
      colors: {
        'foundry-charcoal': '#2B2D2F',
        'brass-patina': '#D4AF37',
        'deep-brass': '#B8860B',
        'blueprint-blue': '#4A90E2',
        'workshop-white': '#F8F9FA',
        'oxidized-copper': '#6B4423',
        'steel-gray': '#71797E',
        'sawdust-cream': '#E8DCC4',
        'oil-black': '#1A1A1A',
      }
    }
  }
}
```

---

## Quality Control Checklist

- [ ] All text meets WCAG AA minimum contrast
- [ ] Interactive elements have 3:1 contrast minimum
- [ ] Color is not the only indicator of meaning
- [ ] Brand colors consistent across all materials
- [ ] Pantone specifications provided for print
- [ ] Dark mode and light mode both implemented
- [ ] Semantic colors clearly differentiated
- [ ] Gradients used sparingly and purposefully

---

**Last Updated**: November 4, 2025
**Version**: 1.0
