---
name: photo-to-oil-painting-poster
description: Convert uploaded photos into a coherent series of impressionist oil-painting posters with oversized image-filled uppercase typography, ivory negative space, handwritten subtitles, and foreground occlusion. Use for photo-to-poster, travel art posters, and matching the supplied paired visual references.
---
# Photo to Oil Painting Poster

## Contract
Turn each source photo into one finished poster when generation is requested. When asked only for a prompt or analysis, return that instead. Default: vertical 3:4, English headline and subtitle, full bleed, no additional text. User-specified wording and aspect ratio override defaults. Do not ask for optional details; infer them from the source. Never claim generation or inspection occurred if unavailable.

## Workflow
1. Read `references/style-guide.md`, `references/composition-rules.md`, and `references/typography-rules.md`.
2. Inspect the actual source image. Identify key subjects, spatial relationships, perspective, foreground/midground/background, sky, colors, mood, and potential occluders. For people preserve count, pose, clothing and recognizable appearance; for landmarks preserve geometry. Do not infer an unverified location as fact.
3. Select the closest paired example using `examples/index.md`. Inspect its source and target images if present and image viewing is supported. Use target for style/layout only; never transplant its subjects into the new source. If images cannot be inspected, use the written reference notes and disclose the limitation when relevant.
4. Choose a composition strategy and copy. Follow exact user text; otherwise choose a single expressive uppercase English word, preferably 4–7 letters, and a complementary short handwritten phrase. Do not recycle reference titles indiscriminately.
5. Fill `templates/master-prompt.md` with scene-specific instructions. Replace all placeholders. Use a single coherent prompt and the actual source image; attach the closest target reference where supported, explicitly distinguishing content from style.
6. Invoke the available image generation/editing capability if requested. If unavailable, return the ready-to-use prompt and explain that no image was generated. Do not substitute an SVG or mockup. For a batch, process each photo independently and maintain consistent typography, cream background, rendering and hierarchy. Do not combine into a collage unless asked.
7. Inspect output against `references/quality-checklist.md` if possible. If critical failures exist, use a targeted revision or regeneration where supported; do not promise perfect results or unlimited retries. Deliver the finished image(s), noting any remaining material deviations.

## Priority
Exact copy and recognizable source content > coherent typography mask and legibility > painterly style > decorative enhancements. A deliberate user override takes precedence over stylistic defaults. Keep optional creative changes modest; never add unrelated landmarks, people, or events.

## Optional controls
aspect_ratio=3:4; painting_intensity=high; source_fidelity=high; foreground_overlap=moderate; lighting=warm daylight; headline_width=90–96% of canvas. These are descriptive targets, not native model parameters. Preserve time-of-day or weather when essential to the photo or requested.
