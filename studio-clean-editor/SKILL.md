---
name: studio-clean-editor
description: "Premium photo refinement for high-end brand and streetwear aesthetics. Transforms raw captures into professional 'Studio Clean' assets with pure white backgrounds, cinematic lighting, and strict anatomical preservation. Use for: studio cleanup, background replacement, color grading, and texture sharpening for fashion and lifestyle photography."
---

# Studio Clean Editor

This skill provides a specialized workflow for creating professional, brand-ready assets with a focus on the "Studio Clean" aesthetic—a high-contrast, polished look popular in premium streetwear (e.g., Nike, Supreme).

## Core Principles

1. **Anatomical Integrity**: NEVER alter human features. Preserve the subject's identity, skin texture, and body proportions 100%.
2. **Pose Preservation**: Maintain the exact pose and composition of the original shot unless explicitly asked to change it.
3. **High-Key Studio Aesthetic**: Clean, pure white backgrounds with realistic floor shadows that ground the subject.
4. **Cinematic Contrast**: Deep, rich blacks and crisp, bright highlights.

## Workflow

### 1. Analysis & Style Loading
Before editing, review the subject's environment and the desired output.
- **Read Style Guide**: Always read `/home/ubuntu/skills/studio-clean-editor/references/style_guide.md` for the latest prompt templates and aesthetic definitions.
- **Reference Selection**: Identify a "Studio Clean" reference image to guide the AI's color grading and lighting.

### 2. Prompt Engineering
Use the `generate_image_variation` tool with the following logic:
- **Style Name**: Always refer to the style as "Studio Clean".
- **Background Command**: Explicitly command a "pure, clean studio white" background.
- **Shadow Preservation**: Instruct the tool to "maintain realistic floor shadows."
- **Integrity Guardrail**: Include the critical instruction: "**Do not alter any human features, body shape, or skin texture. Preserve the subject's identity, pose, and anatomical integrity 100%.**"

### 3. Professional Finishing
- **Instagram Optimization**: Default to a **4:5 aspect ratio** for portrait shots to maximize social media impact.
- **Texture Sharpening**: Specifically mention sharpening the textures of denim, sneakers, and specialized materials like rugs or mats.

## Tool Guidance (media_generation)

When using `generate_image_variation`, always provide:
1. The **original photo** to be edited.
2. A **reference image** that exhibits the desired "Studio Clean" lighting and color grading.
3. A detailed prompt based on the templates in the `references/style_guide.md`.
