# Hi, I'm Seph 👋

I build practical software that people use every day: a cross-platform app with its own installer and automatic updates, a website with interactive data stories, and tools with real users. I care about the parts users don't see too. That means security, testing, releases and code that other people can work on.

💼 **5 years of professional experience** as a programmer-analyst and IT analyst (2020–2025): C#/.NET applications, SQL databases and business process automation.

**What I work with:** Dart & Flutter (Windows, Android) · JavaScript, HTML & CSS · Lua · Git & GitHub (pull requests, code review, releases) · Windows APIs · HTTPS & networking · automated testing · AI-assisted development (Claude Code)

## Featured project

### [PocketDrive](https://github.com/SepiHub/PocketDrive) · Flutter app for Windows + Android · [latest release](https://github.com/SepiHub/PocketDrive/releases/latest)
Turns a folder on your Windows PC into extra storage for your Android phone over home Wi-Fi. You can browse, view photos, stream videos, upload, move and delete, with no cloud account and nothing leaving your home network.

- **Secure by design:** all traffic is encrypted with HTTPS. The phone pairs by scanning a QR code that carries the PC's certificate fingerprint, so it trusts only that PC. Each paired device gets its own key (stored only as a hash), checked on every request, and the server blocks any attempt to reach files outside the shared folder.
- **Smooth media:** streams video with seeking, resume where you left off, subtitles (including tracks built into the video, extracted with FFmpeg) and gallery-style gestures. Photo thumbnails come from Windows itself.
- **Works without setup:** the phone finds the PC on the network by itself (mDNS). On the PC it runs quietly in the system tray and can start with Windows.
- **Shipped like a real product:** a Windows installer, a signed Android app, and one-tap updates in both apps that download from GitHub Releases and check each file's SHA-256 checksum. A one-command script builds and publishes each release.
- **Tested:** 120 automated tests, including security checks for blocked file paths and full HTTPS round trips.
- Three-part codebase: a Windows server app, an Android client app, and a shared package for the protocol both apps speak.

## More projects

### [GuildWrapped](https://github.com/SepiHub/GuildWrapped) · website · [live site](https://sepihub.github.io/GuildWrapped/)
A "Spotify Wrapped"-style yearly recap for an online gaming community. Each member gets a card that plays their year as a slide-by-slide story.
- Turns raw activity data into story slides and skips any slide that has no data
- Members submit their data by pasting a code. The site validates it with a CRC32 checksum and decodes it, so nobody needs a GitHub account.
- Keeps a version history per member, with a "since last time" comparison
- Plain HTML, CSS and JavaScript with no framework, hosted on GitHub Pages

### [GatherMaxing](https://github.com/SepiHub/GatherMaxing) · published plugin
A real-time stats overlay for World of Warcraft, published on CurseForge. It shows what each action is worth as it happens, and keeps session history with gold per hour.
- Live prices read from another plugin's public API, with a fallback when it's missing
- Sortable history tables, plus a per-session breakdown that saves each price at the time it was earned
- Migrates saved user data safely from one version to the next

### [GFoA Guild Sync](https://github.com/Harl3yVT/gfoa-guildsync) · open-source contributor
I contribute to another developer's project through reviewed pull requests. **7 pull requests merged**, including:
- A new **leaderboard tab** comparing members on several stats ([#15](https://github.com/Harl3yVT/gfoa-guildsync/pull/15), [#19](https://github.com/Harl3yVT/gfoa-guildsync/pull/19), [#20](https://github.com/Harl3yVT/gfoa-guildsync/pull/20))
- A **kill board** with filtering rules ([#13](https://github.com/Harl3yVT/gfoa-guildsync/pull/13)), and a bug fix for a counter stuck at zero ([#22](https://github.com/Harl3yVT/gfoa-guildsync/pull/22))
- Smaller UI improvements ([#12](https://github.com/Harl3yVT/gfoa-guildsync/pull/12), [#14](https://github.com/Harl3yVT/gfoa-guildsync/pull/14))

→ [All my pull requests](https://github.com/Harl3yVT/gfoa-guildsync/pulls?q=author%3ASepiHub)

<!-- Optional: add a way to contact you, e.g. email or LinkedIn -->
