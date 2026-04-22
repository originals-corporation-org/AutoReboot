# 🚀 Auto Reboot (Fabric)

**Auto Reboot** is a professional-grade server utility for Minecraft (Fabric) designed to handle automated restarts with precision. Whether you run a small private server or a high-traffic public network, this mod ensures your server stays fresh and stable without manual intervention.

---

## ✨ Key Features

* **Three Operational Modes:** Complete control via manual execution, time intervals, or precise 24-hour scheduling.
* **Safety First (Auto-Save):** Forcefully saves the world (`save-all`) the moment a reboot is triggered to prevent data corruption.
* **Smart Chat Warnings:** Customizable alert schedule (e.g., 10, 5, 2, and 1 minutes) to keep players informed.
* **Visual Countdown:** High-visibility titles and subtitles appear in the center of the screen during the final 5 seconds.
* **JSON5 Configuration:** Modern configuration format supporting comments for easier management without server restarts.
* **Script Automation:** Automatically triggers a launch script (`.bat` or `.sh`) upon shutdown for a seamless reboot cycle.

---

## 🛠 Commands & Permissions

| Command | Permission | Description |
| :--- | :--- | :--- |
| `/reboot` | **OP Level 4** | Initiates the reboot sequence. |
| `/reboot info` | **All Players** | Displays current mode, progress bar, and time remaining. |
| `/reboot reload` | **OP Level 4** | Reloads configuration and language files instantly. |

---

## ⚙️ Configuration

All files are automatically generated in the `/config/autorebootmod/` directory upon the first launch.

### 1. Main Configuration (`autorebootmod.json5`)
* **Manual:** Server only stops via administrative command.
* **Interval:** Restarts every X minutes based on server uptime.
* **Scheduled:** Restarts at specific 24-hour marks (e.g., `00:00`, `06:00`, `12:00`, `18:00`).

### 2. Localization (`en_us.json5` / `ru_ru.json5`)
Supports full customization of prefixes, colors (using the `§` symbol), and notification text.

---