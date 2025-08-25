# OneCrew Design System v2 - Modern & Distinctive

## Overview

OneCrew v2 represents a bold evolution of our design system, featuring distinctive typography, vibrant color palettes, and modern gradients that set us apart from competitors. This design system is built for impact while maintaining the professional credibility needed for enterprise software.

## Design Philosophy

- **Distinctive Identity**: Unique font combinations and vibrant colors that stand out in the market
- **Modern Aesthetics**: Contemporary design trends with gradients, enhanced shadows, and smooth animations
- **Mobile-First**: Optimized for mobile experiences with touch-friendly interactions
- **Accessibility**: WCAG 2.1 AA compliant with enhanced focus states and contrast ratios
- **Performance**: Optimized for fast loading with modern CSS techniques

## Typography System

### Font Stack - More Distinctive

Our typography system uses four carefully selected fonts to create visual hierarchy and personality:

- **Display Font**: **Outfit** - Modern, geometric sans-serif with excellent readability for headlines
- **Heading Font**: **Space Grotesk** - Contemporary monospace-inspired sans-serif for section headers
- **Body Font**: **Albert Sans** - Clean, highly legible sans-serif optimized for UI text
- **Monospace**: **JetBrains Mono** - Developer-friendly monospace for code and technical content

### Type Scale

```css
.h1 { font-family: var(--font-display); font-size: 3.5rem; font-weight: 800; line-height: 1.1; letter-spacing: -0.02em; }
.h2 { font-family: var(--font-heading); font-size: 2.75rem; font-weight: 700; line-height: 1.2; letter-spacing: -0.01em; }
.h3 { font-family: var(--font-heading); font-size: 2.25rem; font-weight: 600; line-height: 1.3; }
.h4 { font-family: var(--font-heading); font-size: 1.75rem; font-weight: 600; line-height: 1.4; }
.h5 { font-family: var(--font-heading); font-size: 1.5rem; font-weight: 600; line-height: 1.4; }
.h6 { font-family: var(--font-heading); font-size: 1.25rem; font-weight: 600; line-height: 1.5; }
.body-lg { font-size: 1.25rem; line-height: 1.7; font-weight: 400; }
.body { font-size: 1rem; line-height: 1.6; font-weight: 400; }
.body-sm { font-size: 0.875rem; line-height: 1.5; font-weight: 400; }
.caption { font-size: 0.75rem; line-height: 1.4; color: var(--gray-500); font-weight: 500; }
.mono { font-family: var(--font-mono); }
```

## Color Palette - Vibrant & Modern

### Primary Colors
A more vibrant blue palette that conveys innovation and trust:

```css
--primary-50: #f0f7ff   /* Lightest background */
--primary-100: #e0effe  /* Light background */
--primary-200: #bae0fd  /* Subtle accent */
--primary-300: #7cc5fb  /* Light accent */
--primary-400: #36a3f7  /* Medium accent */
--primary-500: #0d8aed  /* Base primary */
--primary-600: #006edb  /* Primary (main brand color) */
--primary-700: #0057b3  /* Dark primary */
--primary-800: #004a94  /* Darker primary */
--primary-900: #003d7a  /* Darkest primary */
```

### Vibrant Accent Colors
Bold accent colors for creating visual interest and hierarchy:

```css
--accent-purple: #8b5cf6      /* Purple accent */
--accent-purple-light: #a78bfa /* Light purple */
--accent-teal: #06b6d4        /* Teal accent */
--accent-teal-light: #22d3ee  /* Light teal */
--accent-orange: #f97316      /* Orange accent */
--accent-orange-light: #fb923c /* Light orange */
--accent-pink: #ec4899        /* Pink accent */
--accent-pink-light: #f472b6  /* Light pink */
```

### Modern Grays
Warm undertones for a more approachable feel:

```css
--gray-50: #fafafa   /* Lightest background */
--gray-100: #f5f5f5  /* Light background */
--gray-200: #e5e5e5  /* Borders and dividers */
--gray-300: #d4d4d4  /* Input borders */
--gray-400: #a3a3a3  /* Placeholder text */
--gray-500: #737373  /* Secondary text */
--gray-600: #525252  /* Body text */
--gray-700: #404040  /* Strong text */
--gray-800: #262626  /* Headings */
--gray-900: #171717  /* Primary text */
```

