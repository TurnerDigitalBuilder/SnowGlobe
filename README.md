# Snow Globe Quest

A mobile-friendly snow globe mini-game. Open `index.html` in a modern browser to play—no build step required.

## Controls and tools
- **Tilt**: Request device-sensor access to steer by tilting your phone.
- **Keyboard**: Arrow keys or WASD now steer the snowball when tilt is unavailable.
- **Shake**: Button or quick device shake to trigger a blizzard bonus.
- **Pause / Restart**: Manage the game state without leaving the page.
- **Sound toggle**: Turn audio feedback on or off.
- **Festive start jingle**: A short sleigh-bell inspired chime celebrates each new run.

## Scene and template
- The globe now holds a winter town vignette: ringed evergreens, cozy houses, glowing lampposts, and a central Christmas tree wrapped in ornaments and gifts.
- All visuals render directly in `index.html`—no external assets or build tools are required.

## Site flow
1. The overlay card introduces the game and asks to start or enable tilt.
2. Once running, the HUD shows score, timer, level, remaining stars, and bonus multiplier.
3. Stats pin to the upper-left corner while the control panel hugs the lower-right, leaving the globe clear in the center.
4. Keyboard input replaces the on-screen joystick, keeping the screen clear while remaining desktop-friendly.
5. Game-over or pause states bring back the overlay with contextual messaging.

## Audio notes
- The first interaction resumes the Web Audio context so sounds play reliably on mobile browsers.
- The start button now triggers a brief Christmas-flavored jingle to confirm audio is live.

## Mobile readiness
The layout responds to narrow screens by stacking panels, widening touch targets (44px+), and centering overlay actions. Control buttons compact into an auto-fitting grid so they stay on-screen, and safe-area insets are respected for notched devices.
