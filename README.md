<h1 align="center">🎬 Movie Vault</h1>

<p align="center"><b>Discover movies and web series, track what you've watched, and find where to stream them legally.</b></p>

<p align="center">No ads. No tracking. Works on any Android phone.</p>

<p align="center">
  <a href="https://github.com/yourmostak2/movievaultapp/releases"><img src="https://img.shields.io/github/downloads/yourmostak2/movievaultapp/total?style=for-the-badge&logo=github&label=DOWNLOADS&color=4CAF50" alt="Downloads"></a>
  <a href="https://github.com/yourmostak2/movievaultapp/releases/latest"><img src="https://img.shields.io/github/v/release/yourmostak2/movievaultapp?style=for-the-badge&logo=github&label=LATEST&color=2196F3" alt="Latest release"></a>
  <a href="https://t.me/movievaultupdate"><img src="https://img.shields.io/badge/Telegram-Updates-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Android-8.0%2B-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="Android 8+">
  <img src="https://img.shields.io/badge/Capacitor-6-119EFF?style=for-the-badge&logo=capacitor&logoColor=white" alt="Capacitor">
  <img src="https://img.shields.io/badge/TMDB-API-01B4E4?style=for-the-badge" alt="TMDB">
  <img src="https://img.shields.io/badge/Firebase-Auth%20%2B%20Firestore-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase">
  <img src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge" alt="License">
</p>

<p align="center">
  <a href="#-download">Download</a> •
  <a href="#-features">Features</a> •
  <a href="#-screenshots">Screenshots</a> •
  <a href="#-how-it-works">How it works</a> •
  <a href="#-build-from-source">Build</a> •
  <a href="#-privacy">Privacy</a> •
  <a href="#-credits">Credits</a>
</p>

---

## ✨ Features

| | |
|---|---|
| 🔥 **Discover** | Trending, popular, top rated, In Theaters and Coming Soon |
| 🇮🇳 **Indian-first Home** | Bollywood, Tollywood, Kollywood, Mollywood, Sandalwood, Dhallywood and more. World titles too |
| 📺 **Where to Watch** | Streaming, free, rent and buy options in your country, with the provider name (JustWatch data) |
| ✅ **Your lists** | Watchlist, Watched and Favourite, with Movies and Series sections |
| 📅 **Calendar** | Add upcoming releases to your phone calendar |
| 🎞️ **Details** | Synopsis, cast, director, trailer, ratings, runtime |
| 🔎 **Search** | Movies, series and actors |
| ☁️ **Backup** | Sign in and back up your lists to your account |
| 🔔 **Alerts** | Optional notifications: cinema releases, OTT releases, app updates |
| 🌗 **Themes** | Light and dark |

---

## 📸 Screenshots

<p align="center">
  <img src="screenshots/home.png" width="180" alt="Home">
  <img src="screenshots/details.png" width="180" alt="Details">
  <img src="screenshots/watched.png" width="180" alt="Watched">
  <img src="screenshots/settings.png" width="180" alt="Settings">
</p>

---

## 📥 Download

1. Open the **[latest release](https://github.com/yourmostak2/movievaultapp/releases/latest)**.
2. Download `MovieVault.apk`.
3. Open it on your phone. If asked, allow installs from your browser or file manager.
4. Open Movie Vault. Sign in if you want backup.

**Requirements:** Android 8.0 or newer.

---

## ⚙️ How it works

- The app is one web page, wrapped as an Android app with Capacitor.
- Movie data comes from a Cloudflare Worker, which calls TMDB and OMDb. API keys stay on the server, never in the app.
- Accounts and backup use Firebase.

---

## 🔄 Updates

- When a new version is out, the app shows an update popup.
- Tap **Open in browser** to download the new APK from the releases page.
- Install it over the old version. Your data stays.

Follow [@movievaultupdate](https://t.me/movievaultupdate) for release news.

---

## 🛠️ Build from source

1. Clone this repository.
2. Add your own TMDB and OMDb keys to the Cloudflare Worker secrets.
3. Push to `main`. GitHub Actions builds the APK.

See [CHANGELOG.md](CHANGELOG.md) for version history.

---

## 🔐 Privacy

- Your lists stay on your phone. Signed-in users back them up to their account.
- No ads. No selling of data.
- Anonymous usage counts only.
- Full details: [PRIVACY.md](PRIVACY.md).

---

## ⚖️ Content & copyright

Movie Vault does **not** host, store or stream any movies or series. Movie data, posters and streaming availability come from third-party services. Streaming links go only to official services or to content the owner has made available.

To report a problem with any content, open an [issue](https://github.com/yourmostak2/movievaultapp/issues). It will be reviewed and removed promptly if it infringes.

---

## 🙏 Credits

- Movie and TV data: [The Movie Database (TMDB)](https://www.themoviedb.org/). This product uses the TMDB API but is not endorsed or certified by TMDB.
- Streaming availability: [JustWatch](https://www.justwatch.com/), via TMDB.
- Ratings: [OMDb API](https://www.omdbapi.com/).
- Built with [Capacitor](https://capacitorjs.com/).

---

## 📜 License

Released under the [MIT License](LICENSE).
