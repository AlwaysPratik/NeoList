<p align="center">
  <img src="assets/main.png" alt="NeoList Logo" width="140" style="border-radius: 50%; box-shadow: 0 4px 14px rgba(0,0,0,0.15);">
</p>

<h1 align="center">NeoList 📝</h1>

<p align="center">
  <strong>A modern, minimalist, and lightweight task management app built with Flutter.</strong><br>
  Stay organized, set priorities, meet deadlines, and boost your daily productivity with zero clutter.
</p>

<p align="center">
  <a href="https://play.google.com/store/apps/details?id=com.yourname.easy_notes&hl=en_IN">
    <img src="https://img.shields.io/badge/Google_Play-Get%20it%20on%20Play%20Store-34A853?style=for-the-badge&logo=google-play&logoColor=white" alt="Get it on Google Play">
  </a>
</p>

<p align="center">
  <a href="https://github.com/AlwaysPratik/NeoList/releases">
    <img src="https://img.shields.io/badge/version-v1.2-0288D1.svg?style=flat-square" alt="Version">
  </a>
  <a href="https://flutter.dev">
    <img src="https://img.shields.io/badge/Flutter-%3E%3D3.8.1-02569B?style=flat-square&logo=flutter&logoColor=white" alt="Flutter Version">
  </a>
  <a href="https://dart.dev">
    <img src="https://img.shields.io/badge/Dart-%3E%3D3.8.1-0175C2?style=flat-square&logo=dart&logoColor=white" alt="Dart Version">
  </a>
  <a href="https://github.com/AlwaysPratik/NeoList/stargazers">
    <img src="https://img.shields.io/github/stars/AlwaysPratik/NeoList?style=flat-square&color=gold" alt="GitHub Stars">
  </a>
  <a href="https://github.com/AlwaysPratik/NeoList/blob/main/LICENSE">
    <img src="https://img.shields.io/badge/license-MIT-green.svg?style=flat-square" alt="License">
  </a>
  <img src="https://img.shields.io/badge/platform-Android%20%7C%20Web%20%7C%20Windows-lightgrey?style=flat-square" alt="Platform Support">
</p>

---

## 📲 Download on Google Play Store

Experience **NeoList** directly on your Android device:

<div align="center">
  <a href="https://play.google.com/store/apps/details?id=com.yourname.easy_notes&hl=en_IN" target="_blank">
    <img src="https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png" alt="Get it on Google Play" height="80">
  </a>
  <br>
  👉 <a href="https://play.google.com/store/apps/details?id=com.yourname.easy_notes&hl=en_IN"><strong>Install NeoList on Google Play</strong></a>
</div>

---

## 📸 App Screenshots & Preview

<div align="center">
  <table>
    <tr>
      <td align="center" width="25%">
        <strong>🏠 Dashboard & Tasks</strong><br><br>
        <img src="assets/screenshot_home.png" width="190" alt="Dashboard Screen" style="border-radius: 12px; box-shadow: 0 4px 10px rgba(0,0,0,0.1);"><br><br>
        <sub>Clean overview of pending & completed tasks</sub>
      </td>
      <td align="center" width="25%">
        <strong>➕ Add & Schedule</strong><br><br>
        <img src="assets/screenshot_add.png" width="190" alt="Add Task Screen" style="border-radius: 12px; box-shadow: 0 4px 10px rgba(0,0,0,0.1);"><br><br>
        <sub>Quick title, notes, and calendar deadline picker</sub>
      </td>
      <td align="center" width="25%">
        <strong>🏷️ Priorities & Labels</strong><br><br>
        <img src="assets/screenshot_priority.png" width="190" alt="Priority & Labels" style="border-radius: 12px; box-shadow: 0 4px 10px rgba(0,0,0,0.1);"><br><br>
        <sub>Categorize by Study, Work & color-coded priorities</sub>
      </td>
      <td align="center" width="25%">
        <strong>⚡ Swipe Gestures</strong><br><br>
        <img src="assets/screenshot_swipe.png" width="190" alt="Swipe Quick Actions" style="border-radius: 12px; box-shadow: 0 4px 10px rgba(0,0,0,0.1);"><br><br>
        <sub>Smooth swipe-to-reveal quick Edit & Delete buttons</sub>
      </td>
    </tr>
  </table>
</div>

> 💡 *Tip: You can update these preview pictures at any time by replacing the image files inside the `assets/` folder.*

---

## 🌟 Key Features

- 🎯 **Simple & Intuitive Task Flow** — Create, edit, complete, or remove to-dos in seconds with zero friction.
- 🏷️ **Smart Category Labels** — Organize your tasks by built-in tags:
  - 📌 `Today`
  - 🚨 `Important`
  - 📚 `Study`
  - 💼 `Work`
  - 👤 `Personal`
- 🚦 **3-Tier Priority Tagging** — Color-coded visual badges so you always tackle what matters first:
  - 🔴 **High Priority** — Critical deadlines and urgent action items
  - 🟣 **Medium Priority** — Important everyday routines
  - 🔵 **Low Priority** — Backlog and future ideas
- 📅 **Integrated Due Date Scheduling** — Set deadlines with the built-in calendar picker to ensure no milestone is missed.
- 👆 **Interactive Swipe-to-Reveal Cards** — Slide any task card to quickly access dedicated **Edit** (✏️) and **Delete** (🗑️) controls.
- 💾 **Dual-Layer Redundant Offline Storage**:
  - Ultra-fast key-value caching using `shared_preferences`.
  - Multi-location automated JSON file backup (`todos.json` in Documents, external storage fallback, and `todo/todos_backup.json`).
  - **100% Offline** — Your data stays private on your device with no internet connection required.
- 🎨 **Minimalist Material Design 3** — Soft contrast, rounded geometry, distraction-free typography, and responsive animations.

---

## 🛠️ Tech Stack

| Component | Technology | Description |
| :--- | :--- | :--- |
| **Framework** | [Flutter 3](https://flutter.dev) | Cross-platform UI toolkit with Material 3 |
| **Language** | [Dart](https://dart.dev) (>= 3.8.1) | Strongly typed client-optimized language |
| **Fast Storage** | [`shared_preferences`](https://pub.dev/packages/shared_preferences) | Fast persistent key-value local cache |
| **File Persistence** | [`path_provider`](https://pub.dev/packages/path_provider) | Access to internal and external device storage |
| **Path Handling** | [`path`](https://pub.dev/packages/path) | Safe filesystem path manipulation |
| **Data Format** | `dart:convert` (JSON) | Structured offline serialization & backups |
| **Supported Platforms** | Android, Web, Windows, macOS, Linux | Multi-platform compiled from single codebase |

---

## 📂 Project Structure

```plaintext
NeoList/
├── android/                   # Native Android Gradle configuration
│   └── app/
│       ├── build.gradle.kts   # App ID: com.yourname.easy_notes (v1.2, code 4)
│       └── src/main/          # AndroidManifest, launcher icons & resources
├── assets/                    # Visual assets & preview screenshots
│   ├── main.png               # Brand artwork & app illustration
│   ├── screenshot_home.png    # Preview: Dashboard
│   ├── screenshot_add.png     # Preview: Add task
│   ├── screenshot_priority.png# Preview: Priorities & labels
│   └── screenshot_swipe.png   # Preview: Swipe gestures
├── lib/
│   └── main.dart              # Entire app entrypoint, models, state & UI screens
├── web/                       # Web entrypoint, manifest & PWA assets
├── windows/                   # Windows runner & desktop build files
├── pubspec.yaml               # App metadata, dependencies & asset registration
└── README.md                  # Comprehensive GitHub documentation
