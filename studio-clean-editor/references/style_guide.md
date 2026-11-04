# Studio Clean Style Guide

This guide defines the "Studio Clean" aesthetic used for premium streetwear and brand photography.

## Core Aesthetic
- **Background**: Pure, high-key studio white (#FFFFFF).
- **Lighting**: High-contrast, cinematic lighting that creates deep blacks and crisp, bright highlights.
- **Shadows**: Realistic, soft floor shadows that ground the subject.
- **Textures**: High sharpening on fabrics (denim, knit, leather) and materials (sneaker soles, rug textures).

## Prompt Templates

### Standard Refinement
Use this for transforming a raw indoor shot into a professional asset.
> "Apply a 'Studio Clean' edit to this photo. Transform the background into a pure, clean studio white while maintaining realistic floor shadows and [specific floor texture like rug/mat]. Enhance the lighting and color grading to a premium brand standard (e.g., Nike, High-end Streetwear), with deep blacks and crisp, bright whites. **CRITICAL: Do not alter any human features, body shape, or skin texture. Preserve the subject's identity, pose, and anatomical integrity 100%.** Sharpen the textures of [clothing/sneakers]."

### Strict Pose Preservation
Use this when the AI attempts to change the subject's orientation or position.
> "Apply a 'Studio Clean' background and lighting edit to this specific image. **CRITICAL: Maintain the exact pose, orientation, and composition of the subject as seen in the original photo.** Do not change the subject's clothing or seated/standing position. Transform ONLY the background into a pure, clean studio white while preserving realistic floor shadows. Preserve all human features and anatomical integrity 100%."

## Visual References
When applying this style, always include a high-quality "Studio Clean" reference image in the `references` parameter of the `generate_image_variation` tool to guide the color grading.
