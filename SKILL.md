# AI Resume Adapter Bot — Visual Design Skill

## Direction
**ATS Command Center**: dark recruiter / cyber dashboard. Confident, professional, technological. Avoid generic purple gradients and default “tool UI” aesthetics.

## Tokens (CSS variables)
- **Background**: graphite / near-black (`--bg-base`).
- **Surfaces**: deep slate + glass (`--surface-glass`, `--panel`).
- **Accents**: cold blue (AI/analysis), green (approval/match), amber (warnings), red (risk).
- **Typography**: technical sans + monospace for labels/headings (`--font-display`, `--font-body`).
- **Elevation**: layered shadows (`--shadow-sm/md/lg`), subtle glow for AI accents.

## Hierarchy
1. Hero title — largest, monospace display.
2. Section title — `h2` / `.type-section`.
3. Card title — `h3` / `.type-card`.
4. Body — `.type-body` / default paragraph.
5. Labels — `.type-label`, `.type-small`.

## Motion
CSS-only: staggered hero lines, card entrance, hover lift, dashboard scan line. Respect `prefers-reduced-motion`.

## Constraints
Do not remove or rename functional IDs, form fields, or workflow logic. Visual layers only.
