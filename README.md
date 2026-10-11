# HappenUpon // Serendipity Deck

A standalone, zero-dependency dispatch console for exploring the web. Built entirely in vanilla HTML, CSS, and client-side JavaScript contained inside a single `index.html` file[cite: 2]. 

No build tools, no package managers, and no backend configuration required.

---

## Channels

* **Pure Chaos**: An unfiltered, configurable blend across all channels[cite: 2].
* **The Indie Web**: Handcrafted personal homepages dispatched via Wiby[cite: 2].
* **Deep Tech**: Engineering deep-dives, simulations, utilities, and post-mortems pulled from Hacker News[cite: 2].
* **Wormholes**: Random deep-encyclopedia rabbit holes via the Wikipedia API[cite: 2].
* **Time Machine**: Snapshots of classic early-web domains (1996–2004) via the Internet Archive Wayback Machine[cite: 2].
* **Cosmic Vault**: Astronomical captures pulled from NASA's Astronomy Picture of the Day (APOD) archive dating back to June 1995[cite: 2].

---

## Features

* **Zero Footprint**: Runs completely in the browser with zero external npm dependencies[cite: 1, 2].
* **Local Persistence**: Dispatch history, starred items (Vault), and channel mix settings persist exclusively in browser `localStorage`[cite: 2].
* **Data Portability**: Export your starred Vault links as a JSON file anytime[cite: 2].
* **Industrial UI**: Cyberdeck-inspired interface styled with pure CSS[cite: 2].

---

## Quick Start

### 1. Run Locally
1. Clone or download this repository.
2. Double-click `index.html` to open it directly in any modern browser[cite: 2].

### 2. Deploy to GitHub Pages (Free Hosting)
1. Fork or push this repository to your GitHub account.
2. Navigate to **Settings > Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Choose the `main` branch and `/ (root)` folder, then click **Save**.
5. Your live app will be accessible at `https://<your-username>.github.io/<repo-name>/`.

---

## Customization

Because everything is contained in `index.html`[cite: 2], customization requires only basic HTML/JS edits:
* **Vintage Domain List**: Add or swap out target retro domains inside the `vintageDomains` array in the `bounceRetro()` function[cite: 2].
* **Chaos Weights**: Adjust the default mix flags inside the `defaultMix` object[cite: 2].
* **Custom Endpoints**: Wire up your own RSS feeds, APIs, or static link dictionaries by dropping a new bounce function into the master dispatcher[cite: 2].

---

## License

This project is open-source and available under the [MIT License](LICENSE).
