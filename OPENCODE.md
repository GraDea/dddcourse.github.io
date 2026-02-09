# DDDevotion Project Notes

## Product Intent

- Build a focused Russian-language landing page for a Domain-Driven Design course.
- Optimize for trust and clarity rather than flashy interactions.
- Treat the page as a waitlist funnel: explain value, show structure, prompt action.

## Audience Priorities

- Primary readers: software architects, senior developers, tech leads, product owners.
- They care about practical outcomes: architecture quality, team alignment, predictable delivery.
- Messaging should stay concrete, professional, and business-aware.

## Content Strategy

- Hero states transformation: from ad-hoc design to domain-driven architecture.
- Feature cards map to core DDD areas: Ubiquitous Language, Strategic Design, Tactical Patterns.
- Curriculum communicates progression: mindset -> strategy -> tactical modeling -> enterprise adoption.
- Testimonial should reinforce organizational impact, not personal hype.

## Visual Direction

- Dark enterprise baseline: background `#0f172a`, accent `#8b5cf6`.
- High contrast, generous spacing, restrained decoration.
- No animations or transitions; static confidence is part of the brand voice.
- Mobile readability is mandatory: stacked sections and clear CTA visibility.

## Technical Constraints

- Stack: GitHub Pages + Jekyll.
- Main editable files: `index.md`, `assets/css/custom.css`, optional `_includes`/`_layouts`.
- Keep dependencies minimal and avoid JS unless it has a clear conversion purpose.

## Publishing Workflow

- Working branch for publishing: `gh-pages`.
- Make atomic commits with clear intent in message.
- Validate final rendering on desktop and mobile after each significant layout update.
