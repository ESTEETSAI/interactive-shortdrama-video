# interactive-shortdrama-video

Codex skill for generating branching interactive short-drama workflows in Chinese, including topic selection, branch maps, character sheets, video prompt planning, and provider-aware video generation handoff.

## What It Does

- Guides users through background, theme, and setup selection before script generation.
- Produces branching story plans for interactive short-drama episodes.
- Uses image generation for branch visualization and character reference sheets.
- Requires character confirmation before submitting video generation jobs.
- Supports provider planning for fal.ai, Replicate, Kling, Runway, Luma, Crate, and related image-to-video workflows.

## Installation

Copy this folder into your Codex skills directory:

```bash
mkdir -p ~/.codex/skills
cp -R interactive-shortdrama-video ~/.codex/skills/
```

Then restart Codex or reload skills.

## Files

- `SKILL.md` - the skill definition and workflow instructions.
- `assets/douyin-zaizai-style/` - optional reference images for the built-in Douyin-style character sheet mode.

## Notes

Video generation can consume credits on third-party providers. The skill requires a generation plan and confirmation before submitting real jobs.
