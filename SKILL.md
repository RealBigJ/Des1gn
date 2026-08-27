---
name: des1gn
description: Browser-first UI reference research for building, modifying, designing, or redesigning any app, website, or frontend; inspect every public catalog item, avoid AI-slop patterns, and integrate customized real code.
---

# Des1gn

Use this skill for every request involving the visual design, layout, interaction, or frontend implementation of an app, website, dashboard, landing page, desktop UI, or mobile UI.

## Complete reference set

Use every source below for every interface task. The list is deduplicated and contains 21 references. The descriptions are routing hints only; they never replace opening and inspecting the actual pages.

- [beautifului.dev](https://beautifului.dev/) - curated UI components and patterns.
- [beUI](https://beui.dev/) - animated React and Next.js components.
- [Rare UI](https://rareui.com/) - distinctive animated React components.
- [Transitions.dev](https://transitions.dev/) - ready-made UI transitions.
- [shadcn/ui](https://ui.shadcn.com/) - open-code component foundation.
- [UI Skills](https://ui-skills.com/) - design playbooks for UI audits, generic AI design fixes, motion, accessibility, and polish.
- [coss/ui](https://coss.com/ui) - Cal.com production-ready design system with accessible React components you own, useful for real product UI without the usual SaaS look.
- [Design System Checklist](https://designsystemchecklist.com/) - practical design-system checklist that prevents random UI styles.
- [ReUI](https://reui.io/components) - 1,000+ free shadcn components and advanced patterns such as data grids, kanban, gantt, filters, and calendars.
- [Kinetics](https://kinetics.colorion.co/) - ready-made spring animations with CSS, React, and AI prompts.
- [Icon Creator](https://iconcreator.dev/) - free browser-based custom icon designer.
- [VibePrompts](https://vibeprompts.dev/) - 256 concrete prompts for UI sections such as dashboards, pricing, auth, onboarding, and hero sections.
- [Animated Buttons](https://animatedbuttons.colorion.co/) - 99 CSS-only button interactions.
- [Component Gallery](https://component.gallery/) - 2,600+ examples from 95 real design systems.
- [Design Systems](https://designsystems.one/) - 88 production design systems with tokens, stacks, and downloadable `design.md` files.
- [Utopia](https://utopia.fyi/) - fluid typography and spacing generator.
- [Open Props](https://open-props.style/) - ready-made design tokens for colors, shadows, radii, spacing, easing, and more.
- [Rauno Interfaces](https://interfaces.rauno.me/) - checklist of small interaction details that make interfaces feel finished.
- [Ibelick Backgrounds](https://bg.ibelick.com/) - copy-paste backgrounds for Tailwind and CSS.
- [Motion Primitives](https://motion-primitives.com/) - reusable motion components for React.
- [21st.dev](https://21st.dev/) - additional ready-made frontend components and patterns.

## Mandatory browser-first audit

Before making UI decisions or editing interface code, inspect all 21 sources above in a real browser. Use in-app browser control, Playwright, or another browser tool that can open and interact with the rendered pages.

Web search is allowed only to discover a source or an otherwise hidden direct URL. A search result, search snippet, AI summary, homepage scan, or link list does not count as inspection. Do not satisfy this requirement by merely searching the nine original URLs.

For each source, follow this exact coverage requirement:

1. Open the homepage and every public catalog, library, category, index, search, sitemap, pagination, and infinite-scroll path that exposes items.
2. Enumerate every unique public detail page for each component, pattern, animation, prompt, token tool, checklist item, example, template, or other reusable resource.
3. Open every enumerated item page individually. Inspect its rendered demo, all visible variants and states, interaction controls, responsive preview, source/code/install views, dependencies, and license or attribution information when available.
4. Follow linked source repositories and documentation when they contain the implementation or additional variants. Do not treat a registry card as a substitute for its detail page.
5. Continue until there are no unvisited item pages or catalog paths left. Do not narrow the audit to components that look relevant before the audit is complete.

Maintain an internal audit ledger with `source`, `url`, `item`, `type`, `visited`, `observed behavior`, `reusability`, and `license` fields. An item whose page was not opened is `not_inspected`, not "covered". If a source is unavailable, blocked, client-only, or impossible to traverse, record the exact blocker and continue without claiming full coverage for that source. Never replace a blocked inspection with invented details.

During the audit, build a compact candidate inventory containing the strongest fitting pieces, their exact source URLs, visual role, interaction behavior, variants, responsive behavior, dependencies, reuse method, and attribution requirements.

## Choose and assemble

Treat the references as a component library of legos. Select components based on the product brief, information hierarchy, existing design language, accessibility, responsive behavior, performance, and the project's actual stack. Combine pieces from different sources when that produces the strongest coherent result, but normalize them into one system instead of creating a collage of unrelated styles.

Prefer the smallest set of components that solves the interface well. Adapt typography, spacing, color, radius, borders, states, motion, density, and responsive rules to the project. Preserve the component's useful behavior while making its appearance and API fit the surrounding codebase.

## Anti-AI-slop prohibitions

Use only the prohibition list in this section. Do not import external design dials, palettes, typography recommendations, framework choices, or other design-direction rules. These are default bans; relax one only when the product brief, brand, real content, or accessibility requirement explicitly calls for it.

- Do not default to AI-purple gradients, dark mesh backgrounds, centered heroes, three equal feature cards, generic glassmorphism everywhere, endless micro-animations, or Inter with slate-900.
- Do not use neon or outer glows by default, oversaturated accents, excessive gradient text, oversized shouting headlines, or custom mouse cursors.
- Do not use three-column rows of identical feature cards.
- Do not fill interfaces with generic placeholder names, generic avatars, fake-perfect numbers, startup-slop brand names, or filler verbs such as "Elevate", "Seamless", "Unleash", "Next-Gen", and "Revolutionize".
- Never hand-roll SVG icons and never build fake product screenshots from rectangles or divs.
- Do not leave copied component-library examples in their untouched default styling.
- Do not add decorative version labels, fake metadata, section-number eyebrows, fake pagination, fake scroll cues, repeated separator dots, or decorative status dots that do not represent real state.
- Do not use em dashes or en dashes as decorative separators or visible copy. Use ordinary punctuation or a regular hyphen when a hyphen is semantically required.
- Do not use forced `<br>` and italic headline splits, vertical rotated text, decorative crosshair or hairline grids, or floating corner paragraphs that exist only to make a page look designed.
- Do not add locale, time, weather, fake live-stock counters, version footers, or other atmospheric metadata unless it represents real product content.
- Do not place decorative pills, tags, or fake photo-credit captions over images.
- Do not use generic "Step 1", "Stage 2", or "Phase 03" labels as decoration, and do not repeat border lines or filled comparison tracks just to make a list or section feel designed.

## Integrate real implementation

Inspect the existing project before choosing an implementation: framework, styling system, component conventions, routing, assets, dependencies, and current responsive/accessibility constraints. Reuse installed primitives when compatible; add a dependency only when it is justified and consistent with the project.

Integrate the adapted component into the actual user flow and existing files. Do not stop at a screenshot, isolated snippet, static mock, or decorative demo. Keep data, actions, loading, empty, error, disabled, focus, hover, keyboard, and mobile states connected to the real application behavior. Never invent product data or API behavior just to make the component look complete; use the project's real contracts or an explicit unavailable state.

If source code is copied or adapted, keep required license notices and attribution, and do not extract proprietary code or assets that the source does not make available for reuse.

## Verify the result

After integration, verify the rendered result at the relevant viewport sizes and interaction states. Check that the component is visually coherent with the rest of the app, accessible by keyboard, usable on touch/mobile, responsive, and free of console/build errors. Revisit the selected source pages if an implementation detail is unclear. Report the audit coverage per source, the exact selected reference URLs, and every source or page that could not be inspected.

The user's product requirements and the existing project constraints take precedence over copying a reference literally. The goal is an authored, customized implementation informed by the references, not a pasted gallery.
