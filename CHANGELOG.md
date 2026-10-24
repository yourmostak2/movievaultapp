# Movie Vault: Release History

Movie Vault is a free Android app for tracking the movies and web series you want to watch, are watching and have watched. This page lists everything that changed, version by version.

---

## v1.5.7
**Readable update notes and chip fix**

### Improved
- **Release notes now look clean inside the app.** On the Check for updates page, headings, bullet lists, bold text and links are shown properly instead of raw symbols. Long notes are no longer cut short.

### Fixed
- **Selected category chips stay white in dark mode.** Tapping a category such as In Theaters or New on OTT no longer turns it black.
- Long links no longer push the Download button outside its card.

---

## v1.5.6
**Small polish update**
- Fixed a visible line in the background on short pages such as Check for updates. The glass background now fills the whole screen.
- Also used to test that in-app updates show up correctly.

---

## v1.5: Liquid Glass redesign
**v1.5.0 to v1.5.5**

### New
- **Liquid Glass design.** Frosted, see-through glass on cards, lists, buttons, the top bar and the bottom navigation, with soft light edges and colourful lights moving behind it. Works in dark and light mode.
- **Glass effects setting.** Settings now has *Full glass* and *Lite*. Pick Lite if your phone feels slow.
- **Floating glass top bar and bottom navigation.** The active tab is a bright gradient pill that bounces when you switch.
- **Alive everywhere.** Shimmering titles, posters that float in one by one with a gentle light sweep, pulsing "In Theaters" tags and spring animations on every tap.
- **Redesigned movie page.** Year, runtime, age rating and genres are glass tags. The IMDb rating sits in a golden badge with a twinkling star.
- **Pill action buttons.** Add to watch, Watched and Love it are glass pills that glow in their own colour when selected, and the heart beats when you love a title.
- **Where to watch button.** The streaming list now opens and closes from a single button, so the page stays clean.
- **Poster background.** Each movie page is softly lit by its own poster, blurred behind the content.
- **New login and register page** in the same glass style as the rest of the app, with a larger logo, round fields and a glowing button.
- **True black dark mode (AMOLED).** Dark mode now uses pure black, so the glass and colours stand out more and your battery thanks you on OLED screens.

### Improved
- The top bar and tabs on the home page were rebuilt so nothing gets cut off.
- The bottom navigation is clearer: readable labels and a vivid active tab.
- Smoother page transitions and press animations throughout.

---

## v1.4.3
**Update checker fix**
- Fixed "Could not check for updates" on some phone networks. The app now falls back to a second route automatically.

---

## v1.4.2
**Small update**
- Version bump used to test the in-app update flow end to end.

---

## v1.4: The public release
**v1.4.0 and v1.4.1**

### New
- **First public release.** Download the APK from the Releases page or from the Movie Vault website.
- **Check for updates** now reads releases published here, so new versions show up inside the app with release notes and a Download button.
- **Home page and Privacy Policy** are live on the website.

### Improved
- **Movie data is served through a private proxy server.** The app no longer contains any API key, so it is safe to share with everyone.
- **Permanent release signing key.** Every future update installs directly over your current app.

### Good to know
- If you tested an earlier build, uninstall it once before installing v1.4. Your lists come back after you sign in (or restore from your Google Drive or word backup).

---

## v1.3: Google Drive backup, the way other apps do it
**v1.3.0, v1.3.1 and v1.3.2**

### New
- **Sign in with Google** opens the normal Google sign-in page in your browser and brings you back to the app.
- **Backup to Google Drive.** Your lists are stored in a hidden app folder in your Drive. Only Movie Vault can see that file, and it never touches your other files.
- **Automatic backups.** When signed in, the app backs up by itself every few hours.
- **Restore from backup** brings your lists back on a new phone with one tap.
- **Sign out of Google** from Settings whenever you want.

### Improved
- Clear messages when something goes wrong, including the exact reason from Google.
- The app now checks that you allowed the Google Drive permission and tells you if you did not.

---

## v1.2: New look
**v1.2.0 and v1.2.1**

### New
- **Completely redesigned interface.** A soft light theme with blue tones and a deep navy dark theme with warm cream highlights.
- **Wide, bold titles** and cleaner type throughout the app.
- **Floating bottom navigation.** The active tab expands to show its name.
- **New Settings page** with a profile header, grouped cards and icon tiles for Preferences, Backup and About.
- **Appearance buttons.** Pick Light, Dark or System with a single tap.
- **New Profile page** with a large avatar, your account information, your library shortcuts and a Delete account option.
- **Backup with words.** Copy your lists as a list of simple words, keep it in Notes or Telegram, and paste it back to restore. No file needed.

### Changed
- Cards, buttons and chips use smooth solid surfaces instead of glass blur.
- Smoother taps and transitions across the app.

---

## v1.1: Accounts, updates and a new identity
**v1.1.0, v1.1.1 and v1.1.2**

### New
- **Movie Vault logo** and name across the whole app.
- **Accounts.** Sign in or register, and your lists are saved to your account automatically. Log in on another phone and everything is there.
- **Delete my account** erases your account and your saved lists.
- **In Theaters** and **New on OTT** categories, with the newest releases placed first on the home page.
- **About page** with the developer profile and credits.
- **Check for updates** page.
- **Backup as text** so you can save your lists even without Google.

### Improved
- More breathing room: spacing between cards, icons and menus.
- Better update behavior: new builds install directly over the old app.
- Credits for data sources moved to the About page.

---

## v1.0: The first version
### Lists
- **Watchlist, Watched and Favorites** for movies and web series.
- **Season and episode tracking.** See how many seasons and episodes you have watched.

### Discover
- **Home page** with today's charts, new releases and a Top 10.
- **Details page** with poster, rating, director, cast, genres and where to watch.
- **Cast pages** to browse a person's other work.
- **Search** across the built-in catalog and the whole TMDB database.
- **Titles from Hollywood, Bollywood, Tollywood and Dhallywood.**
- **52 built-in titles** to start with, and new releases are added automatically.

### Everyday use
- **Login and register** with Remember me.
- **9 languages:** English, Bengali, Hindi, Tamil, Telugu, Urdu, Arabic, Spanish and French.
- **Light and dark themes.**
- **Android Back button** works the way you expect.

---

Movie data and images are provided by TMDB. This product uses the TMDB API but is not endorsed or certified by TMDB.
