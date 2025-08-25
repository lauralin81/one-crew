# Command View Design Tokens

## Overview

Command View is a comprehensive organizational management platform designed for small to medium businesses. The design system combines the clean, functional aesthetic of Notion with the modern, efficient interface of Linear, optimized for mobile-first experiences.

## Design Philosophy

- **Mobile-First**: All components are designed for mobile devices first, then enhanced for desktop
- **Accessibility**: WCAG 2.1 AA compliant color contrasts and interactive elements
- **Performance**: Optimized for fast loading and smooth interactions
- **Scalability**: Design tokens ensure consistency across all platforms and screen sizes

## Color Palette

### Primary Colors
Our primary blue palette conveys trust, professionalism, and reliability - essential for business applications.

```css
--primary-50: #f0f9ff   /* Lightest background */
--primary-100: #e0f2fe  /* Light background */
--primary-200: #bae6fd  /* Subtle accent */
--primary-300: #7dd3fc  /* Light accent */
--primary-400: #38bdf8  /* Medium accent */
--primary-500: #0ea5e9  /* Base primary */
--primary-600: #0284c7  /* Primary (main brand color) */
--primary-700: #0369a1  /* Dark primary */
--primary-800: #075985  /* Darker primary */
--primary-900: #0c4a6e  /* Darkest primary */
```

### Neutral Grays
A comprehensive gray scale for text, backgrounds, and borders.

```css
--gray-50: #f8fafc   /* Lightest background */
--gray-100: #f1f5f9  /* Light background */
--gray-200: #e2e8f0  /* Borders and dividers */
--gray-300: #cbd5e1  /* Input borders */
--gray-400: #94a3b8  /* Placeholder text */
--gray-500: #64748b  /* Secondary text */
--gray-600: #475569  /* Body text */
--gray-700: #334155  /* Strong text */
--gray-800: #1e293b  /* Headings */
--gray-900: #0f172a  /* Primary text */
```

### Semantic Colors

#### Success
```css
--success-50: #f0fdf4   /* Success background */
--success-500: #22c55e  /* Success text/icon */
--success-600: #16a34a  /* Success hover */
```

#### Warning
```css
--warning-50: #fffbeb   /* Warning background */
--warning-500: #f59e0b  /* Warning text/icon */
--warning-600: #d97706  /* Warning hover */
```

#### Error
```css
--error-50: #fef2f2   /* Error background */
--error-500: #ef4444  /* Error text/icon */
--error-600: #dc2626  /* Error hover */
```

## Typography

### Font Families

- **Primary**: Inter - Modern, highly legible sans-serif optimized for UI
- **Monospace**: JetBrains Mono - Clean monospace font for code and technical content

### Type Scale

```css
.h1 { font-size: 3rem; font-weight: 700; line-height: 1.2; }      /* Page titles */
.h2 { font-size: 2.25rem; font-weight: 600; line-height: 1.3; }   /* Section headers */
.h3 { font-size: 1.875rem; font-weight: 600; line-height: 1.4; }  /* Subsection headers */
.h4 { font-size: 1.5rem; font-weight: 600; line-height: 1.4; }    /* Card titles */
.h5 { font-size: 1.25rem; font-weight: 600; line-height: 1.5; }   /* Small headers */
.h6 { font-size: 1.125rem; font-weight: 600; line-height: 1.5; }  /* Micro headers */
.body-lg { font-size: 1.125rem; line-height: 1.7; }                /* Large body text */
.body { font-size: 1rem; line-height: 1.6; }                       /* Standard body text */
.body-sm { font-size: 0.875rem; line-height: 1.5; }                /* Small body text */
.caption { font-size: 0.75rem; line-height: 1.4; }                 /* Captions and metadata */
```

## Spacing System

