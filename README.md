# DreamApp – Client-Only Prototype

Zero-key, zero-backend copy/paste runner for early UX testing.

**How it works**
1. Paste a dream.
2. Pick a framework (Jung, Freud, Gestalt, Shamanic, Cognitive) + depth (Plain / Standard / Advanced).
3. Click **Copy Prompt** and paste it into an Incognito ChatGPT window.
4. Copy the model’s output back into the app’s **Paste Output** box (optional) and/or save it elsewhere.

**Notes**
- No analytics, no storage, no cookies—everything lives in your browser session.
- Freud “Plain Language” auto-sanitizes explicit wording (age-friendly default).
- Later we can add age gates for Standard/Advanced, and wire an API backend if needed.

**Deploy**
- Enable GitHub Pages (Settings → Pages → Build and deployment = “Deploy from a branch”, branch `main`, folder `/root`).
- Your app will be served at `https://<your-username>.github.io/<repo>/`.
