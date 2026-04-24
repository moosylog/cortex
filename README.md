<div align="center">
  
# ⚡ CORTEX
**A neuro-reactive typing survival system**

[![HTML5](https://img.shields.io/badge/HTML5-Strict-E34F26?style=for-the-badge&logo=html5&logoColor=white)](#)
[![Zero Dependencies](https://img.shields.io/badge/Dependencies-0-00FF66?style=for-the-badge)](#)
[![eSports Ready](https://img.shields.io/badge/eSports-Ready-BC13FE?style=for-the-badge)](#)
[![Moosy Research](https://img.shields.io/badge/Moosy_Research-2026-00E5FF?style=for-the-badge)](#)

> *CORTEX is a high-octane, split-brain typing survival engine designed for competitive ergonomic keyboard players.*

</div>

---

## 🌐 Overview

CORTEX is not a standard typing test—it is an **eSports-grade reflex engine**. Designed specifically for split-ergonomic keyboards, CORTEX forces players to decouple their hands, read independent radial vectors, and type under extreme pressure. 

Built with a relentless focus on performance, CORTEX is a single, zero-dependency HTML5 file. No frameworks, no build steps, no external assets. Just pure, hyper-optimized JavaScript running a bespoke rendering pipeline and spatial audio engine directly in the browser.

---

## 🚀 Key Features

* **Dual-Hemisphere Targeting:** Words spawn on either the Left (SYS.RADAR) or Right (SYS.TACTICAL) monitor. You must type the word using only the corresponding hand's layout.
* **Dynamic Threat Scaling (DDA):** The system constantly analyzes your APM (Actions Per Minute) and accuracy. Miss a keystroke or take damage, and the threat decreases. Slay enemies efficiently, and the speed and complexity ramp up aggressively.
* **45-Second Sprints:** Endurance is broken into intense 45-second levels. Survive the sprint to clear the level and enter the next, more dangerous phase.
* **Cinematic Broadcast UI:** Features a dynamic CRT-glitch pipeline, frosted-glass overlays (`backdrop-filter`), and layout scaling that looks flawless on both 4K tournament displays and standard 1080p laptops.
* **Persistent Hall of Fame:** Secure `localStorage` caching keeps track of your exact hardware configuration, layout mappings, and your Top 5 highest scores across sessions.
* **Spatial Audio Engine:** Built on the Web Audio API. Pitch-shifting hit markers, directional laser panning, and heavy EMP bass-drops. 

---

## ⌨️ Supported Hardware

CORTEX features native geometry mapping for the world's most popular competitive split keyboards:

* **MoErgo Glove80**
* **MoErgo Go60**
* **Corne (42-key)**
* **ZSA Voyager**
* **Standard ANSI 60%**

### 📁 Custom Hardware Injection
CORTEX includes a custom JSON parser. You can directly upload a `MoErgo JSON` layout file in the setup menu. The game will instantly read your layers, map your custom keycodes to the precise geometric coordinates of your board, and dynamically update the dictionary pool to ensure valid keystrokes.

---

## 🕹️ Gameplay Mechanics

1. **TARGET LOCK:** Press the first letter of an approaching threat to lock onto it. You cannot switch targets until the current threat is destroyed.
2. **COMBO MULTIPLIER:** Sequential hits build your combo meter, multiplying your score and ramping up the audio pitch. A single missed keystroke breaks the combo.
3. **CORE LINK (EMP):** Destroying targets charges your Synergy bar. At 100%, the system initiates a countdown. Type the high-level **Synergy Word** flawlessly to detonate an EMP, wiping the board, restoring Hull Integrity, and granting a massive score bonus.
4. **THREAT TYPES:**
   * **Standard (Cyan/Pink):** Linear pathing.
   * **Surprise (Yellow):** Ultra-fast, single-character interceptors.
   * **Weaver (Teal):** Enemies that move in sine-wave oscillation patterns.
   * **Pulse (Purple):** Slow moving, highly complex, multi-syllable targets.

---

## 🛠️ Installation & Usage

Because CORTEX is a strictly optimized, zero-dependency engine, installation is instant:

1. Clone or download this repository.
2. Double-click `index.html` to open it in any modern browser (Chrome, Edge, Firefox, Brave).
3. Select your hardware and layout.
4. Click **INITIALIZE CORTEX**.

*(Note: Ensure your browser allows local file execution and Web Audio API playback).*

---

## 🏆 Championship Ruleset

* **No Pausing:** Once CORTEX is initialized, the system cannot be paused. You must survive the sprint or power off the system.
* **Layout Integrity:** Uploaded custom JSONs are validated upon initialization. Layouts missing core vowels or heavy consonant clusters on either half will be rejected.
* **Scoring:** Final scores are recorded to the local cache only upon Hull Integrity failure or manual abort.

---

<div align="center">
  <p><i>"Split the brain. Link the core. Survive the sprint."</i></p>
  <b>© 2026 Moosy Research - All rights reserved.</b>
</div>
