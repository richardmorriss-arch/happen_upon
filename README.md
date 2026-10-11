# HappenUpon // Serendipity Deck

A standalone, zero-dependency dispatch terminal for rediscovering the open web.

HappenUpon routes you away from algorithmic feeds and into independent personal sites, engineering archives, vintage web snapshots, encyclopedia rabbit holes, and cosmic records.

---

### Channels Online

* **Pure Chaos:** Dynamic multi-frequency blend configured via onboard toggles.
* **The Indie Web:** Handcrafted personal homepages via Wiby.
* **Deep Tech:** Long-form engineering discussions, utilities, and post-mortems via Hacker News archives.
* **Wormholes:** Deep rabbit holes powered by the Wikipedia REST API.
* **Time Machine:** Preserved 1996–2004 website snapshots via the Wayback Machine.
* **Cosmic Vault:** NASA Astronomy Picture of the Day archives (1995–present).

---

### Architecture & Privacy

* **Zero Dependencies:** Single-file vanilla HTML, CSS, and modern JavaScript. No bundlers, frameworks, build steps, or `node_modules`.
* **Zero Tracking / BYOC:** No third-party analytics or server backends.
* **Local Persistence:** Dispatch logs, starred vault bookmarks, and chaos mixing profiles live entirely inside your browser's `localStorage`. Export your starred vault anytime as a standalone JSON file.

---

### Quick Start

#### Option 1: Run Locally (Instant)
1. Clone or download this repository.
2. Double-click `index.html` to run it in any modern browser.

#### Option 2: Host via GitHub Pages (Free 60-Second Deploy)
1. Fork this repository to your GitHub account.
2. Navigate to **Settings** > **Pages**.
3. Under **Build and deployment**, set **Source** to `Deploy from a branch`.
4. Select `main` branch and `/ (root)` folder, then click **Save**.
5. Your instance will go live at `https://<your-username>.github.io/<repo-name>/`.

#### Option 3: Deploy to Vercel / Cloudflare Pages
Drop the repository into a new Vercel or Cloudflare Pages project. No build commands or output directory settings required—just hit deploy.

---

### Modifying the Deck

Because the entire application lives inside `index.html`, customization requires zero tooling:
* Add custom vintage domains inside `bounceRetro()`.
* Tweak Hacker News API queries inside `bounceTech()`.
* Restyle the industrial terminal aesthetics by modifying the `:root` CSS variables at the top of the file.

---

### License

Distributed under the Apache 2.0 License. See `LICENSE` for more information.
