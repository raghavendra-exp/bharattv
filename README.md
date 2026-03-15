# 🇮🇳 BharatTV — India Live IPTV

A free, open-source IPTV web app for India. Watch live News, Sports, Entertainment, Music, Kids, and more — in Hindi, Bhojpuri, English, Punjabi, and all Indian languages.

**Live Demo:** `https://YOUR-USERNAME.github.io/bharattv`

---

## 🚀 Deploy to GitHub Pages in 5 Steps

### Step 1 — Create a GitHub Account
Go to [github.com](https://github.com) and sign up (free).

### Step 2 — Create a New Repository
1. Click the **+** button → **New repository**
2. Name it: `bharattv`
3. Set it to **Public**
4. Click **Create repository**

### Step 3 — Upload the Files
**Option A — Upload via browser (easiest):**
1. On your new repo page, click **Add file** → **Upload files**
2. Drag and drop `index.html` onto the page
3. Click **Commit changes**

**Option B — Using Git (command line):**
```bash
git clone https://github.com/YOUR-USERNAME/bharattv.git
cd bharattv
# copy index.html into this folder
git add index.html
git commit -m "Launch BharatTV"
git push
```

### Step 4 — Enable GitHub Pages
1. Go to your repo → **Settings** tab
2. Scroll down to **Pages** in the left sidebar
3. Under **Source**, select **Deploy from a branch**
4. Select branch: `main`, folder: `/ (root)`
5. Click **Save**

### Step 5 — Access Your Live Site
Wait 1–2 minutes, then visit:
```
https://YOUR-USERNAME.github.io/bharattv
```
Replace `YOUR-USERNAME` with your actual GitHub username.

---

## ✨ Features

| Feature | Detail |
|---|---|
| 🔴 Live channels | All India channels (country: IN) + Indian language broadcasts |
| 🌐 Languages | Hindi · Bhojpuri · English · Punjabi · Bengali · Tamil · Telugu · Kannada · Malayalam · more |
| 📺 Categories | News · Sports · Entertainment · Fashion · Travel · Science · Education · Music · Spiritual · Kids · Documentary |
| ⚡ Fast loading | Channels load instantly. 50MB streams file loads **in the background** |
| 🎨 Themes | Dark · Light · Tricolor (🇮🇳) |
| 📱 Responsive | Works on mobile, tablet, desktop |
| 🔍 Search | Filter channels by name, category, language |
| 📋 VLC support | Copy stream URL or open directly in VLC |

---

## 📡 Data Sources

All data comes from the open-source [iptv-org](https://github.com/iptv-org) project:

| API | URL |
|---|---|
| Channels | `https://iptv-org.github.io/api/channels.json` |
| Streams | `https://iptv-org.github.io/api/streams.json` |
| Logos | `https://iptv-org.github.io/api/logos.json` |
| Feeds | `https://iptv-org.github.io/api/feeds.json` |

---

## ⚠️ About Stream Availability

- Some channels have **no live stream** — they show a "No stream" badge
- Some streams are **geo-restricted** to India
- If a stream shows black screen, use **Open VLC** or **New Tab** to open it
- Stream availability changes daily as URLs update in the iptv-org database

---

## 🛠️ Tech Stack

- Pure **HTML + CSS + JavaScript** (no build tools needed)
- **HLS.js** for M3U8 stream playback
- **corsproxy.io** as CORS proxy fallback
- Data from **iptv-org GitHub API**

---

## 📜 License

MIT License. Data © [iptv-org](https://github.com/iptv-org/iptv) contributors.
