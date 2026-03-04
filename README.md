<p align="center">
  <img src="https://img.shields.io/badge/version-2.0-blue?style=for-the-badge" alt="Version 2.0"/>
  <img src="https://img.shields.io/badge/java-25-orange?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java 25"/>
  <img src="https://img.shields.io/badge/javafx-GUI-purple?style=for-the-badge" alt="JavaFX"/>
  <img src="https://img.shields.io/badge/license-GPL--2.0-green?style=for-the-badge" alt="GPL-2.0 License"/>
  <img src="https://img.shields.io/badge/platform-windows-lightgrey?style=for-the-badge&logo=windows&logoColor=white" alt="Windows"/>
</p>

# ☁️ Caelum — Modern Weather Desktop App

**Caelum** is a sleek, modern, and lightweight desktop weather application built with **Java** and **JavaFX**. Get real-time weather forecasts, current conditions, and beautiful visualizations — all in an elegant graphical interface, no browser needed.

> *Caelum* — Latin for "sky" — because the sky should look good on your desktop too.

---

## ✨ Features

- **Real-Time Weather Data** — Fetches live weather information using HTTP APIs.
- **Modern GUI** — Clean, contemporary JavaFX interface with smooth visuals.
- **Lightweight & Fast** — Minimal resource footprint; launches in seconds.
- **Self-Contained** — Ships with a bundled Java 25 runtime — no JDK installation required.
- **Native Executable** — Packaged via `jpackage` as a native Windows `.exe` for one-click launch.

---

## 🚀 Getting Started

### Prerequisites

None! Caelum ships as a fully self-contained application with an embedded Java runtime.

### Installation

1. Download or clone this repository:
   ```bash
   git clone https://github.com/TheBenn/Caelum.git
   ```
2. Navigate to the `Caelum` directory.
3. Run **`Caelum.exe`** — that's it!

> No Java installation, no environment variables, no configuration. Just launch and go.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **Java 25** | Core application language |
| **JavaFX** | Modern GUI framework (controls, graphics) |
| **java.net.http** | Built-in HTTP client for weather API requests |
| **jpackage** | Native application packaging & bundled runtime |

---

## 📁 Project Structure

```
Caelum/
├── Caelum.exe              # Native Windows launcher
├── app/
│   ├── Caelum.jar          # Main application JAR
│   ├── Caelum.cfg          # App configuration (classpath, main class, JVM options)
│   └── .jpackage.xml       # jpackage build metadata
└── runtime/                # Bundled Java 25 runtime (JRE)
    ├── bin/
    ├── conf/
    ├── legal/
    ├── lib/
    └── release
```

---

## 📸 Screenshots

<!-- Add your screenshots here -->
<!-- ![Caelum Main Screen](screenshots/main.png) -->
<!-- ![Caelum Forecast View](screenshots/forecast.png) -->

*Screenshots coming soon.*

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the **GNU General Public License v2.0 (GPL-2.0)** — the same license used by the Linux kernel.

You are free to use, modify, and distribute this software under the terms of the GPL-2.0. See the [LICENSE](LICENSE) file for full details, or read the complete license text at:  
🔗 https://www.gnu.org/licenses/old-licenses/gpl-2.0.html

---

## 👤 Author

**The Benn**

- GitHub: [@TheBenn](https://github.com/TheBenn)

---

## ⭐ Show Your Support

If you found Caelum useful, give it a ⭐ on GitHub — it helps others discover the project!

---

<p align="center">
  <sub>Built with ☕ Java & ❤️ by The Benn</sub>
</p>
