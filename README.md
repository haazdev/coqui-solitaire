# Coquí Solitaire

A Puerto Rican-themed Klondike solitaire game designed for the Remix.gg/Farcade gaming platform. Features tropical visuals, coquí frog sounds, and classic solitaire gameplay optimized for mobile and desktop play.

## Game Features

- **Classic Klondike Solitaire**: Traditional 52-card solitaire gameplay
- **Puerto Rican Theme**: Tropical backgrounds and coquí frog sound effects
- **Mobile Optimized**: Touch-friendly controls with drag & drop and double-tap actions
- **Undo System**: Full undo/redo functionality including deck operations
- **Traditional Scoring**: Classic solitaire scoring system
- **Tutorial**: Interactive tutorial for new players
- **8-bit Aesthetic**: Retro pixel art style with modern polish

## How to Play

### Goal
Move all 52 cards to the 4 foundation piles (top), building each suit from Ace to King.

### Controls
- **Drag & Drop**: Move cards between piles
- **Double-Tap**: Auto-move cards to valid positions
- **Tap Deck**: Draw 3 new cards from stock
- **Undo Button**: Reverse last move
- **Help Button**: View tutorial

### Rules
- **Foundations**: Build up by suit (A→2→3...K)
- **Tableau**: Build down by alternating colors (red on black, black on red)
- **Empty Columns**: Only Kings can be placed on empty tableau spaces
- **Stock**: Draw 3 cards at a time, cycle through deck when empty

## Technical Details

### Platform
- **Target**: Remix.gg / Farcade gaming platform
- **Framework**: Vanilla JavaScript with HTML5 Canvas
- **SDK**: Farcade SDK integration for scoring and haptic feedback

### Browser Support
- Chrome 90+
- Safari 14+
- Firefox 88+
- Edge 90+
- Mobile Safari (iOS 14+)
- Chrome Mobile (Android)

### Performance
- 60 FPS target framerate
- Optimized for mobile devices
- Minimal network requests (assets hosted on CDN)
- < 100KB total game size (excluding images)

## Development

### Project Structure
```
coqui-solitaire/
├── index.html          # Main game file
├── assets/
│   ├── images/        # Game graphics
│   └── sounds/        # Audio files (future)
├── src/               # Source files (if modularized)
├── docs/              # Documentation
├── README.md          # This file
├── LICENSE            # MIT License
└── package.json       # Project metadata
```

### Local Development
1. Clone the repository
2. Open `index.html` in a web browser
3. For testing with Farcade SDK, use a local web server:
   ```bash
   python3 -m http.server 8000
   # or
   npx serve
   ```

### Deployment
The game is designed to be deployed on Remix.gg/Farcade platform. Files are optimized for CDN delivery with proper caching headers.

## Recent Updates

### Version 1.1.0 (Aug 2025)
- Fixed undo button bug where deck operations weren't properly tracked
- Fixed visual glitch with face-up cards appearing in stock pile
- Improved waste pile card visibility management
- Enhanced animation smoothness for card dealing

### Version 1.0.0 (Aug 2025)
- Initial release
- Core solitaire gameplay
- Puerto Rican theme implementation
- Mobile optimization
- Tutorial system

## Credits

- **Developer**: haaz.eth (https://haaz.dev)
- **Repository**: https://github.com/haazdev/coqui-solitaire
- **Theme**: Puerto Rican culture and coquí frogs
- **Platform**: Built for Remix.gg / Farcade
- **Testing**: Community playtesting feedback incorporated

## License

MIT License with Attribution Requirement - See LICENSE file for details.

When using this software, you must provide visible attribution including:
- "Coquí Solitaire by haaz.eth"
- Link to: https://github.com/haazdev/coqui-solitaire

## Feedback & Bug Reports

Please report issues through:
- GitHub Issues (when repository is public)
- Remix.gg community forums
- Direct feedback in Farcade app

## Playtesting Acknowledgments

Special thanks to our playtesters:
- joker4fun - Critical undo button bug discovery
- tuanteku - Gameplay enhancement suggestions
- ireside.eth - Functionality validation
- kisscosme - General feedback
- sangbuiliemkhiet - UX improvement suggestions

---

*Coquí Solitaire - Bringing the sounds of Puerto Rico to classic card gaming*