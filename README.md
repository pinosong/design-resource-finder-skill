# design-resource-finder

Find **visual references before designing** — so thumbnails, covers, title cards, and pages start from curated, human-vetted design instead of guesswork or AI slop.

- **Style-first workflow** — define the look (or load your `brand-preset.md`) *before* browsing; never collect references blind
- **Curated directory** — ~35 design inspiration galleries, section libraries, typography/color/texture resources, icon sets, and stock photo sources in `references/site-directory.md`
- **Concrete picks** — aggregators for mood (Designeer, Awwwards, SiteInspire), section libraries for layout (Unsection, Landingfolio, Mobbin), element sources for type/color/texture/icons
- **Brand presets** — `assets/brand-preset.example.md` shows how to pin your own visual identity (with two filled examples); copy to `brand-preset.md` and make it yours
- **Readability rules** — no neon-cyberpunk AI clichés, no busy imagery behind text, prefer real shipped work over concept shots

## Quick start

1. Read `SKILL.md` (the 5-step workflow).
2. Copy `assets/brand-preset.example.md` → `assets/brand-preset.md` and fill in your brand — or just tell your agent 2–3 adjectives and one reference you like.
3. Ask your agent: "find cover references for <topic>" / "找一下竖屏封面的版式参考".

## Layout

```
SKILL.md                          # purpose, workflow, output contract, operating rules
references/site-directory.md      # the curated site directory (~35 sources)
assets/brand-preset.example.md    # brand preset template + 2 filled examples
```

## For skill authors

This skill finds *references*; it deliberately does not generate designs. Pair it with your build/render pipeline (video, thumbnails, pages) — hand the picks to the design step.
