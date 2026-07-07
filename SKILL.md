---
name: google-xhs-tutorial-carousel
description: Use when creating or prompt-writing clean Google-style Xiaohongshu tutorial carousel images, foreign trade SOP cards, search-command explainers, tool tutorials, knowledge cards, infographic slides, or 3:4 vertical educational posts with white cards, Google colors, big Chinese headings, icons, search bars, steps, checklists, and page numbers.
---

# Google XHS Tutorial Carousel

## Overview

Create clean, trustworthy, Google-inspired 3:4 Xiaohongshu tutorial carousel cards. The style is best for practical tutorials, SOPs, foreign trade workflows, search commands, tool lessons, and list-based knowledge posts.

Core principle: make each page feel like a collectible mini lesson, not a poster. Use large readable Chinese headings, white rounded cards, light shadows, blue-led Google color accents, simple line icons, search-bar modules, and consistent page numbers.

## Use This For

- 3:4 vertical Xiaohongshu carousel covers and inner pages.
- Google search command lessons, buyer-finding SOPs, export trade tutorials, AI/tool tutorials, and workflow cards.
- Prompt generation for image tools.
- Design specs for a designer or frontend/card renderer.
- Multi-page educational carousels with consistent visual identity.

Do not use this for high-drama celebrity covers, dark tech posters, realistic product ads, or dense long-form documents.

## Workflow

1. Collect the topic, audience, and page count.
2. Decide the page role: cover, logic overview, command cards, combo search, lookup table, website category, deeper research, contact-finding, case study, or final SOP.
3. Use `references/visual-system.md` for the fixed style system.
4. Use `references/page-templates.md` for the page layout recipe.
5. Write one prompt per page. Keep the shared style constant and vary only the content module.
6. If generating images, use the active image generation skill/tool after prompt shaping.
7. Validate every page with the checklist below before calling it done.

## Content Structure

For a 10-page tutorial set, prefer this arc:

1. Cover: topic promise and audience.
2. Logic: before action, explain the thinking.
3. Basic commands: 4-6 small command cards.
4. Combination searches: 3 larger search examples.
5. Lookup table: suffixes, domains, terms, or filters.
6. Source categories: 4 kinds of websites or channels.
7. Deeper sources: distributors, associations, exhibitions.
8. Contact finding: email, contact pages, social media, directories.
9. Case studies: 3 examples users can copy.
10. SOP: final process plus common pitfalls.

Use fewer pages when the topic is narrower, but keep the same rhythm: promise -> logic -> methods -> examples -> summary.

## Prompt Output Format

When the user wants prompts, return:

```text
Shared style:
<fixed style system for the whole carousel>

Page 01 - <role/title>:
<complete prompt>

Page 02 - <role/title>:
<complete prompt>
```

For a single page, return only that page prompt plus a short note listing aspect ratio, exact title text, and template type.

## Prompt Rules

- Keep all visible Chinese text exact and short.
- Use Chinese bold sans-serif typography; make the main title the strongest element.
- Use English examples inside search bars when the topic is search, B2B, SaaS, or tools.
- Do not overload one page. Use 3-6 modules per page.
- Use blue as the main accent; use red, yellow, and green only for small meaning-coded accents.
- Prefer simple line icons inside soft circular backgrounds.
- Keep cards aligned to a clear grid. Avoid decorative chaos.
- Include bottom page number such as `03/10` in a rounded pill.
- Avoid fake brand marks unless the user explicitly wants Google-themed visuals. When using Google-style colors, do not imply official Google endorsement.

## Quality Checklist

- 3:4 vertical ratio is explicit.
- White or very pale blue-gray background feels clean.
- Main title is readable at phone thumbnail size.
- Page has one primary teaching point.
- Cards have consistent rounded corners, shadows, spacing, and icon style.
- Google color accents are present but not noisy.
- Search bars, checkmarks, arrows, and labels are visually organized.
- Decorative rings/dots stay in the corners and do not compete with content.
- Bottom page number is present and correct.
- No tiny dense text, distorted logos, unreadable UI, or random extra copy.

## Resources

- `references/visual-system.md`: fixed colors, typography, layout, icon, card, and decoration rules.
- `references/page-templates.md`: reusable prompt recipes for covers and inner-page layouts.
