# Loci — Game Studio

Static authoring page for [Loci](https://github.com/mossaab0/Loci) quiz games: sign in with
your Loci account, write questions for AR markers placed from the app, manage a reusable
question bank, and run the game lifecycle.

Live: https://mossaab0.github.io/loci-web/

One file (`index.html`, supabase-js from a CDN) + `config.js` (Supabase project URL and the
**publishable** anon key — safe to serve; Row-Level Security is the authorization boundary).
The source of truth lives in the main app repo under `web/`; copy `index.html` here to deploy.
