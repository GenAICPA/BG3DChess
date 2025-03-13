# CLAUDE.md - Musical Chess 3D Assistant Guide

## Build Commands
- Development server: `npm run dev`
- Build project: `npm run build`
- Preview build: `npm run preview`

## Testing
- Lint code: `npm run lint`
- Type check: `npm run typecheck`

## Code Style Guidelines
- Use TypeScript for type safety and interfaces
- Follow camelCase for variables/functions, PascalCase for classes/interfaces
- Group imports: built-in, external, internal, relative
- For 3D objects, position using (x, y, z) coordinates where:
  - x: horizontal position (left/right)
  - y: vertical position (up/down)
  - z: depth position (front/back)
- Chess coordinate system:
  - Row: 0-7 (white at 0-1, black at 6-7)
  - Column: 0-7 (from left to right)
- Musical instruments representations:
  - King: Banjo
  - Queen: Guitar
  - Bishop: Dobro
  - Knight: Mandolin
  - Rook: Double Bass
  - Pawn: Fiddle