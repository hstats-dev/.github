# 🛡️ HStats.dev (Hytale Mod Stats)

**HStats** is a lightweight, real-time analytics platform specifically designed for the **Hytale** modding community. Inspired by bStats for Minecraft, HStats allows mod developers to visualize their impact with live server counts, player metrics, and system-level data.

[**Visit HStats.dev**](https://hstats.dev) | [**View Documentation**](https://hstats.dev/docs)

---

## 📂 Our Repositories

### 💻 [HStats-Frontend](https://github.com/hstats-dev/HStatsFrontend)
The HStats web dashboard built for speed and clarity. This handles user registration, mod management, and the rendering of analytics charts.
* **Status:** Public

### ⚙️ HStats-Backend (Private for the moment, will be public soon)
The engine under the hood. The backend API handles incoming pings from Hytale servers, processes data anonymously, and serves the analytics API that powers the frontend.
* **Status:** Private / Internal Development

### 🛠️ [HStatsExamplePlugin](https://github.com/hstats-dev/HStatsExamplePlugin)
The official reference implementation for Hytale mod developers. This repository contains the `HStats.java` class and a boilerplate setup to show you how to integrate analytics into your mod.
* **Language:** Java
* **Status:** Public / Reference Implementation

---

## 🔒 Privacy
HStats does **not** track player IPs, usernames, or sensitive data. We only collect:
* Operating System & Java Version
* General Geographic Region (Country level)
* Active Server/Player Counts

---

## 🤝 Getting Involved
If you are a Hytale developer and want to start tracking your mod:
1.  Create an account at [HStats.dev](https://hstats.dev).
2.  Register your mod and grab your **UUID**.
3.  Check out the **ExamplePlugin** repository to get started.
