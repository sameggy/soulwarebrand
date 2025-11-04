# The Workshop: Design Elements & Visual Assets

## Typography System

### Font Family Hierarchy

#### Primary: IBM Plex Mono
**Precision & Craftsmanship in Every Character**

```
Family: IBM Plex Mono
Weights: 300 (Light), 400 (Regular), 500 (Medium), 600 (SemiBold)
Fallback: 'Courier New', Courier, monospace
Google Fonts: https://fonts.google.com/specimen/IBM+Plex+Mono
```

**Characteristics**:
- Monospaced for technical precision
- Excellent readability at small sizes
- Industrial yet friendly
- Perfect code-to-design bridge

**Usage**:
- Headings (H1, H2, H3)
- Technical documentation
- Code blocks and snippets
- Navigation menus
- Button labels
- Captions and labels
- Numeric data

**Example Sizing**:
```css
h1 { font: 600 48px/1.2 'IBM Plex Mono'; letter-spacing: -0.02em; }
h2 { font: 600 36px/1.3 'IBM Plex Mono'; letter-spacing: -0.01em; }
h3 { font: 500 24px/1.4 'IBM Plex Mono'; letter-spacing: 0; }
code { font: 400 14px/1.6 'IBM Plex Mono'; }
```

---

#### Secondary: Inter
**Clean, Functional Body Text**

```
Family: Inter
Weights: 400 (Regular), 500 (Medium), 600 (SemiBold)
Fallback: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif
Google Fonts: https://fonts.google.com/specimen/Inter
```

**Characteristics**:
- Optimized for screens
- Excellent at small sizes
- Neutral and professional
- High x-height for readability

**Usage**:
- Body copy (paragraphs)
- UI elements (forms, inputs)
- Long-form content
- Descriptions
- Metadata
- Lists

**Example Sizing**:
```css
body { font: 400 16px/1.6 'Inter'; letter-spacing: -0.011em; }
p { font: 400 18px/1.7 'Inter'; }
small { font: 400 14px/1.5 'Inter'; }
```

---

#### Accent: Playfair Display
**Artisan Elegance**

```
Family: Playfair Display
Weights: 400 (Regular), 600 (SemiBold), 700 (Bold)
Fallback: Georgia, 'Times New Roman', serif
Google Fonts: https://fonts.google.com/specimen/Playfair+Display
```

**Characteristics**:
- High contrast, elegant
- Heritage craftsmanship feel
- Display-optimized
- Use sparingly for impact

**Usage**:
- Hero headlines (special occasions)
- Pull quotes
- Premium product names
- Editorial content headers
- About/Story sections
- Anniversary or special edition branding

**Example Sizing**:
```css
.hero-headline { font: 700 72px/1.1 'Playfair Display'; }
.quote { font: 400 28px/1.5 'Playfair Display'; font-style: italic; }
```

---

### Typography Scale

**Desktop Scale**:
```
Hero Display: 72px / 4.5rem - Playfair Display Bold
H1: 48px / 3rem - IBM Plex Mono SemiBold
H2: 36px / 2.25rem - IBM Plex Mono SemiBold
H3: 24px / 1.5rem - IBM Plex Mono Medium
H4: 20px / 1.25rem - IBM Plex Mono Medium
Body Large: 18px / 1.125rem - Inter Regular
Body: 16px / 1rem - Inter Regular
Small: 14px / 0.875rem - Inter Regular
Micro: 12px / 0.75rem - Inter Regular
Caption: 10px / 0.625rem - IBM Plex Mono Light
```

**Mobile Scale** (Adjusted):
```
Hero Display: 48px / 3rem
H1: 36px / 2.25rem
H2: 28px / 1.75rem
H3: 22px / 1.375rem
H4: 18px / 1.125rem
Body: 16px / 1rem
```

---

### Letter Spacing & Line Height

**Headings**:
```
Display (72px): -0.03em tracking, 1.1 leading
H1 (48px): -0.02em tracking, 1.2 leading
H2 (36px): -0.01em tracking, 1.3 leading
H3-H4: 0em tracking, 1.4 leading
```

**Body Text**:
```
Large (18px): -0.011em tracking, 1.7 leading
Regular (16px): -0.011em tracking, 1.6 leading
Small (14px): 0em tracking, 1.5 leading
```

**Monospace**:
```
Code blocks: 0.02em tracking, 1.6 leading
Inline code: 0em tracking, 1.5 leading
```

---

### Paragraph Formatting

