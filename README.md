# Musical Chess 3D

A 3D chess game with musical instrument pieces, built with Three.js and TypeScript.

## Musical Instrument Pieces

The chess pieces are represented by musical instruments:
- King: Banjo
- Queen: Guitar
- Bishop: Dobro
- Knight: Mandolin
- Rook/Castle: Double Bass
- Pawn: Fiddle

## Installation

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build
```

## Gameplay

- **Left click**: Select/move a piece
- **Right click + drag**: Rotate the view
- **Mouse wheel**: Zoom in/out
- **R key**: Reset the view

## Chess Rules

The game follows standard chess rules, including:
- Castling (King and Rook special move)
- En passant captures
- Pawn promotion to Queen
- Check and checkmate detection

## Technologies

- Three.js for 3D rendering
- TypeScript for type-safe code
- Vite for fast development and building