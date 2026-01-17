# Portfolio Brand Guidelines
**Hilmi Khaidar N - Personal Portfolio**

---

## 📋 Table of Contents
1. [Brand Overview](#brand-overview)
2. [Color Palette](#color-palette)
3. [Typography](#typography)
4. [Layout & Spacing](#layout--spacing)
5. [Components](#components)
6. [Animations & Transitions](#animations--transitions)
7. [Iconography](#iconography)
8. [Best Practices](#best-practices)

---

## 🎯 Brand Overview

### Brand Identity
- **Name:** Hilmi Khaidar N
- **Tagline:** Computer Science Student | Aspiring Software Engineer
- **Mission:** Bridging the gap between cutting-edge technology and seamless user experiences
- **Personality:** Modern, Professional, Clean, Minimalist, Tech-savvy

### Design Philosophy
- **Minimalism First:** Clean design with focus on content
- **User Experience:** Smooth interactions and intuitive navigation
- **Accessibility:** WCAG compliant, readable, and inclusive
- **Performance:** Fast loading, optimized animations
- **Responsive:** Mobile-first approach

---

## 🎨 Color Palette

### Light Mode
```css
Primary Background:    #FFFFFF
Secondary Background:  #F2F2F7
Text Primary:          #000000
Text Secondary:        #8E8E93
Card Background:       #F2F2F7
Border Color:          #E5E5EA
Shadow:                rgba(0, 0, 0, 0.1)
Glass Background:      rgba(255, 255, 255, 0.8)
Glass Border:          rgba(255, 255, 255, 0.2)
```

**Color Codes:**
| Color Name | Hex Code | RGB | Usage |
|------------|----------|-----|-------|
| Pure White | `#FFFFFF` | `rgb(255, 255, 255)` | Main background |
| Light Gray | `#F2F2F7` | `rgb(242, 242, 247)` | Cards, secondary bg |
| Pure Black | `#000000` | `rgb(0, 0, 0)` | Primary text |
| Medium Gray | `#8E8E93` | `rgb(142, 142, 147)` | Secondary text |
| Border Gray | `#E5E5EA` | `rgb(229, 229, 234)` | Borders, dividers |

### Dark Mode
```css
Primary Background:    #000000
Secondary Background:  #1C1C1E
Text Primary:          #FFFFFF
Text Secondary:        #8E8E93
Card Background:       #1C1C1E
Border Color:          #38383A
Shadow:                rgba(0, 0, 0, 0.3)
Glass Background:      rgba(0, 0, 0, 0.8)
Glass Border:          rgba(255, 255, 255, 0.1)
```

**Color Codes:**
| Color Name | Hex Code | RGB | Usage |
|------------|----------|-----|-------|
| Pure Black | `#000000` | `rgb(0, 0, 0)` | Main background |
| Dark Gray | `#1C1C1E` | `rgb(28, 28, 30)` | Cards, secondary bg |
| Pure White | `#FFFFFF` | `rgb(255, 255, 255)` | Primary text |
| Medium Gray | `#8E8E93` | `rgb(142, 142, 147)` | Secondary text |
| Border Dark | `#38383A` | `rgb(56, 56, 58)` | Borders, dividers |

### Accent Colors (Optional)
For future enhancements or call-to-action elements:
```css
Blue Accent:    #007AFF  /* iOS Blue */
Green Success:  #34C759  /* Success states */
Red Error:      #FF3B30  /* Error states */
Orange Warning: #FF9500  /* Warning states */
```

---

## ✍️ Typography

### Font Family
```css
Primary Font: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif
```
**Rationale:** System fonts for optimal performance and native feel across platforms

### Font Sizes
| Element | Size | Weight | Line Height | Usage |
|---------|------|--------|-------------|-------|
| Hero Title | `3rem` (48px) | 700 | 1.2 | Main heading |
| Section Title | `2rem` (32px) | 700 | 1.3 | Section headings |
| Subsection Title | `1.5rem` (24px) | 600 | 1.4 | Card titles |
| Body Large | `1.25rem` (20px) | 500 | 1.6 | Hero subtitle |
| Body Regular | `1rem` (16px) | 400 | 1.6 | Body text |
| Body Small | `0.875rem` (14px) | 500 | 1.5 | Meta info |
| Caption | `0.75rem` (12px) | 500 | 1.4 | Tags, labels |

### Font Weights
- **Light:** 300 (rarely used)
- **Regular:** 400 (body text)
- **Medium:** 500 (emphasis)
- **Semibold:** 600 (subtitles)
- **Bold:** 700 (headings)

### Responsive Typography
```css
/* Mobile (< 768px) */
Hero Title: 2rem (32px)
Section Title: 1.75rem (28px)

/* Tablet (768px - 1024px) */
Hero Title: 2.5rem (40px)
Section Title: 2rem (32px)

/* Desktop (> 1024px) */
Hero Title: 3rem (48px)
Section Title: 2rem (32px)
```

---

## 📐 Layout & Spacing

### Container
```css
Max Width: 1200px
Padding: 2rem (32px)
Margin: 0 auto
```

### Spacing Scale
Based on 8px grid system:
```css
XXS: 0.25rem (4px)
XS:  0.5rem (8px)
SM:  0.75rem (12px)
MD:  1rem (16px)
LG:  1.5rem (24px)
XL:  2rem (32px)
2XL: 3rem (48px)
3XL: 4rem (64px)
4XL: 6rem (96px)
```

### Grid System
```css
/* Projects/Cards Grid */
Grid Template: repeat(auto-fit, minmax(300px, 1fr))
Gap: 1.5rem (24px)

/* Skills Grid */
Grid Template: repeat(auto-fit, minmax(280px, 1fr))
Gap: 2rem (32px)
```

### Border Radius
```css
Small:  8px   /* Tags, small buttons */
Medium: 12px  /* Dock items */
Large:  16px  /* Buttons */
XLarge: 20px  /* Cards */
2XL:    24px  /* Dock, modals */
3XL:    32px  /* Avatar, special cards */
```

### Shadows
```css
/* Light Mode */
Small:  0 2px 8px rgba(0, 0, 0, 0.1)
Medium: 0 8px 32px rgba(0, 0, 0, 0.1)
Large:  0 12px 40px rgba(0, 0, 0, 0.1)
XLarge: 0 20px 60px rgba(0, 0, 0, 0.1)

/* Dark Mode */
Small:  0 2px 8px rgba(0, 0, 0, 0.3)
Medium: 0 8px 32px rgba(0, 0, 0, 0.3)
Large:  0 12px 40px rgba(0, 0, 0, 0.3)
XLarge: 0 20px 60px rgba(0, 0, 0, 0.3)
```

---

## 🧩 Components

### Buttons
```css
/* Primary Button */
Padding: 1rem 2rem
Border Radius: 16px
Font Weight: 600
Transition: all 0.3s cubic-bezier(0.25, 0.46, 0.45, 0.94)
Hover: translateY(-2px) + shadow

/* Icon Button (Dock) */
Size: 40px × 40px
Border Radius: 12px
Hover: translateY(-2px) scale(1.05)
```

### Cards
```css
/* Project Card */
Background: var(--card-bg)
Border Radius: 32px
Padding: 2rem
Border: 1px solid var(--border-color)
Hover: translateY(-8px) + shadow

/* Certification Card */
Background: var(--card-bg)
Border Radius: 20px
Padding: 1.5rem
Border: 1px solid var(--border-color)
Top Border: 3px gradient on hover
```

### Dock Navigation
```css
Position: fixed bottom 1.5rem
Background: glassmorphism (blur 20px)
Border Radius: 24px
Padding: 0.75rem
Gap: 0.25rem
Shadow: 0 8px 32px
```

### Theme Toggle
```css
Size: 60px × 32px
Border Radius: 32px
Slider: 28px × 28px circle
Transition: 0.3s cubic-bezier
```

### Tags
```css
Padding: 0.25rem 0.75rem
Border Radius: 12px
Font Size: 0.75rem
Font Weight: 500
Border: 1px solid var(--border-color)
```

---

## ✨ Animations & Transitions

### Easing Functions
```css
/* Standard */
Standard: cubic-bezier(0.25, 0.46, 0.45, 0.94)

/* Smooth Theme Transition */
Smooth: cubic-bezier(0.19, 1, 0.22, 1)

/* Buttery Smooth */
Buttery: cubic-bezier(0.16, 1, 0.3, 1)
```

### Transition Durations
```css
Fast:     0.2s  /* Hover states */
Standard: 0.3s  /* Most interactions */
Slow:     0.6s  /* Theme toggle */
XSlow:    1.0s  /* Theme colors */
XXSlow:   1.2s  /* Background transitions */
```

### Hover Effects
```css
/* Cards */
Transform: translateY(-8px)
Shadow: 0 20px 60px

/* Buttons */
Transform: translateY(-2px)
Shadow: 0 8px 24px

/* Dock Items */
Transform: translateY(-2px) scale(1.05)
Background: var(--card-bg)
```

### Scroll Animations
```css
Fade In: opacity 0 → 1
Slide Up: translateY(30px) → 0
Duration: 0.6s
Easing: cubic-bezier(0.25, 0.46, 0.45, 0.94)
```

### Particle Background
```css
Particle Count: 80
Particle Size: 1-3px
Connection Distance: 120px
Mouse Interaction Radius: 150px
Opacity: 0.6
```

---

## 🎯 Iconography

### Icon Style
- **Type:** Line icons (stroke-based)
- **Stroke Width:** 2px
- **Size:** 20px × 20px (dock), 24px × 24px (cards)
- **Style:** Rounded corners, consistent weight
- **Source:** Custom SVG icons

### Icon Usage
```html
<!-- Standard Icon -->
<svg width="24" height="24" viewBox="0 0 24 24" 
     fill="none" stroke="currentColor" stroke-width="2" 
     stroke-linecap="round" stroke-linejoin="round">
  <!-- icon path -->
</svg>
```

### Icon Colors
- Inherit from parent text color
- Use `currentColor` for stroke
- No fill (outline style)

---

## 📱 Responsive Breakpoints

```css
/* Mobile First Approach */
Mobile:       < 480px
Mobile Large: 480px - 768px
Tablet:       768px - 1024px
Desktop:      > 1024px
Large Desktop: > 1440px
```

### Responsive Adjustments
```css
/* Mobile (< 768px) */
- Container padding: 1rem
- Hero title: 2rem
- Grid: 1 column
- Dock: smaller items (36px)

/* Tablet (768px - 1024px) */
- Container padding: 1.5rem
- Hero title: 2.5rem
- Grid: 2 columns

/* Desktop (> 1024px) */
- Container padding: 2rem
- Hero title: 3rem
- Grid: 3+ columns
```

---

## ✅ Best Practices

### Do's ✅
- Use system fonts for performance
- Maintain consistent spacing (8px grid)
- Keep animations smooth (60fps)
- Test in both light and dark mode
- Ensure proper contrast ratios (WCAG AA)
- Use semantic HTML
- Optimize images (lazy loading)
- Keep file sizes small
- Test on multiple devices
- Use CSS variables for theming

### Don'ts ❌
- Don't use too many colors
- Don't overuse animations
- Don't ignore accessibility
- Don't use fixed pixel values everywhere
- Don't forget mobile users
- Don't use heavy images without optimization
- Don't mix different icon styles
- Don't use `!important` unless necessary
- Don't forget to test performance
- Don't ignore browser compatibility

### Accessibility
```css
/* Minimum Contrast Ratios */
Normal Text: 4.5:1
Large Text: 3:1
UI Components: 3:1

/* Focus States */
Always visible
Clear indication
Keyboard navigable

/* Screen Readers */
Use semantic HTML
Add ARIA labels when needed
Provide alt text for images
```

### Performance
```css
/* Optimization Tips */
- Use CSS transforms over position changes
- Prefer opacity over visibility
- Use will-change sparingly
- Lazy load images
- Minimize repaints/reflows
- Use requestAnimationFrame for animations
- Optimize particle count for mobile
- Compress images (WebP format)
```

---

## 🎨 Design Tokens (CSS Variables)

```css
:root {
  /* Colors */
  --bg-primary: #FFFFFF;
  --bg-secondary: #F2F2F7;
  --text-primary: #000000;
  --text-secondary: #8E8E93;
  --card-bg: #F2F2F7;
  --border-color: #E5E5EA;
  --shadow: rgba(0, 0, 0, 0.1);
  --glass-bg: rgba(255, 255, 255, 0.8);
  --glass-border: rgba(255, 255, 255, 0.2);
  
  /* Spacing */
  --space-xs: 0.5rem;
  --space-sm: 0.75rem;
  --space-md: 1rem;
  --space-lg: 1.5rem;
  --space-xl: 2rem;
  --space-2xl: 3rem;
  
  /* Border Radius */
  --radius-sm: 8px;
  --radius-md: 12px;
  --radius-lg: 16px;
  --radius-xl: 20px;
  --radius-2xl: 24px;
  --radius-3xl: 32px;
  
  /* Transitions */
  --transition-fast: 0.2s;
  --transition-base: 0.3s;
  --transition-slow: 0.6s;
  --easing-standard: cubic-bezier(0.25, 0.46, 0.45, 0.94);
  --easing-smooth: cubic-bezier(0.19, 1, 0.22, 1);
}
```

---

## 📝 Version History

**v1.0.0** - January 2026
- Initial brand guidelines
- Light/Dark mode color system
- Typography scale
- Component library
- Animation standards
- Particle background system

---

## 📞 Contact

For questions or suggestions about these guidelines:
- **Email:** hello.mikhaiii@gmail.com
- **GitHub:** [@HilmiKhaidarN](https://github.com/HilmiKhaidarN)
- **LinkedIn:** [Hilmi Khaidar N](https://linkedin.com/in/hilmikhaidarn)

---

**Last Updated:** January 14, 2026  
**Maintained by:** Hilmi Khaidar N
