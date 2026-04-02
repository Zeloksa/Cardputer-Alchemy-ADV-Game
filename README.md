![Version](https://img.shields.io/badge/Version-1.0_ADV-blue)
![Hardware](https://img.shields.io/badge/Hardware-Cardputer-orange)
![Platform](https://img.shields.io/badge/Platform-M5Stack-red)
![License](https://img.shields.io/badge/License-Proprietary-gray)
[![Boosty](https://img.shields.io/badge/Support-Boosty-orange)](https://boosty.to/zeloksa)

# ⚗️ Alchemy ADV (V1.0)

**Alchemy V1.0 ADV** is a highly optimized, visually rich element-combining puzzle game specifically engineered for the **M5Stack Cardputer ADV**. Starting with just 4 basic elements (Water, Fire, Earth, Air), players can combine and evolve their inventory to discover up to **186 unique items**, ranging from basic nature to advanced technology and mythical creatures.

> [!IMPORTANT]
> **Source Code Status:** This project is proprietary. The source code is private. 
> **Distribution:** Binary (`.bin`) only via the **Releases** tab.

---

## ⚡ Technical Highlights

* **Dynamic Environment Engine:** The game features a real-time, smoothly transitioning Day/Night cycle (120-second phases). The background is fully animated with custom events including drifting clouds, rotating suns, meteor showers, flying witches, and highly detailed rocket launches.
* **Intelligent Hint System:** A built-in algorithm that scans the player's currently unlocked inventory against the entire recipe map to find valid, undiscovered combinations, highlighting the target item without spoiling the exact recipe.
* **SD Card Persistence:** Zero-friction auto-saving. Every newly discovered element is instantly written to `/alchemy.txt` on the SD card, ensuring progress is never lost.
* **Custom "Open Book" UI:** The interface mimics a vintage grimoire with categorized side-tabs, integrated search functionality, and an interactive 32-slot Library grid to track completion progress.

---

## 🛠 Installation

> [!NOTE]  
> **Prerequisite:** Insert a formatted MicroSD card into your Cardputer before playing. This is required for the auto-save functionality to retain your unlocked elements.

### Method 1: M5Burner (Recommended)
1. Open **M5Burner**.
2. Search for `Alchemy ADV` or `Zeloksa`.
3. Select version **V1.0**.
4. Burn to your M5Stack Cardputer.

### Method 2: Manual Flashing
1. Go to the **[Releases]** tab on the right side of this GitHub repository.
2. Download the latest **Alchemy ADV `.bin`** file.
3. Flash the `.bin` to your M5Stack Cardputer using **M5Burner** (via the local file option) or the official **Espressif ESP32 Download Tool**.

---

## 🕹 Controls
* **[ ; / . / , / / ]** (or Arrows): Navigate elements and categories (Up/Down/Left/Right).
* **[ ENTER / SPACE ]**: Select Element A / Select Element B / Confirm.
* **[ Q / ESC ]**: Cancel current selection.
* **[ H / ? ]**: Activate Hint System (highlights a valid element for a new recipe).
* **[ 1 / 2 ]**: Turn pages backward (1) and forward (2).
* **[ - / = ]**: Adjust Master Volume (10% increments).
* **[ A-Z ]**: Quick Search (type to instantly filter your unlocked elements).
* **[ DEL / BACKSPACE ]**: Delete search character.

---

## 📖 Comprehensive User Manual

### 📖 The Book of Knowledge (Main UI)
The main screen is divided into two pages. On the far left and right are category tabs (Base, Nature, Animal, Mixed, Energy, Microbes, Tech, and Library). 
* Navigate `Left/Right` to switch between focusing on the category tabs or the elements on the pages.
* Press `Up/Down` while focused on the tabs to quickly swap categories.
* Press `Enter` on an element to select it (it will be highlighted in green with a "1" badge). Select a second element to attempt a combination.

### 🔍 Search & Filtering
If you have a massive inventory, simply start typing on the Cardputer keyboard. A `SEARCH` bar will appear at the top, instantly filtering your current view to elements matching your input. Press `Q` or delete all characters to exit search mode.

### 📚 The Library (Progress Tracker)
The bottom-right tab opens the Library. This mode displays a dense 8x4 grid showing your overall completion percentage (e.g., `[ 136 / 186 ]`).
* **Colored Icons:** Elements you have successfully discovered.
* **Shadowed Silhouettes:** Elements that exist in the game but haven't been unlocked yet. Use these shapes as visual clues for what you need to craft next!

### 🎇 Particle Merging & Events
When a valid combination is found, the game initiates a particle-swarm merge animation ending in an explosive flash. If the screen goes dark, watch the background—rare events like UFOs, Parachutists, or Airships may appear depending on the time of day.

---

## 🆕 Alchemy ADV (V1.0) Release Notes
* **Initial Release:** 186 fully playable elements and recipes.
* **Engine:** Custom 160MHz underclocking applied for extreme battery saving without sacrificing UI framerate.
* **Audio:** Adaptive dual-soundtrack system (switches BGM based on the internal Day/Night phase).
* **QoL:** Added visual "NEW" red dot indicators for recently crafted items.

---

## 💬 Feedback & Suggestions
If you find a bug, have a suggestion for a new element, or want to report a broken recipe:
1. Go to the **[Issues]** tab at the top of this repository.
2. Click **[New Issue]**.
3. Describe your problem or idea in detail.

---

## ☕ Support the Project
If you enjoy this game or my other Cardputer tools, consider supporting further development and new content updates:
* **[https://boosty.to/zeloksa]**

---
*Developed by Engineer Zeloksa. Strictly optimized for Cardputer ADV.*
