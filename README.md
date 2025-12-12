# Nexus - Modern SaaS Landing Page

A stunning, contest-winning frontend project built with Next.js, TypeScript, Tailwind CSS, and Framer Motion.

![Next.js](https://img.shields.io/badge/Next.js-16-black)
![TypeScript](https://img.shields.io/badge/TypeScript-5-blue)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4-38bdf8)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-12-purple)

## 🚀 Live Demo

[View Live Demo](#) *(Deploy to Vercel/Netlify to get URL)*

## 📋 Features Implemented

### 🎨 Design & Aesthetics
- **Premium Dark Theme** with vibrant purple/blue gradient accents
- **Glassmorphism Effects** on navigation and cards
- **Custom Design System** with CSS variables for consistency
- **Responsive Desktop Layout** optimized for 1280px+ screens

### ⚡ Components
| Component | Description |
|-----------|-------------|
| **Navbar** | Fixed header with glassmorphism, smooth scroll navigation, mobile menu |
| **Hero** | Animated headlines, gradient text, CTA buttons, trust badges |
| **Features** | 6 feature cards with icons, scroll-triggered animations |
| **Stats** | Animated number counters with scroll detection |
| **Testimonials** | Customer testimonial cards with ratings |
| **CTA** | Call-to-action section with animated gradient orbs |
| **Footer** | Multi-column layout, newsletter signup, social links |

### 🎭 Animations (Framer Motion)
- Page load animations with staggered children
- Scroll-triggered reveal animations
- Hover effects on buttons and cards
- Animated scroll indicator
- Counter animations for statistics

### ♿ Accessibility (WCAG 2.1)
- Semantic HTML5 structure (`<header>`, `<main>`, `<section>`, `<footer>`)
- Skip link for keyboard navigation
- ARIA labels and roles
- Focus states for all interactive elements
- Reduced motion support (`prefers-reduced-motion`)
- Color contrast compliance

## 🛠️ Tech Stack

| Technology | Version | Purpose |
|------------|---------|---------|
| Next.js | 16.0.10 | React framework with App Router |
| TypeScript | 5.x | Type safety |
| Tailwind CSS | 4.x | Utility-first styling |
| Framer Motion | 12.x | Animations |
| Lucide React | 0.561.x | Icons |

## 📦 Setup Instructions

### Prerequisites
- Node.js 18+ 
- npm or yarn

### Installation

```bash
# Clone the repository
git clone <repository-url>
cd frontend

# Install dependencies
npm install

# Run development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to view the app.

### Build for Production

```bash
# Create production build
npm run build

# Start production server
npm start
```

### Linting

```bash
npm run lint
```

## 📁 Project Structure

```
src/
├── app/
│   ├── globals.css      # Design system & global styles
│   ├── layout.tsx       # Root layout with SEO metadata
│   └── page.tsx         # Main landing page
├── components/
│   ├── index.ts         # Barrel exports
│   ├── Navbar.tsx       # Navigation component
│   ├── Hero.tsx         # Hero section
│   ├── Features.tsx     # Features grid
│   ├── Stats.tsx        # Statistics section
│   ├── Testimonials.tsx # Customer testimonials
│   ├── CTA.tsx          # Call-to-action section
│   └── Footer.tsx       # Footer component
```

## 💡 Key Design Decisions

1. **Dark Theme**: Chosen for modern, premium feel common in SaaS products
2. **CSS Variables**: Used for maintainable theming and consistency
3. **Glassmorphism**: Applied sparingly for depth without overwhelming
4. **Cubic-bezier Easing**: Custom easing curves for smooth, natural animations
5. **Component Isolation**: Each section is a self-contained component for reusability

## 🎯 Assumptions Made

- Desktop-first design (optimized for 1280px+)
- Modern browser support (Chrome, Firefox, Safari, Edge)
- Users have JavaScript enabled
- No backend/API integration required

## ⏱️ Time Spent

| Task | Time |
|------|------|
| Project Setup | 15 min |
| Design System | 30 min |
| Components Development | 2 hours |
| Animations & Interactions | 45 min |
| Accessibility | 30 min |
| Testing & Bug Fixes | 30 min |
| Documentation | 20 min |
| **Total** | **~4.5 hours** |

## 🚀 Deployment

### Vercel (Recommended)

1. Push code to GitHub
2. Import project in [Vercel](https://vercel.com)
3. Deploy with default settings

### Netlify

1. Push code to GitHub
2. Import project in [Netlify](https://netlify.com)
3. Build command: `npm run build`
4. Publish directory: `.next`

---

Built with ❤️ for the Frontend Developer Intern position