### Enhanced Semantic Colors

```css
--success-50: #f0fdf4   /* Success background */
--success-500: #10b981  /* Success text/icon */
--success-600: #059669  /* Success hover */

--warning-50: #fffbeb   /* Warning background */
--warning-500: #f59e0b  /* Warning text/icon */
--warning-600: #d97706  /* Warning hover */

--error-50: #fef2f2   /* Error background */
--error-500: #ef4444  /* Error text/icon */
--error-600: #dc2626  /* Error hover */
```

## Gradient System

Modern gradients for creating depth and visual interest:

```css
--gradient-primary: linear-gradient(135deg, var(--primary-600) 0%, var(--accent-purple) 100%);
--gradient-secondary: linear-gradient(135deg, var(--accent-teal) 0%, var(--accent-purple) 100%);
--gradient-accent: linear-gradient(135deg, var(--accent-orange) 0%, var(--accent-pink) 100%);
--gradient-warm: linear-gradient(135deg, var(--accent-orange) 0%, var(--accent-pink) 100%);
--gradient-cool: linear-gradient(135deg, var(--accent-teal) 0%, var(--primary-600) 100%);
```

## Enhanced Spacing System

Expanded spacing scale for more design flexibility:

```css
--space-1: 0.25rem   /* 4px - Micro spacing */
--space-2: 0.5rem    /* 8px - Small spacing */
--space-3: 0.75rem   /* 12px - Medium spacing */
--space-4: 1rem      /* 16px - Base spacing */
--space-5: 1.25rem   /* 20px - Large spacing */
--space-6: 1.5rem    /* 24px - Extra large spacing */
--space-8: 2rem      /* 32px - Section spacing */
--space-10: 2.5rem   /* 40px - Large section spacing */
--space-12: 3rem     /* 48px - Page spacing */
--space-16: 4rem     /* 64px - Major section spacing */
--space-20: 5rem     /* 80px - Hero spacing */
```

## Modern Border Radius

Enhanced border radius system for contemporary aesthetics:

```css
--radius-sm: 0.5rem   /* 8px - Small elements */
--radius-md: 0.75rem  /* 12px - Standard elements */
--radius-lg: 1rem     /* 16px - Cards and panels */
--radius-xl: 1.5rem   /* 24px - Large elements */
--radius-2xl: 2rem    /* 32px - Hero sections */
```

## Enhanced Shadows

Progressive shadow system for depth and hierarchy:

```css
--shadow-sm: 0 1px 2px 0 rgb(0 0 0 / 0.05)                                    /* Subtle elevation */
--shadow-md: 0 4px 6px -1px rgb(0 0 0 / 0.1), 0 2px 4px -2px rgb(0 0 0 / 0.1) /* Standard elevation */
--shadow-lg: 0 10px 15px -3px rgb(0 0 0 / 0.1), 0 4px 6px -4px rgb(0 0 0 / 0.1) /* High elevation */
--shadow-xl: 0 20px 25px -5px rgb(0 0 0 / 0.1), 0 8px 10px -6px rgb(0 0 0 / 0.1) /* Maximum elevation */
--shadow-2xl: 0 25px 50px -12px rgb(0 0 0 / 0.25)                              /* Hero shadows */
```

## Enhanced Transitions

```css
--transition-fast: 0.15s ease   /* Quick interactions */
--transition-normal: 0.3s ease  /* Standard interactions */
--transition-slow: 0.5s ease    /* Complex animations */
```

## Component Specifications

### Buttons

**Primary Button**
- Background: `--gradient-primary`
- Text: White
- Hover: 2px lift with `--shadow-xl`
- Focus: 2px `--primary-500` outline with 2px offset

**Secondary Button**
- Background: White
- Border: 2px `--gray-300`
- Text: `--gray-700`
- Hover: `--gray-50` background with border color change

**Accent Button**
- Background: `--gradient-accent`
- Text: White
- Hover: 2px lift with `--shadow-xl`

**Ghost Button**
- Background: Transparent
- Text: `--gray-600`
- Hover: `--gray-100` background with border

