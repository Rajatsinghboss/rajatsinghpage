# Project Context

## Repository
https://github.com/Rajatsinghboss/rajatsinghpage.git

## Deployment
Not deployed yet. The page is a standalone `index.html` and is suitable for GitHub Pages once deployment is configured.

## Product
A personal portfolio and lead-generation landing page for Rajat Singh, founder of Growth Karo.

## Audience
- Brands, D2C and e-commerce companies, local businesses, and founders seeking SEO, social media, video advertising, websites, branding, and lead generation.
- Political leaders and their teams seeking digital political PR, leader branding, campaign creative, video production, social media strategy, and digital outreach.

## Goal
Start qualified project conversations with Rajat, with equally visible contact paths for brand marketing and political PR. Encourage visitors to explore selected work and the full Growth Karo portfolio.

## Brand
- Name: Rajat Singh
- Role: Founder of Growth Karo
- Instagram: https://www.instagram.com/rajatsingh_boss2/
- Agency website: https://growthkaro.in/
- Portfolio source: https://growthkaro.in/portfolio
- Primary contact: Growth Karo WhatsApp link, https://wa.me/918076517834

## Visual Direction
Premium light-theme portfolio with soft white and blue-tinted backgrounds, mint, lavender, sky-blue, and coral accents, rounded cards, subtle shadows, and large Space Grotesk headings with DM Sans body copy. The Three.js hero uses a colorful 3D orb and floating particles. Scroll-triggered section reveals, floating artwork, hover lift, and gentle ambient movement add energy without clutter. A CSS fallback remains available if WebGL or the CDN is unavailable.

## Page Structure
1. Sticky navigation and direct WhatsApp CTA.
2. Hero presenting Rajat as founder, with an animated 3D object and two audience signals.
3. Brief credibility strip.
4. Two clear service paths: brands/businesses and political leaders.
5. Selected Growth Karo portfolio work, linking to the full portfolio.
6. Founder introduction and Instagram link.
7. Simple four-step project process.
8. Contact section with audience-specific WhatsApp messages.
9. Footer linking to Growth Karo, its portfolio, and Rajat's Instagram.

## Copy Direction
Professional English with a natural Indian-business tone. Make services and next steps specific. Avoid unsupported founder credentials, invented testimonials, or guaranteed performance claims. Case-study figures shown on the source portfolio are marked as website-reported and should be verified before use in paid promotion.

## Assets
- Visual design uses inline SVG geometry, a Three.js scene, and the founder portrait asset at `assets/rajat-singh.webp`; no build tooling is required.
- Growth Karo case study names and reported metrics are referenced from https://growthkaro.in/portfolio.
- Founder portrait: `assets/rajat-singh.webp`, created as an optimized transparent cutout from the photo supplied in the conversation. Used in the opening hero and About section with a pop-in entrance and gentle float animation.
- Instagram profile: @rajatsingh_boss2.

## Functionality
- Responsive layout for desktop, tablet, and mobile.
- Working section navigation and mobile menu.
- Three.js colorful animated 3D hero with pointer interaction and a CSS fallback.
- Rajat's transparent portrait animates into the hero and also appears in the About section.
- IntersectionObserver scroll reveals, float animations, hover lifts, and pastel ambient background motion.
- Respects `prefers-reduced-motion`.
- Audience-specific WhatsApp links, full portfolio link, and Instagram links.
- Semantic sections, focus-visible states, and inline SVG icons.

## Avoid
- Generic agency-template styling and repeated identical card grids.
- Fake headshots or imagery attributed to Rajat without verification.
- Unverified personal biography, client claims, performance guarantees, and invented testimonials.
- Making political PR look tied to a specific political party.
- Overuse of motion, blur, glowing effects, emoji icons, gradient text, and visual noise. Animation should be soft, purposeful, and disabled/reduced when `prefers-reduced-motion` is enabled.

## Current Decisions
- Audience priority: equal focus on brands/businesses and political leaders.
- Main positioning: Rajat Singh, founder of Growth Karo.
- Primary conversion action: start a WhatsApp conversation.
- Brand services include SEO, social media, video ads, websites, branding, and lead generation.
- Political PR focuses on digital strategy, leader branding, campaign creatives, video, social media, and digital outreach.
- Portfolio case details source: https://growthkaro.in/portfolio.
- Instagram handle: @rajatsingh_boss2.
- Design reference: no supplied reference; custom light-theme 3D-led direction with pastel gradients and scroll-triggered reveals.
- Latest visual update: convert dark surfaces to a bright palette, animate scroll reveals and floating portfolio artwork, and recolor the Three.js orb. Portrait and real brand/political leader imagery are intentionally not part of this change.
- Language: professional English with selective Hinglish where it adds warmth.
