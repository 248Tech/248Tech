## Joe W · 248Tech LLC

**I build self-hosted software for running game servers, monitoring cameras and managing event rentals.**

I have run a gaming community of more than 3,000 members since 2014, and I spent seven years in event rental operations, five of them in management. Most of my software comes out of that work: keeping game servers healthy without losing player progress, watching cameras without a cloud subscription, and quoting rentals without double-booking inventory. It runs on hardware you control, and the open-source flagship READMEs state what each project does, how it is tested and what is not finished yet.

<a href="https://248tech.github.io/project-inquiry/"><img src="assets/start-a-project.svg" alt="Got an idea? Let's build it. Start a project with 248Tech." width="100%"></a>

**[Portfolio and demos](https://248tech.github.io)** · **Work inquiries:** [start a project](https://248tech.github.io/project-inquiry/) or [joe@248tech.com](mailto:joe@248tech.com) · **Bugs and support:** open an issue on the project's repository

### Flagship projects

#### [Mastermind 7DTD](https://github.com/248Tech/Mastermind-7DTD-AI-Server-Manager): server manager for 7 Days to Die communities

A Go agent on each game host takes jobs from a NestJS control plane with a Next.js dashboard. Safe restarts warn players, wait out Blood Moon, take a full backup and confirm the server is empty before restarting. Also handles mod quarantine, save backups, a live map, a player portal and Discord alerts. Runs the servers for my own community in production.

Go · TypeScript · PostgreSQL · Redis · [Browser demo (simulated data)](https://248tech.github.io/Mastermind-7DTD-AI-Server-Manager/) · Actively maintained · Minecraft port: [Mastermind Minecraft](https://github.com/248Tech/Mastermind-Minecraft-Server-Manager) (early)

#### [RTSPanda](https://github.com/248Tech/RTSPanda): self-hosted hub for RTSP cameras

A Go server that supervises mediamtx: restarts it when it exits, reloads after repeated failed health checks and repairs stalled camera streams. Browser live view over HLS, per-camera recording, local YOLO detection on sampled frames or Frigate events, and Discord alerts. Runs on Docker or a Raspberry Pi.

Go · React · Python/ONNX Runtime · [Browser demo (simulated data)](https://248tech.github.io/RTSPanda/demo/) · Beta

#### [RentalOS](https://248tech.github.io/rentalos-site/): event rental management (commercial, source private)

Inventory availability that separates confirmed bookings from pending quotes, quoting with a click-to-sign audit trail, pull sheets for the warehouse, a public SEO catalog and an optional AI assistant whose changes require user confirmation.

React · Express · SQLite · [Product site and browser demo (simulated data)](https://248tech.github.io/rentalos-site/) · Pre-release testing

### Other projects

- **[LiteMap](https://github.com/248Tech/litemap)**: measure sites from satellite imagery and check whether tents and vehicles fit, to scale. Node.js, OpenAPI 3.1 API. [Demo](https://248tech.github.io/litemap/)
- **[ShowTime](https://github.com/248Tech/ShowTime)**: self-hosted watch-party server with synced rooms, passphrase-based end-to-end encrypted chat and a media library encrypted at rest. Node.js. [Demo](https://248tech.github.io/ShowTime/)
- **[GarageIQ](https://github.com/248Tech/GarageIQ)**: planner for vehicle restorations with dependent tasks, parts and expenses, and offline sync. Source-available. [Overview](https://248tech.github.io/GarageIQ/)
- **Windows apps:** [Tidy](https://github.com/248Tech/Tidy) (PC cleaner and system monitor with Recycle Bin undo) · [Tidy Lite](https://github.com/248Tech/Tidy-Lite) (111 KB native edition for low-memory PCs) · [QwenPad](https://github.com/248Tech/QwenPad) (sticky notes with a local LLM via llama.cpp) · [ImgConvert](https://github.com/248Tech/ImgConvert) (offline batch image converter, including HEIC) · [LyricVision](https://github.com/248Tech/LyricVision) (synced Spotify lyrics overlay) · [GhostReel](https://github.com/248Tech/GhostReel) (click-through video overlay) · [DarkNotepad](https://github.com/248Tech/DarkNotepad)
- **Community tools:** [fortnite-updates-bot](https://github.com/248Tech/fortnite-updates-bot) (Discord news bot) · [fortnite-cosmetics-browser](https://github.com/248Tech/fortnite-cosmetics-browser)

### How I work

I build with AI coding assistants and keep their attribution in the commit history. The open-source flagship READMEs list their tests, current status and known limitations, so you can check the work rather than take my word for it.
