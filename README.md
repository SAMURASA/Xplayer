# XPlayer

<p align="center">
  <strong>Modern music player for Windows</strong><br>
  Local library, YouTube, Discord Rich Presence, Party / Listen Together, reactive visuals and Potato Mode.
</p>

<p align="center">
  <a href="https://github.com/SAMURASA/Xplayer/releases/latest"><strong>Download XPlayer</strong></a>
  ·
  <a href="https://github.com/SAMURASA/Xplayer/issues">Report an issue</a>
  ·
  <a href="README.ru.md">Русский</a>
</p>

---

## 🎧 What is XPlayer?

**XPlayer** is a Windows desktop music player built around a local library, with the features you usually need several separate apps for.

It brings together:

- local music and video;
- YouTube search and offline saving;
- Discord Rich Presence;
- **Party / Listen Together**;
- WebRTC P2P-first connections;
- audio-reactive visuals;
- bass-reactive glow;
- Slowed / Nightcore / Reverb;
- profiles and Profile Studio;
- Radio / HypeFM;
- a dedicated **Potato Mode** for low-end systems.

XPlayer is designed for everyday listening, while still giving you a social and visual desktop experience.

## ✨ Why XPlayer?

### Everything in one place

No need to keep one app for local music, another browser tab for YouTube and another utility for Discord presence.

### Music + friends

**Party** lets you create a listening room, sync playback and use a shared queue with friends.

### Visuals you can tune to your PC

Use performance profiles for heavier visual effects, or switch to **Potato Mode** when CPU/GPU usage matters more than visuals.

### Make it yours

Profile Studio brings together card styles, frames, effects, colors and achievement rewards so the player feels personal instead of generic.

---

## 🚀 Features

| Area | Features |
|---|---|
| 🎵 Library | Folder scanning, drag & drop, local audio/video, queue, playlists, favorites, shuffle and repeat |
| ▶ YouTube | Search, Load more, direct links, yt-dlp, offline saving and thumbnail artwork |
| 👥 Party | Up to 6 active listeners, shared queue, play/pause/seek sync, WebRTC P2P-first and TURN fallback |
| 💬 Discord | Rich Presence with title, artist, artwork, timeline, Party and Radio |
| 🎨 Visuals | Audio-reactive modes, bass-focused glow, performance and quality controls |
| 🥔 Potato Mode | Low-load mode that disables heavy visual/reactive and Party preloading features |
| 🎛 Effects | Slowed, Normal, Nightcore, Slowed + Reverb, speed, low-frequency controls and Reverb |
| 👤 Profiles | Profile Studio, card styles, frames, colors, effects, stats and achievement rewards |
| 📻 Radio | HypeFM / Radio with isolated UI and online controls |
| 🌍 UI | Russian / English, onboarding, tooltips, Hub scaling and UX improvements |

[Full feature list →](docs/FEATURES.md)

---

## ▶ YouTube

XPlayer can work with YouTube directly from the player interface.

Supported:

- built-in YouTube search;
- **Load more** for additional results;
- direct video links;
- real title / metadata lookup;
- local offline saving;
- original YouTube thumbnail artwork;
- artwork reuse for local playback and Discord Rich Presence.

Downloads are handled through **yt-dlp**.

> Only use media you are allowed to access or use. YouTube availability can vary by region, age restrictions, authentication and other platform limits.

---

## 👥 Party / Listen Together

Party is XPlayer's shared listening mode.

### Party includes

- up to **6 active slots**;
- shared queue;
- play / pause / seek synchronization;
- WebRTC **P2P-first** networking;
- TURN only as a fallback;
- Metered Realtime signalling;
- local file transfer / preloading paths;
- playback effect synchronization;
- Discord join / invite context.

### Setting up Party

1. Create a **Metered Realtime** project.
2. Create a publishable key `pk_live_...`.
3. Open **Settings → Advanced network settings** in XPlayer.
4. Paste the key and save.
5. Create or join a Party.

XPlayer does not require a secret server-side Metered key.

---

## 💬 Discord Rich Presence

With Discord Desktop running, XPlayer can show:

- track title;
- artist;
- artwork;
- playback timeline;
- normal playback state;
- Party state;
- Radio / HypeFM;
- join / invite context.

Offline tracks can reuse their saved thumbnail artwork in Discord.

---

## 🎨 Visuals

XPlayer includes a music-reactive visual system with:

- audio-reactive visuals;
- bass-focused glow around the cover;
- configurable visual modes and placement;
- performance profiles;
- quality controls;
- visual cache;
- configurable timeline color.

### 🥔 Potato Mode

**Potato Mode** is a dedicated low-load mode for weak PCs and gaming systems.

It limits or disables the heaviest visual, reactive and preloading components while keeping normal playback and core player features working.

---

## 🎛 Slowed / Nightcore / Reverb

The effects panel includes:

- Slowed;
- Normal;
- Nightcore;
- Slowed + Reverb;
- playback speed;
- low-frequency controls;
- Reverb time;
- wet/dry mix;
- live parameter updates.

---

## 👤 Profile Studio

Profile Studio combines customization and achievements.

Available features include:

- **Glass / Solid / Neon** card styles;
- profile frames;
- card and accent colors;
- avatar effects;
- banner effects;
- statistics;
- reactions;
- achievement levels;
- cosmetic rewards.

Locked cosmetic options remain unavailable until the required achievement is unlocked.

---

## 📻 Radio / HypeFM

Radio is a separate playback scenario, isolated from the normal online features.

While Radio is active, regular online controls and lyrics/text overlays are isolated so they do not cover or interfere with the radio interface.

---

## 🖱 Drag & Drop

Drag into XPlayer:

- one track;
- multiple tracks;
- or an entire folder.

You do not need to add every song manually.

---

## ⚙️ Interface

- dark desktop UI;
- XPlayer Hub scaling from **100% to 120%**;
- tooltips for important settings and actions;
- Russian and English UI;
- first-run onboarding;
- saved music-library folder;
- visible current-track highlighting;
- playlists, queue, favorites and statistics.

---

## 📻 Supported formats

XPlayer works with common local audio and video formats, including:

`MP3` · `M4A` · `AAC` · `OGG` · `Opus` · `WAV` · `FLAC` · `WebM` · `MP4`

Actual support for a specific file depends on the playback stack used by the application.

---

## 📦 Download

Open the [**Latest Release**](https://github.com/SAMURASA/Xplayer/releases/latest) and download the Windows installer.

After installation:

1. Launch XPlayer.
2. Select your music folder during first-run setup.
3. Configure Discord, YouTube, visuals and other features as needed.
4. For Party, configure Metered Realtime separately.

---

## 🐛 Issues and feedback

[Report a bug](https://github.com/SAMURASA/Xplayer/issues/new?template=bug_report.md)  
[Request a feature](https://github.com/SAMURASA/Xplayer/issues/new?template=feature_request.md)

---

## 🔐 Privacy and external services

XPlayer is primarily a local desktop application for your music library, settings and profile.

External integrations:

- **YouTube / yt-dlp** — online media and metadata;
- **Metered Realtime** — Party signalling;
- **WebRTC** — peer-to-peer connections;
- **Discord Desktop** — Rich Presence.

Do not publish API keys, cookies or other secrets in issues, README files or the repository.

---

## 📜 License

Distribution and licensing details for the current build are provided separately with the release documentation.
