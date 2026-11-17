# Orbit-Runner
A tiny, self-contained cosmic arcade game. Steer your ship, collect glowing stardust, dodge asteroids, and try to beat your personal best.

**Play:** open [`index.html`](index.html) in any modern browser. No build tools or dependencies are required.

## Controls

- **← / →** or **A / D** to steer
- **Space** to pause
- **Touch or drag** on the playfield on mobile

Your high score is saved in your browser with `localStorage`. The game does not send score or player data anywhere.

## Customize

Everything lives in `index.html`: layout, styling, artwork, and game logic. Tweak the colors in the `:root` variables or adjust asteroid speed in `spawnObject()`.

## License

MIT. See [LICENSE](LICENSE).