### Cards

- Background: White
- Border: 1px `--gray-200`
- Border radius: `--radius-xl`
- Hover: 4px lift with `--shadow-xl`
- Header: `--gradient-primary` background
- Padding: `--space-8` for body, `--space-6` for footer

### Form Elements

**Input Fields**
- Border: 2px `--gray-300`
- Focus: 2px `--primary-500` with 4px `--primary-100` outline
- Padding: `--space-4` `--space-5`
- Border radius: `--radius-lg`

### Badges

- Background: Semantic color with 50% opacity
- Text: Semantic color at 600 level
- Border: 1px solid semantic color
- Padding: `--space-2` `--space-4`
- Border radius: `--radius-lg`
- Font: 0.75rem, uppercase, letter-spacing 0.1em, `--font-heading`

## Animation System

### Keyframe Animations

```css
@keyframes fadeIn {
    from { opacity: 0; }
    to { opacity: 1; }
}

@keyframes slideUp {
    from { 
        opacity: 0;
        transform: translateY(20px);
    }
    to { 
        opacity: 1;
        transform: translateY(0);
    }
}
```

### Animation Classes

```css
.animate-fade-in {
    animation: fadeIn 0.6s ease-out;
}

.animate-slide-up {
    animation: slideUp 0.6s ease-out;
}
```

## Mobile Responsive Breakpoints

```css
/* Mobile First */
@media (max-width: 480px) {
    /* Small mobile adjustments */
    .h1 { font-size: 2rem; }
    .hero h1 { font-size: 2rem; }
}

@media (max-width: 768px) {
    /* Tablet and mobile adjustments */
    .h1 { font-size: 2.5rem; }
    .hero h1 { font-size: 2.5rem; }
    .grid-2, .grid-3, .grid-4 { grid-template-columns: 1fr; }
}

@media (min-width: 769px) {
    /* Desktop enhancements */
}
```

## Accessibility Enhancements

### Focus States
- All interactive elements have visible focus indicators
- Focus outline: 2px `--primary-500` with 2px offset
- Enhanced contrast for better visibility

### High Contrast Mode Support
```css
@media (prefers-contrast: high) {
    :root {
        --primary-600: #0052cc;
        --gray-900: #000000;
        --gray-100: #ffffff;
    }
}
```

### Reduced Motion Support
```css
@media (prefers-reduced-motion: reduce) {
    * {
        animation-duration: 0.01ms !important;
        animation-iteration-count: 1 !important;
        transition-duration: 0.01ms !important;
    }
}
```

## Usage Guidelines

### When to Use Each Font

**Outfit (Display)**: Large headlines, hero text, brand elements
**Space Grotesk (Heading)**: Section headers, navigation, card titles
**Albert Sans (Body)**: Body text, descriptions, form labels
**JetBrains Mono (Monospace)**: Code snippets, technical data, API responses

### When to Use Each Gradient

**Primary Gradient**: Main CTAs, primary navigation, hero sections
**Secondary Gradient**: Alternative CTAs, secondary navigation
**Accent Gradient**: Special features, premium elements, highlights
**Warm Gradient**: Success states, positive actions
**Cool Gradient**: Information states, neutral actions

### Color Usage Guidelines

**Primary Blue**: Main brand color, primary actions, navigation
**Purple Accent**: Premium features, special highlights
**Teal Accent**: Information, data visualization
**Orange Accent**: Warnings, attention-grabbing elements
**Pink Accent**: Success, positive feedback

### Do's and Don'ts

✅ **Do**
- Use gradients for primary actions and hero sections
- Combine different font families for clear hierarchy
- Use vibrant accent colors sparingly for impact
- Maintain consistent spacing throughout
- Test on mobile devices first

❌ **Don't**
- Use more than 2-3 accent colors on a single page
- Mix different gradient types without purpose
- Overuse animations or transitions
- Ignore accessibility guidelines
- Use fonts inconsistently across similar elements

## Implementation Notes

- All design tokens are defined as CSS custom properties
- Components use utility classes for consistent styling
- Mobile-first approach ensures optimal performance
- Design system is built for scalability and maintainability
- Enhanced animations and transitions for modern feel
- Comprehensive accessibility support built-in
