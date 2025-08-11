# Architecture Overview

## File Structure

- `public/` — Static assets (icons, images, sounds)
- `src/` — Source code (HTML, JS, CSS)
- `docs/` — Documentation
- `README.md`, `LICENSE`, etc. — Project metadata

## Game Loop
- Uses requestAnimationFrame for smooth rendering
- Handles input, updates game state, and redraws each frame

## Asset Management
- Loads images and sounds from `public/`
- Fallbacks for missing assets

## Event Handling
- Pointer events for drag, drop, and tap
- Farcade/Remix SDK for platform integration

## Security
- No secrets in code
- All assets are static and safe for web deployment 