# Kuppo — Landing Page

## What is this?
Marketing landing page for Kuppo, a digital loyalty stamp card platform for small businesses (cafés, bakeries, salons, restaurants). Separate from the main React PWA app.

## Task
Build the landing page from scratch using Astro + Tailwind CSS v4.

Full spec with all copy, structure, colors, SEO, and competitive research:
https://github.com/DMB-Soft/over-the-box/wiki/Landing-Page

GitHub issue: https://github.com/DMB-Soft/over-the-box/issues/56

## Tech Stack
- **Astro** (static SSG)
- **Tailwind CSS v4**
- **Plus Jakarta Sans** (headlines) + **Inter** (body) from Google Fonts
- Contact form backend: Supabase (same project as the main app)

## Design Direction
- **Colors:** Warm indigo primary (`#4F46E5`), amber accent (`#F59E0B`), stone neutrals (`#FAFAF9` bg, `#1C1917` text)
- **Tone:** Friendly, direct, Hungarian "te" form. Outcome-focused, no jargon.
- **Language:** Hungarian-first. English can come later.
- **Style:** Clean, warm, minimal. Not corporate. Think "sharp friend who runs a coffee shop."
- **No fake social proof** — use research citations (e.g. Bain & Company stat on returning customers) until we have real customers.

## Page Sections (in order)
1. **Navbar** — sticky, transparent on hero → white on scroll. Logo + "Belépés" + "Próbáld ki ingyen" CTA
2. **Hero** — text left, phone mockup right. Headline: "Törzsvásárlóid egy koppintásra" or "A hűségkártya, amit tényleg használnak". Primary + secondary CTA + trust line.
3. **Social proof bar** — research stat or tagline
4. **How it works** — 3 steps, merchant + customer perspectives side by side
5. **Features** — 5 max (stamp cards, QR scanning, dashboard, flexible rewards, campaigns). Icon + title + one sentence each.
6. **For whom** — 4 merchant types: café, bakery, salon, restaurant
7. **Pricing** — "coming soon" placeholder with contact CTA, or single tier if ready
8. **Contact form** — 4 fields: name, email, business name, message. Submit to Supabase.
9. **FAQ** — 6 questions (see wiki for exact content)
10. **Footer** — links, legal, © 2026 DMB Soft Kft.

## Content
All Hungarian copy (headlines, sublines, feature descriptions, FAQ Q&A, footer links) is defined in the wiki spec. Use it directly — don't rewrite or translate.

## SEO
- Meta description (HU): "Digitális pecsétgyűjtő kártya kisvállalkozásoknak. QR kód alapú hűségprogram — papír nélkül, egyszerűen. Próbáld ki ingyen!"
- Primary keywords: digitális hűségkártya, digitális pecsétgyűjtő, törzsvásárlói program app, hűségprogram kisvállalkozásoknak

## Design Quality
Use the `/frontend-design` skill. This should look polished and distinctive — not a generic template. Study the competitor landing pages in the wiki for patterns to use and avoid. Key rules:
- Max 5-8 CTAs total on page
- No feature dumps
- Each section earns its place — no filler
- Mobile-first responsive

## What NOT to do
- Don't add testimonials (we don't have customers yet)
- Don't use emojis in the actual page (wiki uses them for readability, the page should use proper icons)
- Don't overcomplicate — single page, no routing needed
- Don't add English yet — HU only for MVP

## Design Context

### Users
Hungarian small business owners — café, bakery, salon, restaurant operators. Non-technical, time-poor, often looking at this on a phone between customers. The job: decide if this loyalty card tool is right for their business, in under 60 seconds.

### Brand Personality
**Warm, sharp, confident.** Like talking to a smart friend who runs a coffee shop.

### Aesthetic Direction
- **Reference**: linear.app — minimal, sharp typography, smooth micro-interactions, purposeful whitespace
- **Anti-references**: Enterprise/corporate (salesforce.com), cheap/budget feel (cramped, clashing, banner-ad energy)
- **Theme**: Light mode only. Warm stone neutrals, not cold grays.

### Design Principles
1. **Earn every pixel** — No decorative filler. Every element serves comprehension, trust, or conversion.
2. **Warm precision** — Linear's sharpness meets coffee-shop warmth. Tight spacing and clean type, but approachable.
3. **Obvious over clever** — Value proposition in 5 seconds. No jargon, no abstract illustrations.
4. **Motion with purpose** — Subtle animations that guide attention, never distract. Respect prefers-reduced-motion.
5. **Mobile-first honesty** — Every layout decision starts at 375px.
