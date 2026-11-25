# Photo to Oil Painting Poster

A reusable AI skill that transforms photographs into impressionist oil-painting posters with oversized image-filled typography.

## Visual system

- Vertical 3:4 posters with warm ivory negative space
- Luminous impasto brushwork, warm highlights and cool chromatic shadows
- Giant condensed uppercase headlines filled with continuous painted scenery
- Thin handwritten subtitles and scene-adaptive foreground occlusion
- Preservation of recognizable source subjects and spatial relationships

## Usage

Load the repository as a skill in a compatible AI environment, following that host's import instructions. The entry point is [SKILL.md](SKILL.md). Alternatively, provide the instruction files to an image-capable assistant with your source photo.

Example: “Use photo-to-oil-painting-poster to turn this photo into a poster. Choose the headline and subtitle automatically.”

For precise wording: “Use photo-to-oil-painting-poster. Headline: ESCAPE. Subtitle: Away from it all.”

The host must provide image-generation capability. This repository does not include a model, API keys, or standalone renderer.

## Structure

- [SKILL.md](SKILL.md): workflow and defaults
- [Style guide](references/style-guide.md)
- [Composition rules](references/composition-rules.md)
- [Typography rules](references/typography-rules.md)
- [Quality checklist](references/quality-checklist.md)
- [Prompt template](templates/master-prompt.md)
- [Example index](examples/index.md): BLOOM, ALPINE, STROLL, COAST

## Status

v1.0.0 initial version. One new-photo generation was tested in the development conversation. Independent-session compatibility, platform-specific installation and batch consistency have not yet been validated. The written examples are usable even when paired image files are unavailable.

## 中文说明

将照片转为印象派厚涂油画海报，自动生成主标题与手写副标题，保留原图主体。默认 3:4 竖版。支持自定义标题、批量处理及仅生成提示词。宿主需提供图像生成能力。

## Rights

No open-source license has been selected yet. Reference photographs and artwork are not automatically licensed for redistribution or commercial reuse.
