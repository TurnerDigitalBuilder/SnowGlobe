# Snow Globe Quest

A mobile-friendly snow globe mini-game. Open `index.html` in a modern browser to play—no build step required.

## Controls and tools
- **Tilt**: Request device-sensor access to steer by tilting your phone.
- **Joystick**: On-screen joystick for touch and desktop dragging; always available.
- **Shake**: Button or quick device shake to trigger a blizzard bonus.
- **Pause / Restart**: Manage the game state without leaving the page.
- **Sound toggle**: Turn audio feedback on or off.

## Site flow
1. The overlay card introduces the game and asks to start or enable tilt.
2. Once running, the HUD shows score, timer, level, remaining stars, and bonus multiplier.
3. Controls sit alongside the stats on wide screens; on phones they float in opposite top corners to keep the globe visible.
4. The on-screen joystick stays anchored in the lower-left corner for easy thumb reach.
5. Game-over or pause states bring back the overlay with contextual messaging.

## Mobile readiness
The layout responds to narrow screens by stacking panels, widening touch targets (44px+), and centering overlay actions. Control buttons compact into an auto-fitting grid so they stay on-screen, and safe-area insets are respected for notched devices.
