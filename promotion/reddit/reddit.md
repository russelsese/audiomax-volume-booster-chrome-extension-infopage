# Reddit Post — r/ChromeExtensions

---

**Title:**
I built a free volume booster for Chrome with a real EQ, dB meter, and per-site settings — no ads, no sign-in, no data collection

---

**Body:**

Hey everyone! I built AudioMax, a free Chrome extension that goes well beyond a basic volume slider. Happy to share it here and hear your feedback.

**The problem it solves:** Chrome's volume maxes out at 100%, and most boosters just crank the gain with no regard for audio quality — you get clipping and distortion fast.

**What AudioMax does differently:**

- **Up to 600% volume boost** using the Web Audio API, with a built-in DynamicsCompressor to prevent clipping and distortion at high levels
- **3-band parametric EQ** — Bass (250 Hz), Mid (1 kHz), Treble (4 kHz) with ±12 dB per band, plus 6 instant preset chips (Bass Boost, Vocal Clarity, Loudness, Podcast, Music, Flat)
- **Real-time dB meter** — color-coded bar with numeric readout, updated 10x per second via AnalyserNode
- **Named presets** — save any volume + EQ combo with a custom name, load it in one click
- **Per-site settings** — AudioMax remembers your volume and EQ per domain and applies them automatically when you return
- **Settings sync** across all your Chrome devices via chrome.storage.sync
- **Persistent side panel** so controls stay accessible while you browse, plus a lightweight toolbar popup for quick adjustments

**Works on:** YouTube, Netflix, Spotify, Twitch, Amazon Prime Video, Disney+, Zoom, Google Meet, Apple Music, SoundCloud — basically any site that plays audio.

**Privacy:** Everything runs entirely in your browser via the Web Audio API. No data ever leaves your device, no analytics, no tracking, no account required.

It's free with no premium tier or ads. I built it because I wanted something that actually sounded good at high volumes and let me tune audio differently per site (I keep my Netflix at 200% and my Spotify flat, for example).

Would love any feedback — feature requests, bugs, whatever!

Chrome Web Store: https://chromewebstore.google.com/detail/audiomax-volume-booster/jcefkkcbcmphkdmnacbmkaeghjkacopg

Info page: https://russelsese.github.io/audiomax-volume-booster-chrome-extension-infopage/index.html

---

**Suggested subreddits to post in:**
- r/ChromeExtensions
- r/productivity
- r/software
- r/webdev (as a "I shipped something" post)
- r/YoutubeEnhancement

**Notes for posting:**
- Disclose upfront that you're the developer (Reddit rules + community trust)
- Post during peak hours: Tuesday–Thursday, 9am–12pm EST
- Reply to every comment quickly in the first hour — it signals to the algorithm and builds goodwill
