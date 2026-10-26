---
name: web-style
description: Plan, review, or implement a website's visual style and interface presentation. Use when the task involves layout, typography, color, components, responsive styling, or a visual refresh.
---

# Website style

Shape a website's visual system around the project brief, users, content, and existing technical setup. A style direction should make the site's purpose easier to understand and act on.

## Inspect the project first

Read the project brief, client constraints, brand materials, prior project decisions, and relevant page content. Inspect the current site or codebase before proposing changes. Identify the primary audience, key action, page types, target devices, languages, and technical limits. Keep project information in its authorized workspace.

When the client has a design system, component library, or existing visual identity, use it as the starting point. Check whether the existing system is documented in the repo, Drive folder, design file, or site. Do not invent a new visual language before checking for approved rules.

## Define a usable style direction

Translate the brief into a small set of decisions that can be applied consistently:

- visual character and why it fits this audience and offer;
- color roles, type hierarchy, spacing scale, grid, borders, imagery, and interaction states;
- how the visual system supports scanning, trust, conversion, and the content's hierarchy;
- where the system needs variants for mobile, longer content, localization, or accessibility preferences.

Treat trends as optional references and judge each idea against the brief. Avoid effects, motion, unusual navigation, or decoration that obscures content, slows the site, conflicts with the brand, or complicates a task. Competitor review can reveal market conventions and opportunities. Keep the resulting design original and use approved assets.

## Implement or review

Prefer the project's existing tokens, components, and CSS conventions. Keep changes scoped to the requested pages or shared components. Preserve semantic content, headings, links, forms, and SEO fields unless the user asks to change them. Use responsive layouts rather than fixed desktop-only dimensions, and ensure visual order does not conflict with reading or keyboard order.

Review representative pages at narrow and wide viewport sizes. Check text readability, contrast, focus visibility, hover and active states, image crops, overflow, and long translated strings. Follow the applicable accessibility standard and test with more than automated checks when the change affects access or interaction. Consult [the source index](references/sources.md) for current standards, design-system guidance, and dated research. Treat arXiv preprints as provisional evidence, and confirm the version and jurisdiction before treating any guidance as binding.

## Handoff

Provide the chosen style decisions and the implemented or recommended changes in terms the project team can apply. Mention only material limitations, unresolved dependencies, or deviations from the brief. When no implementation was requested, give a concise visual specification rather than modifying the site.
