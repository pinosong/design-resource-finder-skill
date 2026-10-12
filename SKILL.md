---
name: "design_resource_finder"
description: "Find visual/design reference materials before designing thumbnails, covers, title cards, or pages: curated directory of design inspiration galleries, layout libraries, typography/color/texture resources, plus a workflow for turning references into a design. Use when the user needs design inspiration, a cover/thumbnail style, or visual reference materials."
---

# Design Resource Finder

## Purpose
Look up curated, human-vetted design inspiration and visual-asset sources before designing anything visual: video thumbnails/covers, in-video title cards, or web pages. References, not generation — this skill finds *what good looks like*; the design/build step comes after.

## Workflow
1. **Define the style first.** Check for an existing brand preset (`assets/brand-preset.md`; start from `assets/brand-preset.example.md`). If none exists, ask the user for 2–3 adjectives or one reference they like — never browse blind.
2. **Find the mood.** Start with a curated aggregator — [Designeer](https://www.designeer.xyz) Inspiration — or a gallery from `references/site-directory.md` § Galleries that matches the style (editorial minimalism → Minimal Gallery / Practical Typography; dark tech → Dark Mode Design; bold type cards → posts.design).
3. **Find the layout.** For concrete compositions use the section-specific libraries: Unsection / Landingfolio (landing sections), Footer.design / Navbar Gallery (page furniture), Mobbin / before.click (vertical mobile cards).
4. **Find the elements.** Typography (Fonts In Use, Google Fonts, Fontshare), color (Coolors, Realtime Colors, Huemint), backgrounds/textures (MagicPattern, Haikei, Backgrounds Supply), icons (Lucide, Heroicons, Phosphor), photos (Unsplash, Pexels).
5. **Record the pick.** Save the chosen references (site name + URL + what to borrow: layout / color / typography / texture) in the project notes, so the next design round starts from the same source. If the user approves a look as their brand, write it into `assets/brand-preset.md`.

## Output Contract
- A short list of 3–8 references: name, URL, one-line style note, and exactly what to borrow (layout / color / typography / texture).
- No AI-slop aesthetics unless the user explicitly asks: no neon cyberpunk, no 3D-render hype, no busy imagery behind text.

## Operating Rules
1. Style before browsing — never collect references without a style target.
2. Prefer curated real work over concept shots (SiteInspire over Dribbble for real sites; Mobbin over mockups).
3. Text must stay readable: reject any reference with busy imagery behind type.
4. Keep the directory fresh: if a linked site is dead, note it in `references/site-directory.md` instead of silently dropping it.
5. This skill finds *references* — it does not generate the final design. Hand the picks to the design/build step.
