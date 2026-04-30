# D. Hess Media - Website Design Guidelines

## Brand Overview

**Company Name:** D. Hess Media  
**Tagline:** Your partner in digital innovation  
**Industry:** Digital Services / Web Development

## Design Philosophy

The website should embody a **modern, professional, and minimalist** aesthetic that communicates trust, innovation, and technical expertise. The design prioritizes clarity, bold typography, and generous whitespace to create a premium user experience.

## Color Palette

| Role | Color | Hex Code |
|------|-------|----------|
| Primary Background | Dark Navy | `#1a1a2e` |
| Secondary Background | Electric Blue | `#0f3460` |
| Accent | Coral | `#e94560` |
| Text (Light) | White | `#ffffff` |
| Text (Muted) | Light Gray | `#e0e0e0` |

### Usage Guidelines
- **Dark navy** as the primary background for hero sections and footer
- **Electric blue** for secondary sections and cards
- **Coral** for CTAs, highlights, and interactive elements
- High contrast between text and backgrounds for accessibility

## Typography

### Font Family
- **Primary:** Clean sans-serif font (Inter, system-ui, or similar)
- **Fallback:** `-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif`

### Type Scale
- **H1:** 3.5rem / 56px - Bold (700) - Hero headlines
- **H2:** 2.5rem / 40px - Bold (700) - Section titles
- **H3:** 1.75rem / 28px - Semibold (600) - Subsection titles
- **Body:** 1rem / 16px - Regular (400) - Paragraph text
- **Small:** 0.875rem / 14px - Regular (400) - Captions, metadata

### Typography Guidelines
- Generous letter-spacing on headlines
- Line height: 1.6 for body, 1.2 for headlines
- Left-aligned text for readability
- Max line length: 65-75 characters

## Layout & Spacing

### Grid System
- 12-column grid for desktop
- Responsive breakpoints: 320px, 768px, 1024px, 1280px
- Container max-width: 1200px

### Spacing Scale
- **xs:** 0.25rem (4px)
- **sm:** 0.5rem (8px)
- **md:** 1rem (16px)
- **lg:** 2rem (32px)
- **xl:** 4rem (64px)
- **2xl:** 6rem (96px)

### Guidelines
- Generous whitespace between sections
- Consistent padding: 80px vertical on desktop, 40px on mobile
- Card padding: 32px internal

## Components

### Buttons
- **Primary:** Coral background, white text, 12px padding, rounded corners (4px)
- **Secondary:** Transparent background, white border, hover fills with coral
- Hover state: Slight scale transform (1.02) + shadow

### Navigation
- Fixed/sticky header with dark navy background
- Logo left, nav links right
- Active state indicated by coral underline

### Cards
- Dark blue background (#0f3460)
- Subtle border or shadow
- Hover: slight lift effect + border highlight

### Hero Section
- Full viewport height
- Centered headline with tagline
- Prominent CTA button
- Optional: subtle gradient or geometric background pattern

## Content Structure

### Homepage Sections
1. **Hero** - Headline, tagline, primary CTA
2. **Services** - Three-column card layout showcasing:
   - Web Design & Development
   - Digital Marketing
   - Brand Strategy
3. **About** - Company story, values, team intro
4. **Portfolio/Work** - Showcase of recent projects
5. **Contact** - Contact form, social links, location

### Footer
- Logo + tagline
- Quick navigation links
- Social media icons
- Copyright notice

## Interactions & Animations

- Smooth scroll behavior
- Fade-in on scroll for sections
- Hover effects on interactive elements
- Transitions: 0.3s ease for all hover states
- No excessive animations; keep it professional

## Accessibility

- WCAG 2.1 AA compliance minimum
- All interactive elements keyboard accessible
- Focus indicators visible (coral outline)
- Alt text for all images
- Semantic HTML structure
- Sufficient color contrast ratios

## Performance

- Optimize images (WebP where possible)
- Lazy loading for below-fold content
- Minimize CSS/JS
- Target: <2s load time on 3G
