# AI Artist Portfolio - Specification

## 1. Project Overview

- **Project Name**: AI Artist Portfolio
- **Type**: Single-page portfolio website
- **Core Functionality**: Showcase AI-generated artwork with immersive visual experience, contact form, and modern aesthetics
- **Target Users**: Potential clients, art enthusiasts, gallery curators

---

## 2. UI/UX Specification

### Layout Structure

**Sections (top to bottom):**
1. **Navigation** - Fixed top navbar with logo and menu links
2. **Hero** - Full viewport with animated title and CTA
3. **About** - Artist bio with floating elements
4. **Gallery** - Masonry grid of AI artworks with lightbox
5. **Services** - Pricing/plans cards
6. **Testimonials** - Client reviews carousel
7. **Contact** - Contact form with fields
8. **Footer** - Social links and copyright

**Responsive Breakpoints:**
- Desktop: 1200px+
- Tablet: 768px - 1199px
- Mobile: < 768px

### Visual Design

**Color Palette:**
- Background: `#0a0a0f` (deep space black)
- Surface: `#12121a` (dark purple-black)
- Primary: `#00f5d4` (electric cyan)
- Secondary: `#7b2cbf` (vivid purple)
- Accent: `#ff006e` (hot pink)
- Text Primary: `#ffffff`
- Text Secondary: `#a0a0b0`
- Gradient: `linear-gradient(135deg, #7b2cbf 0%, #00f5d4 100%)`

**Typography:**
- Headings: 'Outfit', sans-serif (weights: 700, 800)
- Body: 'DM Sans', sans-serif (weights: 400, 500)
- Hero Title: 80px desktop, 48px mobile
- Section Titles: 48px desktop, 32px mobile
- Body: 18px, line-height 1.7

**Spacing System:**
- Section padding: 120px vertical desktop, 60px mobile
- Container max-width: 1400px
- Card padding: 32px
- Gap between elements: 24px

**Visual Effects:**
- Glassmorphism cards with backdrop-blur
- Gradient borders on hover
- Floating particle background animation
- Glow effects on primary elements
- Smooth scroll behavior

### Components

**Navigation:**
- Transparent background, blur on scroll
- Logo with gradient text
- Menu items with underline animation on hover
- Hamburger menu on mobile

**Hero Section:**
- Animated gradient background with floating orbs
- Glitch text effect on main title
- Subtitle with typewriter animation
- Two CTA buttons with different styles
- Scroll indicator at bottom

**About Section:**
- Split layout (text + decorative)
- Floating AI-generated visual elements
- Skill tags with glow effect

**Gallery:**
- Masonry grid (3 columns desktop, 2 tablet, 1 mobile)
- Cards with hover zoom and overlay
- Lightbox modal with navigation

**Services Cards:**
- 3 pricing tiers (Starter, Pro, Enterprise)
- Glassmorphism style
- Feature list with checkmarks
- Gradient border on popular plan

**Testimonials:**
- Auto-rotating carousel
- Quote styling with decorative marks
- Client avatar and name

**Contact Form:**
- Floating label inputs
- Gradient submit button
- Form validation styling

**Footer:**
- Social icons with hover glow
- Back to top button

---

## 3. Functionality Specification

### Core Features
- Smooth scroll navigation
- Lightbox gallery with keyboard navigation
- Auto-rotating testimonials (5s interval)
- Form validation (required fields, email format)
- Scroll-triggered animations (fade in, slide up)
- Parallax floating elements

### User Interactions
- Nav menu click → smooth scroll to section
- Gallery image click → open lightbox
- Gallery arrow keys → navigate lightbox
- ESC key → close lightbox
- Service card hover → scale up with border glow
- Form submit → show success message (no backend)
- Mobile menu toggle → slide-in menu

### Animations
- Hero: fade-in + slide-up on load (0.8s)
- Section titles: fade-in on scroll
- Gallery cards: staggered fade-in (0.1s delay each)
- Floating elements: continuous float animation
- Buttons: scale on hover (1.05)
- Links: underline slide animation

---

## 4. Acceptance Criteria

1. All 8 sections render correctly
2. Navigation links scroll to correct sections
3. Gallery lightbox opens/closes/navigates properly
4. Testimonials auto-rotate every 5 seconds
5. Form shows validation errors on invalid input
6. All animations are smooth (60fps)
7. Site is responsive at all breakpoints
8. No console errors on page load
9. All fonts load correctly
10. Color scheme matches specification exactly