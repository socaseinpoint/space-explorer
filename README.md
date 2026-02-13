# Space Explorer 🚀

Minimalist space flight experience with Three.js.

## Current Version: v0.2.0

**Live Demo:** https://space-explorer-drab.vercel.app

### Features
- Forward movement through space
- 1000 stars flying past the camera
- Motion trails for speed effect
- Smooth 60fps animation

## Project Structure

```
space-explorer/
├── index.html          # Current production version
├── versions/           # Archived versions
│   ├── v0.1.0.html
│   └── v0.2.0.html
├── CHANGELOG.md        # Version history
├── PROJECT_RULES.md    # Development guidelines
└── README.md          # This file
```

## Development

See [PROJECT_RULES.md](PROJECT_RULES.md) for versioning and development guidelines.

See [CHANGELOG.md](CHANGELOG.md) for version history.

## Deployment

```bash
# Deploy to Vercel
vercel --prod --yes
```

## Tech Stack

- **Three.js** r160 - 3D rendering
- **Vercel** - Hosting
- Pure JavaScript (no build step)
