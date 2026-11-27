# Hi, I'm Saabith Jiffry

Software builder focused on practical classroom, live-streaming, and cross-device tools for Windows, Android, and the browser.

---

## Featured Project: PresenterSync

[![Website Portal](https://img.shields.io/badge/Portal-saabithjiffry.github.io-10B981?style=for-the-badge)](https://saabithjiffry.github.io)
[![Latest Release](https://img.shields.io/github/v/release/SaabithJiffry/PresenterSync?style=for-the-badge&color=0EA5E9)](https://github.com/SaabithJiffry/PresenterSync/releases/latest)
[![Source Repo](https://img.shields.io/badge/GitHub-PresenterSync-111827?style=for-the-badge)](https://github.com/SaabithJiffry/PresenterSync)

**PresenterSync (v10.1.1)** bridges **OBS Studio**, **Zoom / Microsoft Teams / Google Meet**, **Microsoft PowerPoint**, **Windows Remotes**, **65"+ Android Smart Boards**, **Android Phones**, and a **Zero-Install Browser Web Remote** (iOS, iPadOS, macOS, Linux, Chromebook) into one synchronized presenter workflow:

* **Adaptive 4-Tier Host HUD + Independent Scene & Mic Pills:** CoreAudio VU meter, perimeter hold safeguards (`Mic`, `Rec` click Start/Pause/Resume + hold Stop, `Studio` hold bar), drift-free OBS recording timer sync, scrolling **Active Program Scene** marquee + `700ms` Hold-to-Reset Active Scene (toggling enabled sources without exposing hidden ones), read-only `Stream` health pill, `1.25x` crisp scaling, `MutedOrAlert` / `CornerTallyDot` visibility modes, capture exclusion (`WDA_EXCLUDEFROMCAPTURE` / `FLAG_SECURE`), an independent primary-only Secondary Mic Pill, and a standalone Remote Active Scene HUD across Windows Remote, Android, and Web Remote.
* **Wireless Director Deck, Operator Console & Phone/Smartboard Ergonomics:** Multi-device scene transitions, Preview Scene control, `"BRB"` Standby curtains, 1-action Panic Curtain, non-suspending Live Operator Console, two-way Stage Intercom (`Got It ✓` / `Signal Host`), always-visible **Reconnect Host**, redesigned Android OLED Podium Deck with balanced 2-row Timer presets, cutout-safe floating overlays (`fitInsetsTypes = 0` + DPI-aware palm rejection), 2×1 Home Widget, and 1-click **Capture Keystroke** workflow across all 43 shortcut fields.
* **Protocol v2, RBAC, Security & Zero-Config Failover:** 3-tier Role-Based Access Control (`Tally-Only`, `Presenter`, `Director`) with policy-gated Direct OBS `:4455` fallback, capture-excluded Kiosk PIN lock, Windows DPAPI & Android Keystore secret storage, `PSGCM2` AES-256-GCM WAN Relay, Classroom UDP auto-discovery (`:4457`), LAN Host Bridge (`:4456`), and zero-install HTML5 Web Remote with reconnect & NACK toasts.
* **Session Timeline, Classroom Reset & Verified Updates:** Bounded 2,000-event timeline exporting Video Editor CSV chapters, Markdown summaries, and YouTube timestamps, 1-click Classroom Session Reset, plus fail-closed SHA-256 verified Windows/Android self-updaters and chunked LAN APK serving (`>= 16 MB`).

---

## Tech Stack
`AutoHotkey v2` · `Win32 GDI+ / UIA / WinINet` · `Kotlin` · `Jetpack Compose` · `HTML5 / ES6 Web Remote` · `OkHttp WebSockets` · `OBS WebSocket v5` · `Python E2E`
