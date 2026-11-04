---
name: new-age-lounge-editor
description: "Professional nightclub-style photo editing and logo integration for New Age Lounge. Use for: applying high-end urban color grading, accurate logo watermarking, and Instagram (4:5) optimization."
---

# New Age Lounge Photo Editor

This skill provides a standardized workflow for editing photos to match the New Age Lounge's premium brand aesthetic. It focuses on subtle, high-end color grading and precise logo integration.

## Core Principles

1. **Subtle Professionalism**: Avoid "doing too much." The edit should enhance the existing club atmosphere without adding fake neon elements or excessive AI styling.
2. **Logo Integrity**: The "New Age Lounge" logo must remain 100% accurate. Do not allow AI to reimagine, alter, or "integrate" the logo's design elements. It must be a clean watermark.
3. **Subject Preservation**: Never alter human features, skin textures, or identities.
4. **Instagram Optimization**: Always target a **4:5 aspect ratio** to maximize feed visibility.

## Workflow

### 1. Preparation
If photos are larger than 2048px on the long edge, resize them locally before processing to ensure AI precision.

### 2. Style Application
Apply a professional nightclub color grade:
- **Contrast & Lighting**: Deepen shadows while ensuring subjects are well-lit and "pop."
- **Color Balance**: Maintain a moody, urban vibe with natural club lighting (warm ambers, subtle blues/purples).

### 3. Logo Integration
- **Asset**: Use `/home/ubuntu/skills/new-age-lounge-editor/templates/logo.jpg`.
- **Placement**: Top right corner.
- **Style**: Clean, professional watermark.

## Tool Guidance (media_generation)

When invoking `generate_image_variation`, use this exact prompt structure:

> "Apply a subtle, professional nightclub-style color grade to this photo. Enhance the lighting and contrast for a polished, high-end look while keeping the original scene's integrity—do not over-stylize or add excessive neon. 
> 
> **CRITICAL LOGO INSTRUCTIONS:** Place the provided 'New Age Lounge' logo cleanly in the top right corner as a professional watermark. DO NOT alter the logo's design, text, or elements in any way; it must be represented exactly as shown in the reference logo image. 
> 
> **CRITICAL SUBJECT INSTRUCTIONS:** Preserve all human features, skin textures, and the subject's identity perfectly. Do not apply AI smoothing or feature alterations. Output in a 4:5 aspect ratio for Instagram."

## Resources

- Logo Template: `templates/logo.jpg`