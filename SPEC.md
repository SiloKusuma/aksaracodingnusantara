# TechCorp Landing Page Specification

## Project Overview
- **Project Name**: TechCorp - Technology Company Landing Page
- **Type**: Single-page marketing website
- **Core Functionality**: Corporate landing page showcasing technology company services, features, and contact info
- **Target Users**: Potential B2B clients, investors, tech professionals

## UI/UX Specification

### Layout Structure
- **Header**: Fixed navigation with glassmorphism effect
- **Hero Section**: Full viewport with animated 3D elements and glitch text effect
- **Services Section**: Grid of service cards with 3D hover effects
- **About Section**: Split layout with animated statistics
- **Contact Section**: Modern form with particle background
- **Footer**: Minimal with social icons

### Responsive Breakpoints
- Mobile: < 768px
- Tablet: 768px - 1024px
- Desktop: > 1024px

### Visual Design

#### Color Palette
- **Primary Background**: #0a0a0a (near black)
- **Secondary Background**: #111111 (dark gray)
- **Primary Text**: #ffffff (white)
- **Secondary Text**: #a0a0a0 (gray)
- **Accent**: #00ff88 (neon green)
- **Accent Secondary**: #00d4ff (cyan)
- **Gradient**: linear-gradient(135deg, #00ff88, #00d4ff)

#### Typography
- **Headings**: "Syne", sans-serif (extra bold)
- **Body**: "Outfit", sans-serif
- **Hero Title Size**: 4rem (desktop), 2.5rem (mobile)
- **Section Titles**: 2.5rem (desktop), 1.8rem (mobile)
- **Body Text**: 1rem

#### Spacing System
- Section padding: 100px vertical (desktop), 60px (mobile)
- Card padding: 30px
- Element gaps: 20px

#### Visual Effects
- Glassmorphism on cards: backdrop-filter: blur(10px)
- Glow effects on hover
- Text gradient animation
- Smooth scroll behavior
- Parallax animations on scroll

### Components

#### Navigation
- Logo (text-based with glow)
- Menu items with underline animation
- Mobile hamburger menu

#### Hero Section
- Animated headline with typing effect
- Floating 3D geometric shapes
- CTA buttons with pulse effect

#### Service Cards
- 3D tilt effect on hover
- Icon with glow
- Title and description
- Border gradient animation

#### Statistics Counter
- Animated number counting
- Gradient text

#### Contact Form
- Floating labels
- Validation styling
- Submit button with loading state

## Functionality Specification

### Core Features
1. Smooth scroll navigation
2. Scroll-triggered animations (Intersection Observer)
3. 3D card tilt effect
4. Typed text animation in hero
5. Counter animation for statistics
6. Mobile menu toggle
7. Form validation
8. Particle background in contact section

### User Interactions
- Hover effects on all interactive elements
- Click navigation smooth scroll to sections
- Form submission with validation feedback

## 3D Icons Resource
- Using LUCIDE Icons (free, modern SVG icons) with CSS 3D effects
- URL: https://lucide.dev/

## Acceptance Criteria
- [ ] Page loads without errors
- [ ] All sections visible and properly styled
- [ ] Responsive on all breakpoints
- [ ] Animations smooth (60fps)
- [ ] 3D hover effects working
- [ ] Navigation works correctly
- [ ] Contact form validates inputs