Consistent spacing scale based on 4px (0.25rem) increments:

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
```

## Border Radius

```css
--radius-sm: 0.375rem  /* 6px - Small elements */
--radius-md: 0.5rem    /* 8px - Standard elements */
--radius-lg: 0.75rem   /* 12px - Cards and panels */
--radius-xl: 1rem      /* 16px - Large elements */
```

## Shadows

Progressive shadow system for depth and hierarchy:

```css
--shadow-sm: 0 1px 2px 0 rgb(0 0 0 / 0.05)                                    /* Subtle elevation */
--shadow-md: 0 4px 6px -1px rgb(0 0 0 / 0.1), 0 2px 4px -2px rgb(0 0 0 / 0.1) /* Standard elevation */
--shadow-lg: 0 10px 15px -3px rgb(0 0 0 / 0.1), 0 4px 6px -4px rgb(0 0 0 / 0.1) /* High elevation */
--shadow-xl: 0 20px 25px -5px rgb(0 0 0 / 0.1), 0 8px 10px -6px rgb(0 0 0 / 0.1) /* Maximum elevation */
```

## Transitions

```css
--transition-fast: 0.15s ease   /* Quick interactions */
--transition-normal: 0.2s ease  /* Standard interactions */
--transition-slow: 0.3s ease    /* Complex animations */
```

## Component Specifications

### Buttons

**Primary Button**
- Background: `--primary-600`
- Text: White
- Hover: `--primary-700` with subtle lift animation
- Focus: 3px `--primary-100` outline

**Secondary Button**
- Background: White
- Border: 1px `--gray-300`
- Text: `--gray-700`
- Hover: `--gray-50` background

**Ghost Button**
- Background: Transparent
- Text: `--gray-600`
- Hover: `--gray-100` background

### Cards

- Background: White
- Border: 1px `--gray-200`
- Border radius: `--radius-lg`
- Hover: 2px lift with `--shadow-lg`
- Padding: `--space-6` for body, `--space-4` for footer

### Form Elements

**Input Fields**
- Border: 1px `--gray-300`
- Focus: 1px `--primary-500` with 3px `--primary-100` outline
- Padding: `--space-3` `--space-4`
- Border radius: `--radius-md`

### Badges

- Background: Semantic color with 50% opacity
- Text: Semantic color at 600 level
- Padding: `--space-1` `--space-3`
- Border radius: `--radius-sm`
- Font: 0.75rem, uppercase, letter-spacing 0.05em

## Mobile Responsive Breakpoints

```css
/* Mobile First */
@media (max-width: 480px) {
    /* Small mobile adjustments */
}

@media (max-width: 768px) {
    /* Tablet and mobile adjustments */
}

@media (min-width: 769px) {
    /* Desktop enhancements */
}
```

## Accessibility Guidelines

### Color Contrast
- All text meets WCAG 2.1 AA standards (4.5:1 for normal text, 3:1 for large text)
- Interactive elements have sufficient contrast ratios
- Focus states are clearly visible

### Interactive Elements
- Minimum touch target size: 44px × 44px
- Focus indicators are keyboard accessible
- Hover states provide clear feedback

### Typography
- Minimum font size: 14px for body text
- Line height ensures readability
- Font weights provide clear hierarchy

## Usage Guidelines

### When to Use Each Component

**Primary Buttons**: Main actions, CTAs, form submissions
**Secondary Buttons**: Alternative actions, cancel buttons
**Ghost Buttons**: Tertiary actions, navigation elements

**Cards**: Content containers, project overviews, team information
**Badges**: Status indicators, categories, priority levels

**Form Elements**: Data input, search, filtering

### Do's and Don'ts

✅ **Do**
- Use consistent spacing throughout the interface
- Maintain proper color contrast ratios
- Test components on mobile devices
- Use semantic colors for status indicators

❌ **Don't**
- Mix different border radius values unnecessarily
- Use colors outside the defined palette
- Skip hover and focus states
- Ignore mobile responsiveness

## Implementation Notes

- All design tokens are defined as CSS custom properties
- Components use utility classes for consistent styling
- Mobile-first approach ensures optimal performance
- Design system is built for scalability and maintainability
