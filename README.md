<div align="center">
  <img src="readme-res/ic_launcher_round.png" width="40%" />
  
# Panchajanya

  ### Music player for Android
  
  <p>
    Panchajanya is a minimalist and elegant music player for Android, designed with a focus on aesthetics and a premium user experience. 
    It features a modern Jetpack Compose UI, dynamic color support, and a unique high-quality dark defocus widget system.
  </p>
</div>

## ✨ Features

- **Modern UI**: Built with Jetpack Compose for a fluid, responsive interface.
- **Premium Widget**: Home screen widget featuring a professional "dark defocus" effect powered by RenderEffect (Android 12+) and high-quality software blur fallback.
- **Live Lyrics**: Integrated lyrics viewer with synchronized scrolling and smooth animations.
- **Dynamic Themes**: Responsive to system color schemes and dark mode.
- **Queue Control**: Robust playback management with shuffle, repeat, and queue persistence.
- **Playlist**: The ability to create your own playlists with the music you like, separate from the rest.
- **Automix and Crossfade**: 12-second transition effect when changing songs, for a smooth transition.
- **Timer**: Set a timer to turn off playback; available times: off, 15m, 30m, 60m.
- **Equalizer**: It includes a 10-band Equalizer with several preset modes, plus advanced audio processing tools:
  - **Bass Boost**: Extra low-end enhancement beyond the EQ bands. Works as an invisible offset — the sliders stay put but the hardware gets a boost.
  - **Spatial Audio**: Virtual widening of the soundstage using Android's `Virtualizer` effect. Smooth ramp on toggle for a natural transition.
  - **Loudness Enhancer**: Boosts the perceived loudness of your audio without clipping. Uses Android's `LoudnessEnhancer` to make quiet passages more audible while preserving dynamic integrity. Adjustable gain from 0 to 30 dB.
  - **Balance**: Adjusts the stereo panorama between left and right channels. The on-screen indicator shows L (full left), C (center), or R (full right). A reset button snaps back to center instantly. Applied in real time during playback and preserved across track transitions.
  - **Reverb**: Simulates different acoustic spaces around your audio — from a small Room to a large Concert Hall. Built on `EnvironmentalReverb` (API 31+) with `PresetReverb` fallback on older devices. Six environments available: Room, Hall, Plate, Stage, Arena, and Cathedral. Works independently of the Equalizer.
  - **Pitch**: Changes the playback speed and pitch from 0.5x (slow, deep) to 2.0x (fast, high). Speed and pitch move together via Android's `PlaybackParams`. Useful for voice study, instrumental practice, or just having fun with songs.
  - **Dynamics Processor**: Compresses the dynamic range — the gap between the quietest and loudest parts. Five presets:
    - _Light_ (1.5:1 ratio, gentle smoothing)
    - _Medium_ (3:1 ratio, general purpose)
    - _Strong_ (5:1 ratio, heavy compression with limiting)
    - _Night_ (8:1 ratio, aggressive compression + limiter — ideal for late-night listening without disturbing others)
      Uses Android's `DynamicsProcessing` with multi-band compression (MBC) and a hard limiter. Independent of the EQ.
- **Visualizer**: Bar display that moves to the rhythm of the music.
- **Sample button theme**: A simple button that allows you to change the application's light or dark mode (includes automatic mode, taking the system mode).
- **HI-FI audio**: The application supports audio in HI-FI formats.
- **Audio formats**: Built on Android's `MediaPlayer`, supporting MP3, AAC (`.aac`/`.m4a`), FLAC, Vorbis (`.ogg`), Opus, WAV, ALAC, AMR, MIDI, and MP2.
- **Language**: Available in Spanish and English.
- **Custom Title**: Customize the application title from the settings.

### 👥 The Community
- [Code of Conduct](CODE_OF_CONDUCT.md)
- [License](LICENSE)
- [Security Policy](SECURITY.md)
- [Technical Reference](TECHNICAL_REFERENCE.md)
