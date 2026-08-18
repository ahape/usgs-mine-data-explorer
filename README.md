# ⛏️ Tonopah-Region Mine Explorer

An interactive notebook for exploring every USGS-recorded mine, adit, shaft,
and prospect around Tonopah, NV (Nye County + all adjacent counties).
Data downloads automatically from USGS on first run (~40 MB). No setup needed.

## 🚀 For Dad: one click, nothing to install

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPO/blob/main/tonopah_mines.ipynb)

1. Click the badge above (works on any computer with a browser + Google account)
2. **Runtime ▸ Run all**, wait ~1 minute
3. Scroll to the **🎛️ Playground** sections, change the settings, re-run those cells

**You cannot break anything.** Colab gives you a private throwaway copy —
the original stays safe in this repo. If it gets weird, reload and Run all again.
To keep your own tinkered version: **File ▸ Save a copy in Drive**.

## 🧑‍💻 Power-user options

**GitHub Codespaces** (full VS Code in browser, ~60 free hrs/month):
green **Code** button → **Codespaces** → **Create codespace**. Open the
notebook, select the Python kernel, run. Your codespace is a sandbox —
nothing lands in the repo unless you commit and push.

**Locally:**
```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO && cd YOUR_REPO
pip install -r requirements.txt jupyter && jupyter lab tonopah_mines.ipynb
```

## Publishing this repo (one-time, for you)

1. Create a repo on github.com (public = free Colab access)
2. Upload these files (drag-and-drop in the web UI works fine)
3. Edit this README: replace `YOUR_USERNAME/YOUR_REPO` in the badge URL
4. Send Dad the README link — the badge does the rest

## Data sources (public domain)
- **MRDS** — worldwide mineral sites: commodities, status, geology · mrdata.usgs.gov/mrds
- **USMIN** — mine features from historical topo maps · mrdata.usgs.gov/usmin

⚠️ Historical locations. Many are on private claims or hazardous. Never enter abandoned mines.
