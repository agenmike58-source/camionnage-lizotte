# Camionnage Jonathan Lizotte Inc. — Website Build

## Client
- **Name:** Camionnage Jonathan Lizotte Inc.
- **Industry:** Trucking / Transport (Quebec)

## Requirements
- Must look like a **$20,000 professional website**. Premium feel, polished, high-end
- **NO emoji icons anywhere.** Use inline SVGs only. Emoji break in headless Chrome
- **AI-generated images** — use OpenRouter GPT-5-image-mini for hero shots, fleet photos, driver shots, logistics imagery. Make them look real and high quality. Trucks on Quebec highways, loading docks, fleet lineup, team photos
- **SVG LOGO IS MANDATORY** — create a proper inline SVG logo for the company. Trucking/transport themed. Professional. Must be in logo.svg and referenced in header

## Designer Brief (Myriam)
1. **RESEARCH FIRST** — search for top trucking/transport company websites. Look at 5-10 real competitors (Quebec and North America). Note what makes the expensive ones look expensive: layout, typography, imagery, spacing, animations, color choices
2. Save research findings to /tmp/myriam-research-lizotte.md
3. Design must feel premium. Think: bold typography, strong imagery of trucks/fleet, professional color palette (consider dark navy, industrial tones, or whatever research suggests)
4. Consider what sections a trucking company needs: hero, services (LTL, FTL, local, long-haul, specialized), fleet/equipment, service areas, about/history, safety/certifications, quote request, contact
5. Make it responsive but desktop-first
6. **LOGO:** Design a proper SVG logo. Trucking themed. Clean, professional, works at any size. Save as logo.svg
7. Write full DESIGN-SPEC.md with layout, components, colors, typography, responsive behavior, animation notes, logo description

## Builder Brief (Sonia)
1. Wait for Myriam's DESIGN-SPEC.md before building
2. Single-page or multi-section scroll — whatever Myriam specs
3. Generate all images using OpenRouter image gen script (check /tmp/or_gen.py or recreate from memory/business-website-process.md)
4. All images saved to project directory
5. Static HTML/CSS/JS — no frameworks, Tailwind CDN only
6. Build at ~/Projects/businesses/camionnage-lizotte/
7. SVG logo MUST be included — logo.svg in project root, referenced in header
8. Test locally, validate, self-check against spec
9. Copy finished site to Tony's desk: C:\Users\Agent\Documents\desk\camionnage-lizotte\

## Image Generation
- Use OpenRouter GPT-5-image-mini (~$0.04/image)
- Generate: hero banner (truck on Quebec highway or fleet lineup), 4-6 service/fleet photos (semi trucks, flatbeds, loading dock, logistics), facility shot, team/driver photo
- Images must look realistic and professional. No cartoons, no stock photo feel
- Save all to project images/ directory

## QA
- Samira reviews against DESIGN-SPEC.md
- Must score 8+ to ship
- Playwright screenshots for review
