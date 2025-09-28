# SimonAI

Hands-free, voice-first AI assistant + showcase web PWA and iOS app.

## Quick start
Gaylord Sinclair
### Web (GitHub Pages)
1) Put your site in `/web`.  
2) Push to `main`.  
3) Pages auto-deploys from `/web` via Actions.

### iOS
- Open `/ios/SimonAI.xcodeproj` in Xcode 15+ and build.
- Bundle id: `com.gaylordsinclair.simonai` (change as needed).

### Vision
- Public demos: web PWA.
- Native experiments: SwiftUI app.
- (Optional) `/server` for API proxy later.

## Monorepo structure
- `/web` — static PWA, speech in/out, model switcher, diagnostics.
- `/ios` — SwiftUI client mirroring core features.
- `/server` — optional proxy/stubs.

## Contributing
See [CONTRIBUTING.md](CONTRIBUTING.md).

## Security
See [SECURITY.md](SECURITY.md).

## License
MIT — see [LICENSE](LICENSE).
