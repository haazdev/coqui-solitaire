# Changelog

All notable changes to Coquí Solitaire will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.1.0] - 2025-08-10

### Fixed
- Undo button now properly tracks deck operations (dealing and resetting)
- Fixed bug where cards from columns would incorrectly return to deck on undo
- Fixed visual glitch where cards appeared face-up in stock pile after undo
- Improved waste pile visibility state management during undo operations

### Changed
- Enhanced undo system to support three operation types: DECK_DEAL, DECK_RESET, and regular moves
- Added safety check to ensure stock pile cards are always rendered face-down
- Improved card position restoration when undoing deck operations

### Technical
- Reorganized project structure with proper asset directories
- Added comprehensive documentation (README, LICENSE, CHANGELOG)
- Created package.json with Farcade platform metadata

## [1.0.0] - 2025-08-09

### Added
- Initial release of Coquí Solitaire
- Classic Klondike solitaire gameplay
- Puerto Rican theme with tropical backgrounds
- Coquí frog sound effects
- Mobile-optimized touch controls
- Drag & drop card movement
- Double-tap auto-move functionality
- Traditional solitaire scoring system
- Interactive tutorial for new players
- 8-bit pixel art aesthetic
- Undo/redo functionality for card moves
- Responsive design for mobile and desktop
- Farcade SDK integration
- Haptic feedback support

### Features
- 52-card standard deck
- 4 foundation piles (build up by suit)
- 7 tableau columns (build down by alternating colors)
- Stock pile with 3-card draw
- Waste pile management
- Score tracking
- Move counter
- Game timer
- Give up / Rest option
- Help button with tutorial

### Platform Support
- Remix.gg / Farcade gaming platform
- Mobile Safari (iOS 14+)
- Chrome Mobile (Android)
- Desktop browsers (Chrome, Safari, Firefox, Edge)

## [0.1.0] - 2025-08-01 (Pre-release)

### Added
- Basic game prototype
- Initial card rendering system
- Basic drag and drop implementation
- Foundation game logic