**Standard Paragraphs**:
```
Margin-bottom: 1.5em
Max-width: 65ch (optimal readability)
Text-align: left
Orphans/Widows: 3 lines minimum
```

**Drop Caps** (Optional, for editorial):
```css
.drop-cap::first-letter {
  font-size: 3.5em;
  font-family: 'Playfair Display', serif;
  font-weight: 700;
  float: left;
  line-height: 0.9;
  margin: 0.1em 0.1em 0 0;
  color: var(--brass-patina);
}
```

---

## Icon System

### Icon Style Guide

**Specifications**:
- **Grid**: 24×24px base grid
- **Stroke Width**: 2px
- **Style**: Outlined (not filled)
- **Corners**: Sharp, 90° angles preferred
- **Aesthetic**: Tool-inspired, mechanical

**Export Sizes**:
- 16×16px (small UI elements)
- 24×24px (standard)
- 32×32px (large buttons)
- 48×48px (feature highlights)
- 64×64px (hero sections)

### Icon Themes

**Tool Icons**:
- Hammer, Wrench, Screwdriver
- Ruler, Compass, Square
- Saw, Plane, Chisel
- Anvil, Vise, Caliper

**Process Icons**:
- Blueprint/Schematic
- Measurement marks
- Assembly diagrams
- Precision indicators

**Interface Icons**:
- Navigation (geometric arrows)
- Actions (clean, precise shapes)
- Status (technical indicators)
- Social (minimalist versions)

### Icon Color Usage

```css
/* Default state */
stroke: var(--steel-gray);

/* Hover state */
stroke: var(--brass-patina);
transition: stroke 0.2s ease;

/* Active state */
stroke: var(--brass-patina);
fill: rgba(212, 175, 55, 0.1);

/* Disabled state */
stroke: var(--steel-gray);
opacity: 0.4;
```

---

## Grid & Layout System

### Base Grid
**8-Point Grid System**

All spacing, sizing, and positioning use multiples of 8px:
```
4px (0.25rem) - Micro spacing
8px (0.5rem) - Minimum touch target
16px (1rem) - Standard spacing
24px (1.5rem) - Section padding
32px (2rem) - Component spacing
48px (3rem) - Large sections
64px (4rem) - Major sections
96px (6rem) - Hero spacing
128px (8rem) - Extra large spacing
```

### Column Grid

**Desktop (1440px)**:
```
Columns: 12
Gutter: 24px
Margin: 80px
Content max-width: 1280px
```

**Tablet (768px)**:
```
Columns: 8
Gutter: 16px
Margin: 40px
```

**Mobile (375px)**:
```
Columns: 4
Gutter: 16px
Margin: 24px
```

### Layout Patterns

**Full Bleed**:
```
Edge-to-edge content
Use for: Hero images, full-width backgrounds
```

**Contained**:
```
Max-width: 1280px
Centered with auto margins
Use for: Standard content sections
```

**Sidebar Layout**:
```
Main: 8 columns
Sidebar: 4 columns
Gap: 48px
Use for: Documentation, blog posts
```

---

## Texture & Pattern Library

### Blueprint Grid Pattern

**Specifications**:
```
Grid size: 20×20px
Line weight: 1px
Line color: Brass Patina @ 10% opacity
Background: Foundry Charcoal
Pattern: Repeating squares with corner marks
```

**CSS Implementation**:
```css
.blueprint-grid {
  background-color: #2B2D2F;
  background-image:
    linear-gradient(rgba(212, 175, 55, 0.1) 1px, transparent 1px),
    linear-gradient(90deg, rgba(212, 175, 55, 0.1) 1px, transparent 1px);
  background-size: 20px 20px;
}
```

---

### Brushed Metal Texture

**Specifications**:
```
Direction: Horizontal (0°)
Opacity: 5-10%
Color: Steel Gray
Blend mode: Overlay
```

**Usage**:
- Header backgrounds
- Card surfaces
- Button backgrounds (subtle)

---

### Wood Grain Pattern

**Specifications**:
```
Style: Fine, tight grain
Opacity: 8-12%
Color: Oxidized Copper @ 40%
Orientation: Horizontal
```

**Usage**:
- Warm section backgrounds
- Heritage content areas
- Testimonial sections

---

### Leather Texture

**Specifications**:
```
Style: Subtle pebble grain
Opacity: 6-10%
Color: Oxidized Copper
Blend mode: Multiply
```

**Usage**:
- Premium product showcases
- About sections
- Contact sections

---

## Illustration Style

