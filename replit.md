# SEOInux - SEO & Digital Marketing Platform

## Overview
SEOInux is a comprehensive SEO & Digital Marketing website/platform built with React, Express, and PostgreSQL. It features a stunning landing page with services showcase, portfolio, testimonials, blog, contact forms, free SEO tools, and pricing sections.

## Recent Changes
- **Feb 14, 2026**: Initial build with full landing page, SEO tools (word counter, meta tag generator, keyword density checker), contact form, dark/light mode toggle, orange theme, and database-backed content.

## Architecture
- **Frontend**: React + Vite + Tailwind CSS + shadcn/ui + framer-motion
- **Backend**: Express.js with PostgreSQL (Drizzle ORM)
- **Theme**: Orange primary color (#F97316), dark mode support
- **Font**: Inter (sans), JetBrains Mono (mono)

### Key Files
- `client/src/pages/home.tsx` - Main landing page composing all sections
- `client/src/components/` - All section components (hero, services, portfolio, tools, etc.)
- `client/src/components/theme-provider.tsx` - Dark/light mode toggle
- `server/routes.ts` - API endpoints for contacts, blog, testimonials, services, portfolio
- `server/storage.ts` - Database storage layer
- `server/seed.ts` - Database seed data
- `shared/schema.ts` - Drizzle schema definitions

### Database Tables
- `contacts` - Contact form submissions
- `blog_posts` - Blog content
- `testimonials` - Client testimonials
- `services` - Service offerings
- `portfolio_items` - Portfolio/case studies

### SEO Tools (Frontend-only)
- Word Counter
- Meta Tag Generator
- Keyword Density Checker
- Article Rewriter (coming soon placeholder)

## User Preferences
- Orange/dark theme inspired by SEOInux WordPress theme
- Full landing page with all sections in single scroll
- SEO-optimized with proper meta tags
