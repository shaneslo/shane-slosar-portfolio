# Portrait prompts — Claude Design Workflow

Updated prompts for running the two new AI-generated portraits through the
Claude Design Workflow. Both are tuned to the site's palette so the portraits
read as part of the same family as the rest of the group's work — black,
white, and one blue, never a second accent.

Per the slow dev dinner / slow fleet design pattern.

## Palette to align to

Pulled straight from the site's design tokens (`src/styles/theme.css` and the
dark-mode block in `src/layouts/Base.astro`). Hold the portraits to these:

| Role            | Light      | Dark       |
| --------------- | ---------- | ---------- |
| Accent (the one blue) | `#0066cc` | `#4d9fff` |
| Background      | `#ffffff` / `#fafafa` | `#0d0d0d` / `#141414` |
| Foreground      | `#1a1a1a`  | `#ededed`  |
| Secondary text  | `#525252`  | `#a0a0a0`  |
| Muted           | `#8b8b8b`  | `#6b6b6b`  |

Rules of the house:

- One accent only. `#0066cc` is the single permitted colour; everything else is
  greyscale. Do not introduce a second hue.
- Editorial-tech, restrained. The blue is a highlight, not a wash — think a rim
  light, a single garment, or a backdrop tint, not a full duotone.
- Neutral, near-monochrome base so the portraits sit cleanly on both the light
  (`#ffffff`) and dark (`#0d0d0d`) surfaces they'll render against.

## Shane portrait

> File ID: `25d619b2-c699-49ff-b8eb-666ef5db9607`

```
Restyle this portrait to match an editorial-tech design system that is strictly
black, white, and a single blue accent (#0066cc, or #4d9fff against dark
backgrounds). Keep the subject's likeness, pose, and framing intact.

Convert the overall image to a confident near-monochrome treatment: neutral
greys, clean #ffffff-to-#1a1a1a tonal range, no warm or competing colour casts.
Apply the blue as a single restrained highlight only — a cool rim light or a
subtle backdrop tint — never as a full duotone or second accent. The result
should sit cleanly on both a white (#ffffff) and a near-black (#0d0d0d) surface.

Aesthetic: restrained, modern, confident. Sharp but not glossy. Reads as a
byline portrait in a serious editorial publication, not a stock headshot.
```

## Littlebird portrait

> File ID: `7c683660-a459-432a-ba7b-f797dfd5c9e2`

```
Restyle this portrait to match an editorial-tech design system that is strictly
black, white, and a single blue accent (#0066cc, or #4d9fff against dark
backgrounds). Keep the subject's likeness, pose, and framing intact.

Convert the overall image to a confident near-monochrome treatment: neutral
greys, clean #ffffff-to-#1a1a1a tonal range, no warm or competing colour casts.
Apply the blue as a single restrained highlight only — a cool rim light or a
subtle backdrop tint — never as a full duotone or second accent. The result
should sit cleanly on both a white (#ffffff) and a near-black (#0d0d0d) surface.

Match the Shane portrait exactly in treatment, lighting key, and accent weight
so the two read as a matched pair. Aesthetic: restrained, modern, confident —
a byline portrait in a serious editorial publication, not a stock headshot.
```

## Notes

- Run both in the same pass so the lighting and accent weight stay consistent
  across the pair.
- Notion brief with full context:
  https://app.notion.com/p/38f9c2288f55819f8e30cfd399812637