### Technical Illustrations

**Line Style**:
```
Weight: 1.5px
Color: Brass Patina
Style: Continuous, precise lines
Caps: Square
Joins: Miter
```

**Isometric Grid**:
```
Angle: 30° projection
Grid: 8px base unit
Depth: Consistent, not exaggerated
```

**Blueprint Style**:
```
Background: Foundry Charcoal or Blueprint Blue @ 15%
Lines: Workshop White or Brass Patina
Dimensions: Show measurement annotations
Callouts: Circular with leader lines
```

**Exploded Views**:
```
Separation: 1.5× component size
Connection: Dashed guide lines
Labels: IBM Plex Mono, 12px
```

---

### Iconographic Illustration

**Style Characteristics**:
- Geometric precision
- Tool-inspired metaphors
- 2-3 colors maximum
- Negative space utilization
- Symbolic, not literal

**Color Palette for Illustrations**:
- Primary: Brass Patina
- Secondary: Blueprint Blue
- Accent: Oxidized Copper
- Background: Foundry Charcoal or Workshop White

---

## Photography Art Direction

### Subject Guidelines

**Hands & Craftsmanship**:
- Close-up hand details
- Tools being used
- Work in progress
- Weathered, skilled hands
- Authentic workspace

**Materials & Textures**:
- Wood grain closeups
- Metal surfaces
- Raw materials
- Patina and wear
- Tool details

**Environment**:
- Workshop spaces (organized, not cluttered)
- Natural light preferred
- Authentic work environments
- Process documentation
- Before/after comparisons

### Photography Treatment

**Color Grading**:
```
Shadows: +10 warmth
Highlights: +5 coolness
Saturation: -5 to -10
Contrast: +10 to +15
Clarity: +15 to +20
```

**Composition Rules**:
- Rule of thirds
- Leading lines (tools, grain, edges)
- Selective focus (f/2.8 - f/5.6)
- Natural vignetting acceptable
- Avoid centered, static compositions

**Lighting**:
- Directional, not flat
- Side lighting preferred
- Hard shadows acceptable
- Golden hour warmth
- Workshop/studio lighting feel

---

## Borders & Dividers

### Line Styles

**Standard Border**:
```css
border: 1px solid rgba(113, 121, 126, 0.4);
```

**Accent Border**:
```css
border: 2px solid var(--brass-patina);
```

**Technical Border**:
```css
border: 1px dashed rgba(74, 144, 226, 0.6);
```

**Section Divider**:
```css
height: 2px;
background: linear-gradient(
  90deg,
  transparent 0%,
  var(--brass-patina) 50%,
  transparent 100%
);
opacity: 0.3;
```

---

## Shadow System

**Elevation Levels**:

```css
/* Level 1: Subtle lift */
box-shadow: 0 1px 3px rgba(26, 26, 26, 0.12);

/* Level 2: Card elevation */
box-shadow:
  0 2px 4px rgba(26, 26, 26, 0.08),
  0 4px 8px rgba(26, 26, 26, 0.08);

/* Level 3: Floating elements */
box-shadow:
  0 4px 8px rgba(26, 26, 26, 0.12),
  0 8px 16px rgba(26, 26, 26, 0.12);

/* Level 4: Modal/overlay */
box-shadow:
  0 8px 16px rgba(26, 26, 26, 0.16),
  0 16px 32px rgba(26, 26, 26, 0.16);

/* Level 5: Maximum elevation */
box-shadow:
  0 16px 32px rgba(26, 26, 26, 0.2),
  0 32px 64px rgba(26, 26, 26, 0.2);
```

**Brass Glow** (for accents):
```css
box-shadow:
  0 0 20px rgba(212, 175, 55, 0.3),
  0 0 40px rgba(212, 175, 55, 0.1);
```

---

## Corner Radius System

**Minimal, Precise Corners**:

```css
--radius-none: 0px;          /* Pure geometric */
--radius-minimal: 2px;       /* Slight softening */
--radius-small: 4px;         /* Cards, buttons */
--radius-medium: 8px;        /* Larger components */
--radius-large: 16px;        /* Special elements */
--radius-full: 9999px;       /* Pills, badges */
```

**Usage Guidelines**:
- Prefer sharp corners for technical feel
- Use 2-4px for most UI elements
- Avoid excessive rounding
- Consistent radius per component type

---

## Animation Specifications

### Timing Functions

