# Fishbowl Splash Screen — Info

## Original GIF Author

**James Neilson** — Freelance 2D animator / motion designer, Melbourne, Australia.

- Website: https://james-neilson.com/
- Dribbble (Goldfish Bowl): https://dribbble.com/shots/2800762-Goldfish-Bowl
- Dribbble profile: https://dribbble.com/jneilson
- Instagram: https://www.instagram.com/jamesxneilson/

## KDE Store Versions

- **Original "Fishy" (Plasma 5):** by Kartik Sindura, Aug 2022 — https://store.kde.org/p/1871278
- **"Fishybowl For Plasma6":** ported by djandk0k, Aug 2024 — https://store.kde.org/p/2192566

## Performance Fix (March 2026)

QML changes to `Splash.qml` to fix GIF animation lag at login:

- `smooth: false` — disables bilinear filtering (not needed at native size)
- `cache: true` — keeps decoded frames in memory
- `asynchronous: true` — decodes frames off the main UI thread
- `layer.enabled: true` — rasterizes to GPU texture for compositing

## License

QML code: GPLv2+
GIF: Created by James Neilson (contacted for permission)
