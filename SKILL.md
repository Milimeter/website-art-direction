---
name: website-art-direction
description: Art-direct, build, and refine websites and web apps, including landing pages, portfolios, dashboards, and admin interfaces. Use for visual design work on new or existing web surfaces, including purposeful motion and first-pass browser review.
---

# Website art direction

Aim for a first pass the user could plausibly ship. Give the site a distinct visual point of view and use motion where it rewards attention. Use references when available and move forward from the brief when they are absent.

## Choose the direction

Identify what the visitor came to do on the specific surface. A public launch page and the admin area of the same product may need different treatments. Inspect the existing interface, brand assets, and components when available. Preserve established identity and behavior for a refinement, and use them as constraints for a new surface in an existing product.

Choose one direction by default. Ground the composition, type hierarchy, and focal point in the product, audience, and content. Translate any reference into a specific technique you can adapt. When the user asks to compare directions, vary the composition and focal point as well as the styling.

- **Public and portfolio pages.** Decide what the first screen should communicate and what the eye should land on. Use a real product moment, relevant imagery, or the work itself as the focal point. Build the hero and the transition into the next section early. If the still could belong to five competitors, revisit the composition or focal asset before refining motion.
- **Dashboards, admin areas, and web apps.** Start from the most important task and make its main view work with representative data. Give the primary action, key status, and next step a clear place. Use typography, alignment, density, and consistent states to give a table or workspace character. Check the meaningful edge states early, such as no results after filtering, a failed save, or a long row label. For an existing surface, isolate the few views or components whose hierarchy, density, or feedback actually needs work.

When the user calls part of an existing site basic, inspect that part in context and identify the concrete visual or interaction weakness. Treat the public site and admin as separate surfaces and base changes on what you can inspect. If a private view is essential and unavailable, ask for screenshots or an authorized preview and continue with accessible views.

## Give motion a job

On a public page, choose a signature beat when the content supports it. Show an action and its result in a product demo, or use a change in scale or crop to reveal portfolio work. In an app, use restrained motion to communicate what changed, such as a panel opening from its trigger, a row moving after reordering, or a save completing in place. Keep frequent actions immediate. Make the resting frame meaningful and preserve the same content, controls, and state feedback with reduced motion.

## Use the specialists

Use this skill as the entry point. Read the relevant installed specialist's SKILL.md before making the decisions it covers. Follow the brief and project design system where guidance overlaps. Report which specialists informed the result.

| Work | Specialist and when to use it |
| --- | --- |
| New or materially redesigned marketing page | Use Taste Skill (`design-taste-frontend`) before choosing the concept. Apply its art direction and image guidance. Use its browser checker when the runtime and project support it. |
| Compare visual directions | Use Oil UI for side-by-side options. For targeted enhancements, keep variants within the requested section and compare them with the current version. |
| Meaningful motion | Use Emil Kowalski's `emil-design-eng` for motion decisions and his `animate` playbook for substantial new interactions. Use `review-animations` when explicitly invoked. |
| Focused quality issue on an existing interface | Use Impeccable after the visual direction is settled. Choose the smallest relevant pass, such as critique for hierarchy, audit for accessibility or responsive issues, or polish for details. |
| Components for a React app | When the project uses Astryx, consult its docs or CLI for APIs, theming, and patterns. Consider it for a new React 19+ app when choosing the stack is in scope. Keep the established library for a scoped enhancement. |

### Setup and availability

Use the Codex skill installer to install [Oil UI](https://github.com/oil-oil/oil-ui) from its repository root, [Taste Skill](https://github.com/Leonxlnx/taste-skill) from `skills/taste-skill`, and [Emil's skills](https://github.com/emilkowalski/skills) from `skills/emil-design-eng`, `skills/animate`, and `skills/review-animations`. [Impeccable](https://github.com/pbakaus/impeccable) is a separate Codex skill. [Astryx](https://github.com/meta/astryx) is a project dependency. Follow its setup guide and the project's package manager when the project adopts it.

If a specialist is missing, continue with this workflow and report the gap. Combine overlapping visual checks where their coverage is equivalent.

## Review in the browser

For a public page, inspect the desktop and phone compositions and play the main motion at normal speed. For an app, run the main task with representative data, check keyboard use and the important states touched by the work, and verify the intended layout at relevant widths. Check reduced motion where animation is present.

Ask what the eye lands on first, whether the visitor can take the next step, and what makes the surface feel specific to the product. Fix the biggest visible issues in one batch and verify the affected views. Report important checks that could not run. When evaluating the skill against an earlier Codex build, keep the brief and assets constant and capture the first pass before user feedback.
