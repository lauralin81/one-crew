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

### Font Stack - Updated for OneCrew

Our typography system uses four carefully selected fonts to create visual hierarchy and personality:

- **Display Font**: **Outfit** - Modern, geometric sans-serif with excellent readability for headlines and brand elements
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

## Color Palette - OneCrew Brand Colors

### Primary Colors
A vibrant blue palette matching the OneCrew logo that conveys innovation, trust, and teamwork:

```css
--primary-50: #eff6ff   /* Lightest background */
--primary-100: #dbeafe  /* Light background */
--primary-200: #bfdbfe  /* Subtle accent */
--primary-300: #93c5fd  /* Light accent */
--primary-400: #60a5fa  /* Medium accent */
--primary-500: #3b82f6  /* Base primary */
--primary-600: #2563eb  /* OneCrew Logo Blue (main brand color) */
--primary-700: #1d4ed8  /* Dark primary */
--primary-800: #1e40af  /* Darker primary */
--primary-900: #1e3a8a  /* Darkest primary */
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
--accent-emerald: #10b981     /* Emerald accent */
--accent-emerald-light: #34d399 /* Light emerald */
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

```