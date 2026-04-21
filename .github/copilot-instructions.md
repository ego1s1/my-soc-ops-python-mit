# Copilot Instructions

## Design Guide

### Pixel Arcade Style Theme

Soc Ops uses a retro 8-bit arcade aesthetic inspired by classic arcade games like Pac-Man and Space Invaders. This distinctive visual style creates an immersive gaming experience while maintaining usability.

#### Core Design Principles
- **Pixel Fonts**: Use "Press Start 2P" for authentic 8-bit typography
- **Neon Color Palette**: Primary colors are cyan (#00FFFF), magenta (#FF00FF), and yellow (#FFFF00) on black backgrounds
- **Hard Edges**: No rounded corners - everything has sharp, pixel-perfect edges
- **Thick Borders**: 4px borders for arcade cabinet feel
- **Retro Effects**: CRT scanlines, neon glows, and subtle animations

#### Color Usage
- **Cyan**: Primary text, borders, and interactive elements
- **Magenta**: Accents, free space highlighting
- **Yellow**: Bingo states, important notifications
- **Green**: Marked squares
- **Red**: Error states or warnings
- **Black**: Primary background
- **Gray**: Secondary backgrounds and inactive elements

#### Typography
- **Font Family**: 'Press Start 2P', monospace
- **Sizes**: Use pixel-based sizing (8px, 10px, 12px, etc.) for crisp pixels
- **Effects**: Neon glow for titles, flickering for emphasis
- **Case**: ALL CAPS for retro arcade feel

#### Interactive Elements
- **Buttons**: Pixel-style with outset/inset borders, press animations
- **Squares**: Chunky pixels with hover glows
- **Animations**: Flicker for attention, pulse for calls-to-action
- **Feedback**: Immediate visual feedback on interactions

#### Layout
- **Grid**: 5x5 bingo board with pixel gaps
- **Spacing**: Consistent pixel-based margins and padding
- **Background**: Geometric grid pattern with neon accents
- **Modals**: Full-screen overlays with thick borders

#### Accessibility
- Maintain high contrast ratios despite neon palette
- Preserve ARIA labels and semantic HTML
- Ensure touch targets remain usable on mobile
- Keep text readable despite pixel font limitations

When making design changes, always maintain the arcade aesthetic while ensuring functionality and accessibility.
