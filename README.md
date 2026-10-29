# fold

Two finished, self-contained pages for foldable phones:

- [`index.html`](index.html) — **Over the Fold**, a pong game played across the hinge. One screen is yours, the other is the CPU’s.
- [`hinge.html`](hinge.html) — a live fold-posture diagnostic. It reports posture, viewport segments, and which fold APIs the current browser exposes. The game already links here.

Both pages use the Device Posture and Viewport Segments web APIs. In Safari 27.1 on iPhone Duo those APIs must be enabled under **Settings > Apps > Safari > Advanced > Feature Flags** (Device Posture API and Viewport Segments API). They also need a secure context (HTTPS).

Serve them with GitHub Pages from the root of the `main` branch. The empty `.nojekyll` file tells Pages to publish these files as-is.
