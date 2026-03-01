# 🍪 FluffySnapCracker ☁️

**The crispiest, fluffiest, high-performance HTML screen recorder.**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A lightweight, no-bulls**t, pure JavaScript solution for recording your browser or desktop directly from an HTML page. **FluffySnapCracker** captures crisp video at high frame rates, without bloating your memory, and saves it instantly as a high-quality WebM file. *And yes, it's FREE for EVERYONE.*

---

## 🔥 Features

* 🚀 **High Performance:** Captures $60\text{ fps}$ (or higher) with minimal system load.
* 🪶 **Ultra-Lightweight:** Written in pure HTML/CSS/JS (no heavy framework dependencies).
* 🌐 **In-Browser:** No extensions or plugins required.
* 💾 **Instant Download:** Automatically generates a smooth `.webm` file when you stop recording.
* 🎛️ **Audio Support:** Option to include system audio or microphone input.
* ✈️ **Offline Capable:** Runs entirely on the client side with no server dependency or internet required.

## 🛠️ How it Works

FluffySnapCracker utilizes the native web `getDisplayMedia` API and `MediaRecorder` interface to interface directly with your browser's recording engine. This ensures maximum compatibility and efficiency.

---

## 🚀 Quick Start

1.  **Clone the repo:**
    ```bash
    git clone [https://github.com/sandevmihiranga/FluffySnapCracker](https://github.com/sandevmihiranga/FluffySnapCracker)
    ```
2.  **Open `FluffySnapCracker.html`** directly in Chrome, Firefox, or Edge. (No server setup needed, but it works fine on a live site too!).
3.  **Click 'Start Recording',** choose your screen/window, and record!
4.  **Click 'Pause/Resume', take a break and start just where you left off.
5.  **Click 'Stop Recording'** to automatically download your video.

## ⚙️ Configuration

You can tweak the performance settings within the JavaScript (`recorder.js`):

| Parameter | Default | Description |
| :--- | :--- | :--- |
| `frameRate` | `60` | Higher = smoother, larger file size. |
| `videoBitsPerSecond` | `5000000` | Defines quality ($5\text{ Mbps}$). |
| `mimeType` | `video/webm; codecs=vp9` | High-quality, modern web codec. |

---

## 🤝 Contributing & Usage Rules

**FluffySnapCracker** is open-source for the community! However, to keep the spirit of the project alive, please follow these guidelines:

* **Contribute to the Engine:** We love Pull Requests! If you can make the recording smoother or the files smaller, please submit a PR.
* **Respect the Vibe:** If you fork this project, please keep the original **FluffySnapCracker** branding, icons, and the "vibe coded with Gemini AI" credit intact.
* **Don't Rebrand:** Please do not simply swap the icons and re-release this as your own standalone product. Let's keep the Fluffy family together!

### How to Contribute
1. Fork the Project.
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`).
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the Branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

## ⚖️ License

Distributed under the MIT License. See `LICENSE` for more information.

---

## 💖 Credits

Created with ❤️ by **sandevmihiranga**.

**vibe coded with Gemini AI.** *Because we like creamcrackers and fluffy things, but we demand high performance.*
