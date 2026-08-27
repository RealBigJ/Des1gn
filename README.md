# Des1gn

Probably the easiest way to make your frontend look 10x better without being a designer.

I’m not a designer, so instead of asking AI to invent the entire UI from scratch, I made a skill called Des1gn. It tells the agent where to look, how to inspect the components, and how to build with the right pieces like Lego.

The workflow is simple:

1. Give the agent the Des1gn skill.
2. Let it inspect the references and their components.
3. Let it pick what fits your project.
4. Let it integrate and customize the code.

Des1gn gives the agent a complete reference-driven workflow for turning high-quality UI references into a coherent, customized interface for any app, website, dashboard, landing page, desktop interface, or mobile interface.

## References

For every interface task, Des1gn opens and inspects every public catalog and item page from this full reference set. Web search alone does not count.

- [beautifului.dev](https://beautifului.dev/) - curated UI components and patterns.
- [beUI](https://beui.dev/) - animated React and Next.js components.
- [Rare UI](https://rareui.com/) - distinctive animated React components.
- [Transitions.dev](https://transitions.dev/) - ready-made UI transitions.
- [shadcn/ui](https://ui.shadcn.com/) - open-code component foundation.
- [UI Skills](https://ui-skills.com/) - design playbooks for UI audits, generic AI design fixes, motion, accessibility, and polish.
- [coss/ui](https://coss.com/ui) - Cal.com production-ready design system with accessible React components you own.
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

It compares components, variants, states, and interactions, then adapts the best-fitting pieces to the project’s stack, responsive behavior, accessibility needs, and existing design system. Its anti-AI-slop checks focus on prohibitions, not prescriptive visual-direction rules.

## Install

```bash
npx skills add RealBigJ/Des1gn
```

## Update

After installing Des1gn, pull the latest version with:

```bash
npx skills update des1gn
```

Once installed, it can be discovered automatically or invoked explicitly:

```text
Use $des1gn for this interface task.
```
