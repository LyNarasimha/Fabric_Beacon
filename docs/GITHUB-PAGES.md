# GitHub Pages (one-time)

If `https://glofoxinc.github.io/Fabric_Beacon/` returns **404**, enable hosting once:

**https://github.com/glofoxinc/Fabric_Beacon/settings/pages**

### Option A — fastest (branch deploy)

1. **Build and deployment** → **Source** → **Deploy from a branch**
2. Branch **`gh-pages`** · folder **`/ (root)`** → **Save**
3. Wait 1–2 minutes, then open **https://glofoxinc.github.io/Fabric_Beacon/DOCUMENTATION.html**

The `gh-pages` branch is updated on every release push from `main`.

### Option B — GitHub Actions (same as Semantic Scout)

1. **Settings → Actions → General** → allow workflows on this repo (forks may default to off).
2. On **Pages**, set **Source** to **GitHub Actions**.
3. Run workflow **Deploy GitHub Pages** or push to `main`.

Canonical team link: **https://glofoxinc.github.io/Fabric_Beacon/DOCUMENTATION.html**