```css
/* Mechanical precision */
--ease-workshop: cubic-bezier(0.4, 0.0, 0.2, 1);

/* Smooth assembly */
--ease-craft: cubic-bezier(0.25, 0.1, 0.25, 1);

/* Quick snap */
--ease-precision: cubic-bezier(0.5, 0, 0.5, 1);

/* Gentle ease */
--ease-organic: cubic-bezier(0.33, 0, 0.67, 1);
```

### Duration Scale

```css
--duration-instant: 100ms;    /* Micro-interactions */
--duration-fast: 200ms;       /* Hover states */
--duration-normal: 300ms;     /* Standard transitions */
--duration-slow: 400ms;       /* Page transitions */
--duration-slower: 600ms;     /* Special effects */
```

### Animation Types

**Assembly Animation**:
```css
@keyframes assemble {
  from {
    opacity: 0;
    transform: translateY(20px) scale(0.95);
  }
  to {
    opacity: 1;
    transform: translateY(0) scale(1);
  }
}
```

**Blueprint Draw**:
```css
@keyframes blueprint-draw {
  from {
    stroke-dashoffset: 1000;
  }
  to {
    stroke-dashoffset: 0;
  }
}
```

**Brass Glow Pulse**:
```css
@keyframes brass-pulse {
  0%, 100% {
    box-shadow: 0 0 20px rgba(212, 175, 55, 0.3);
  }
  50% {
    box-shadow: 0 0 30px rgba(212, 175, 55, 0.5);
  }
}
```

---

## Spacing System

**Component Spacing**:

```
Inline Elements: 4px - 8px
Related Items: 16px
Component Padding: 16px - 24px
Section Padding: 48px - 64px
Section Margin: 64px - 96px
Page Margins: 80px - 120px
```

**Rhythm & Vertical Spacing**:
- Maintain consistent vertical rhythm
- Use line-height as spacing base
- Increase spacing between unrelated sections
- Decrease spacing between related elements

---

## Component Specifications

### Button Styles

**Primary Button**:
```css
background: linear-gradient(135deg, #D4AF37 0%, #B8860B 100%);
color: #2B2D2F;
font: 500 16px 'IBM Plex Mono';
padding: 12px 32px;
border: none;
border-radius: 2px;
transition: all 0.2s var(--ease-workshop);

&:hover {
  box-shadow: 0 4px 12px rgba(212, 175, 55, 0.4);
  transform: translateY(-2px);
}

&:active {
  transform: translateY(0);
}
```

**Secondary Button**:
```css
background: transparent;
color: #D4AF37;
font: 500 16px 'IBM Plex Mono';
padding: 12px 32px;
border: 2px solid #D4AF37;
border-radius: 2px;

&:hover {
  background: rgba(212, 175, 55, 0.1);
}
```

---

### Form Elements

**Text Input**:
```css
background: transparent;
border: 1px solid rgba(113, 121, 126, 0.6);
border-radius: 2px;
padding: 12px 16px;
font: 400 16px 'Inter';
color: inherit;

&:focus {
  border: 2px solid #4A90E2;
  outline: none;
}
```

---

### Card Component

```css
background: rgba(248, 249, 250, 0.05);
border: 1px solid rgba(113, 121, 126, 0.2);
border-radius: 4px;
padding: 32px;
box-shadow: 0 2px 4px rgba(26, 26, 26, 0.08);
transition: all 0.3s var(--ease-craft);

&:hover {
  border-color: rgba(212, 175, 55, 0.4);
  box-shadow: 0 4px 8px rgba(26, 26, 26, 0.12);
  transform: translateY(-4px);
}
```

---

## Print Specifications

### Business Card
```
Size: 3.5" × 2" (89mm × 51mm)
Bleed: 0.125" (3mm)
Safe Area: 0.25" (6mm) from edges
Stock: 16pt C2S with Soft Touch coating
Finish: Brass foil stamp on logo
```

### Letterhead
```
Size: 8.5" × 11" (Letter)
Colors: 4-color process + Pantone 7551 C
Stock: 28lb premium bond
Elements: Logo, address footer, subtle blueprint grid
```

---

## Quality Checklist

- [ ] Typography hierarchy is clear and consistent
- [ ] All spacing uses 8-point grid system
- [ ] Icons are consistent stroke weight and style
- [ ] Textures used at appropriate opacity
- [ ] Shadows follow elevation system
- [ ] Animations are purposeful, not distracting
- [ ] Corner radius is minimal and consistent
- [ ] Grid system properly implemented
- [ ] All components documented

---

**Last Updated**: November 4, 2025
**Version**: 1.0
