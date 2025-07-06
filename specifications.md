---
layout: default
title: "OIDI Flag Specifications"
description: "Technical specifications, dimensions, and color codes for the International Organization for Identity Documents (OIDI) flag."
---

# <span class="org-name">OIDI</span> Flag Specifications

## Technical Details

### File Formats
- **Primary Format**: SVG (Scalable Vector Graphics)
- **File Names**: 
  - `flag_b.svg` (Black variant)
  - `flag_n.svg` (Navy variant)

### Dimensions
- **Aspect Ratio**: 3:2 (standard flag proportions)
- **Recommended Sizes**:
  - Web: 150x100px minimum
  - Print: 300 DPI minimum
  - Large format: Vector scaling recommended

### Color Codes

#### Black Variant (`flag_b.svg`)
- **Primary Color**: #000000 (Pure Black)
- **Secondary Colors**: [To be specified based on actual flag design]

#### Navy Variant (`flag_n.svg`)
- **Primary Color**: #1e3a8a (Navy Blue)
- **Secondary Colors**: [To be specified based on actual flag design]

## Usage Requirements

### Minimum Size
- **Digital**: 50x33 pixels
- **Print**: 1 inch width minimum

### Clear Space
- Maintain clear space equal to 1/4 of the flag's height on all sides
- No other graphic elements should appear within this clear space

### Background Usage
- **Light Backgrounds**: Use black variant for optimal contrast
- **Dark Backgrounds**: Consider navy variant or ensure sufficient contrast
- **Colored Backgrounds**: Test contrast ratios to ensure readability

## File Structure

```
flags/
├── flag_b.svg          # Black variant
├── flag_n.svg          # Navy variant
├── flag_b_large.svg    # High-resolution black variant
├── flag_n_large.svg    # High-resolution navy variant
└── specifications.pdf  # Complete technical specifications
```

## Quality Standards

### Vector Graphics
- All flag files maintain vector format for infinite scalability
- Optimized for web delivery while preserving quality
- Compatible with all modern browsers and applications

### Accessibility
- High contrast ratios meet WCAG 2.1 AA standards
- Alternative text provided for screen readers
- Scalable for users with visual impairments