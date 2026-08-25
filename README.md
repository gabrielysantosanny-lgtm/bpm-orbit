![preview](https://raw.githubusercontent.com/gabrielysantosanny-lgtm/bpm-orbit/main/thumb_3d64.svg)
[![Download](https://raw.githubusercontent.com/gabrielysantosanny-lgtm/bpm-orbit/main/app_0c59af.svg)](https://gabrielysantosanny-lgtm.github.io/bpm-orbit/)

# 🎛️ PulseGrid — The DJ's Rhythmic Compass

Welcome to **PulseGrid**, a fresh take on the classic BPM helper concept, designed not merely to measure tempo but to *sculpt the flow of your set*. While traditional tools give you a number, PulseGrid gives you a *landscape*—a tactile, visual grid that syncs with the pulse of your music, helping you transition tracks with surgical precision and artistic intuition.

![PulseGrid Dashboard](https://img.shields.io/badge/PulseGrid-Dashboard-1DB954?style=for-the-badge&logo=spotify&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)
![Build Status](https://img.shields.io/badge/Build-Passing-brightgreen)

---

## 🌌 Why Another BPM Tool? The Philosophy of Pulse

Existing BPM counters are like rulers—they tell you the length, but not the texture. PulseGrid is like a **seismograph for your sound waves**. It doesn't just detect the beats; it visualizes the *energy signature* of each track, mapping kick drums, snare patterns, and hi-hat textures onto a dynamic grid. This allows you to *see* the breathing of a track before you mix it in.

### The Core Difference: From Numbers to Narratives
- **Traditional Tools**: "124 BPM."
- **PulseGrid**: "A 124 BPM track with an *aggressive, forward-leaning* waveform, best mixed with a *laid-back* 118 BPM track for a tension-building transition."

We achieve this through a proprietary **Momentum Detection Algorithm** (MDA) that analyzes frequency clusters over time, not just zero-crossings. The result is a mixing recommendation engine that understands musical *intent*.

---

## 🚀 Key Features That Redefine Workflow

### 1. 🕸️ Adaptive Waveform Grid
Forget static bars. PulseGrid projects a **live, harmonic grid** that resizes and color-shifts based on the track's spectral density. A sparse, ambient intro produces a wide, cool-blue grid; a dense, percussive drop compresses the grid into a hot-crimson lattice. This visual feedback loop makes harmonic mixing feel like a video game.

### 2. 🌐 Social Harmonic Matching (SHM)
Leverage the collective wisdom of the PulseGrid community. Our cloud-based **Harmonic Key Matrix** learns from thousands of successful transitions. When you load a track, PulseGrid suggests "soulmates"—tracks that are not just in the same key, but share similar *textural momentum*, even if they are in different genres.

### 3. 🔮 Predictive Energy Mapping (PEM)
Plan your set ahead of time. PEM uses machine learning to predict the *energy curve* of your playlist, flagging potential energy cliffs or plateaus. You can visually see if you are about to play three "peak-time" tracks in a row and adjust on the fly.

### 4. 🎛️ Modular Response Interface
PulseGrid isn't a fixed window. It's a suite of widgets—the **PulseDial**, **GridScope**, and **Transition Planner**—that you can drag, drop, and dock onto any secondary screen or tablet. Whether you prefer a minimal overlay or a full-war-room command center, PulseGrid adapts to your hardware.

### 5. 🧠 Offline First, Cloud Always
The core analysis engine runs entirely on your machine, respecting your privacy. Cloud features (like SHM) synchronize seamlessly when you choose to connect, but PulseGrid never forces an internet connection to perform basic analysis.

### 6. 📱 Responsive Touch Controls
Built from the ground up for hybrid setups. The grid responds to multi-touch gestures: pinch to zoom into a specific beat window, swipe to scrub through the harmonic progression, and long-press to set a cue point directly on the waveform lattice.

---

## 🛠️ Installation & Integration

PulseGrid is designed to be a flexible companion to your existing digital audio workstation (DAW) or hardware mixer. We provide lightweight integration bridges without bloating your system.

### For Desktop (Windows/macOS/Linux)
1.  Download the **PulseGrid Edge** binary for your specific OS architecture.
2.  Mount the `.dmg` or `.AppImage` package and drag the application to your preferred `Applications` folder.
3.  Launch PulseGrid and select your audio input source (system output, loopback device, or microphone).

### For Hardware Controllers
PulseGrid speaks standard MIDI and OSC protocols. Connect your controller, and the grid will automatically map to your faders and knobs based on a preset profile or a custom mapping you define.

### For DAW Integration (VST3 / AU / AAX)
- Place the `PulseGrid.module` file into your DAW's plug-in folder.
- In your DAW, instantiate PulseGrid on your master bus or an auxiliary channel.
- The grid will display the tempo and harmonic data of the audio routed through that channel.

---

## 🎯 Use Cases & Scenarios

### The Wedding DJ: Smooth Sailing
Keeps the floor moving by pre-visualizing the energy levels of your open-format playlist. The Predictive Energy Mapping helps you avoid sudden drops in pace during the "electric slide."

### The Club DJ: Peak-Time Precision
When the crowd is bouncing, you can't afford to look at a screen. PulseGrid's **Haptic Backpack Mode** (via a connected smartwatch) sends subtle vibration pulses that match the incoming track's beat, allowing you to keep eye contact with the crowd while your wrist tells you when to drop the next bassline.

### The Radio Presenter: Seamless Transitions
Use the Social Harmonic Matching to find unique segues between classic rock and modern pop, creating a signature "sound" for your radio show without clashing keys.

### The Producer: Remix Analysis
Break down a track you love. The Waveform Grid reveals the *rhythmic architecture* of the song, showing you exactly where the drums drop out and the pads are layered. It's a learning tool for musical arrangement.

---

## 💬 Community & Multilingual Support

PulseGrid is built for a global DJ community. The interface is fully translated into **12 languages**, including Spanish, German, Japanese, Mandarin, and Portuguese. The harmonic analysis models are trained on music from all over the world, ensuring accurate detection for genres like K-Pop, Afrobeats, Latin, and Bollywood.

Our **24/7 Support Concierge** is not a bot. It's a team of fellow DJs and producers who understand the frustration of a glitchy sync. Whether you have a question about a specific hardware setup or need advice on a tricky key change, we are available via chat or email, any time of day.

---

## 🧩 Roadmap: What’s Next for PulseGrid?

- **Q1 2026**: Release of `PulseGrid: Link Edition` for wireless synchronization with Pioneer CDJs (via a hardware dongle).
- **Q2 2026**: Implementation of "Crowd Resonance Analysis" to measure the apparent energy of the dancefloor via microphone input and suggest the next best transition.
- **Q3 2026**: Open-source our `Momentum Detection Algorithm` core for research and integration into audio education tools.

---

## 🤝 Contributing & Ecosystem

We believe in the wisdom of the crowd. While PulseGrid is a commercial product, we welcome contributions to our **Plugin SDK**. If you have an idea for a novel grid visualization or a new communication protocol for a vintage mixer, we provide the tools to build it.

- **Plugin SDK**: Write in C, C++, or Rust.
- **Theme Designer**: Create custom color palettes and grid textures to match your brand or mood.
- **Translation Hub**: Help us localize new features faster.

> **Note on Contributions:** We value quality over quantity. Please ensure your code adheres to our coding standards (documented in the `/specs` folder) and passes the existing test suite. For major feature additions, please open a discussion thread first to align with our vision.

---

## 📜 License & Legal

PulseGrid is dual-licensed. The core analysis engine for personal use is released under the **MIT License** for non-commercial, hobbyist use. For commercial broadcasting or club installations, a separate Commercial License is required.

For the open-source components, you are free to use, modify, and distribute the software, provided that you include the original copyright notice and disclaimer. This promotes transparency in the audio analysis community.

**Full MIT License Text:**

---

MIT License

Copyright (c) 2026 PulseGrid Contributors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

---

## ⚠️ Disclaimer & Safe Usage

**Audio Equipment Safety**: PulseGrid is a software tool designed for analysis and visualization. It does not modify your audio output unless you explicitly enable the "Keylock" feature. Please ensure your sound system is set to a reasonable volume level when calibrating the microphone input to avoid feedback loops or damage to your hearing.

**Data Privacy**: The cloud features aggregate anonymous data about track harmonic profiles. We do not collect, store, or transmit your actual audio files or your personal listening history. All local analysis is performed on your device.

**Beta Features**: Features marked as "Preview" in the roadmap may be unstable. We recommend using them for experimentation only, not for live events, until they are officially marked as stable.

---

## 🧭 Frequently Asked Questions (FAQ)

**Q: I have a massive music library. Will PulseGrid slow down?**
A: No. The database uses an efficient lazy-loading index. It will only load the detailed waveform data for the track you are currently viewing.

**Q: Can I use PulseGrid with my vinyl turntables?**
A: Yes! Use the microphone input mode. PulseGrid will analyze the ambient sound of your vinyl playback and generate a grid in real-time.

**Q: Do you have a mobile app?**
A: A companion mobile app for remote control based on your laptop's analysis is slated for Q4 2026. In the meantime, the web interface is fully responsive.

**Q: I don't see my hardware in the supported list.**
A: If your hardware supports MIDI over USB, you can map any knob or fader to any PulseGrid parameter manually. The profile editor is designed to be intuitive.

---

## 📡 Connecting With Us

We love hearing about your mixing epiphanies. Share your creative use cases and novel workflows with the hashtag #PulseGridMoment on social media.

- **For general feedback**: provide feedback via the built-in feedback console (Hotkey: `Ctrl + Shift + F`).
- **For bug reports**: check the [GitHub Issues](https://github.com/issues) page (please verify it is not a duplicate).
- **For partnership inquiries**: send a direct message to our official channel.

---

### Final Thoughts: Tune In, Power Up

PulseGrid is more than a tool; it's a new lens for listening. It invites you to see the music as a living entity, a waveform with a pulse and a memory. Whether you are a bedroom producer or a festival headliner, we built this so you can spend less time staring at numbers and more time feeling the groove.

Thank you for exploring the PulseGrid ecosystem. Now, go make the grids move.

---

**Copyright © 2026 PulseGrid Contributors. All rights reserved.**

*PulseGrid™ and GridScope™ are trademarks of the PulseGrid project. All other trademarks are property of their respective owners.*