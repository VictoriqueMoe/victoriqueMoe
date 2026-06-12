<div align="center">

  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:3a1c71,50:d76d77,100:ffaf7b&height=200&section=header&text=Backend%20Engineer&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=32&desc=Java%20%7C%20Go%20%7C%20Node.js%20%7C%20Distributed%20Systems&descSize=16&descAlignY=55" width="100%" />

  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=2600&pause=900&color=E0A0FF&center=true&vCenter=true&width=780&lines=Building+scalable+backends+and+distributed+systems;Java+and+Go+for+high-throughput+services;Node.js+and+TypeScript+for+APIs+and+tooling;Security%2C+reliability%2C+and+clean+architecture" />

  <br/>

  <img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="700"/>

</div>

## About

I am a backend-focused software engineer with experience in:

- high-throughput and concurrent backends  
- distributed systems and microservices  
- secure data and file pipelines  
- real-time APIs and integration work  

I primarily work with **Java**, **Go**, and **Node.js/TypeScript**, and I care a lot about reliability, observability, and production-readiness rather than throwaway demos.

---

## Core Skills

- Design and implementation of **REST / JSON APIs** and backend services  
- **Java** (Spring-based backends, messaging, persistence)  
- **Go** (microservices, workers, concurrency patterns)  
- **Node.js / TypeScript** (APIs, bots, tooling)  
- Data stores: **PostgreSQL**, **Redis**  
- Containerization and dev tooling: **Docker**, **Linux**  
- Secure handling of user data and files, including encryption and access control  

---

## Tech Stack

<div align="center">

  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" />
  <br/>
  <img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white" />
  <img src="https://img.shields.io/badge/Express-404D59?style=for-the-badge&logo=express&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
  <br/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />

</div>

---

## Featured Projects

### WaifuVault – Secure File Hosting Platform  
Repository: https://github.com/waifuvault/WaifuVault

- Production-grade secure file hosting platform currently serving **3,769+ public files** with a total footprint of **55.32 GiB**  
- Backend built with **Node.js / TypeScript**, with supporting services and infrastructure components  
- End-to-end encrypted file storage with **temporary, permission-based access links**  
- **Streaming-first architecture** for uploads and downloads to avoid loading large files into memory  
- Data layer powered by **PostgreSQL** with **Redis** for caching, rate-limiting, and transient state  
- Fully **containerized with Docker**, enabling reproducible local and production deployments  
- Designed with a focus on:
  - security-by-default
  - horizontal scalability
  - fault isolation
  - and operational monitoring

This project is actively used in production and serves as a real-world backend systems testbed.

---

### Umineko City of Books – Social Platform for the *When They Cry* Community  
Repository: https://github.com/VictoriqueMoe/umineko_city_of_books

- Full-fledged social networking platform for fans of the *When They Cry* visual novel series (theory debates, game board, mysteries, galleries, fanfiction, chat rooms, DMs, and more)  
- Backend in **Go (Fiber v3)** backed by **SQLite** (pure-Go, no CGO), frontend in **React 19 + TypeScript**, served as a single binary embedding the Vite bundle  
- Real-time everything over a single in-process **WebSocket hub**: live notifications, chat, presence, reactions, and like/view counters with exponential-backoff reconnect and ETag polling fallback  
- Background **media pipeline** with a worker pool for image-to-WebP and video-to-MP4 encoding off the request hot path  
- **Permission-based authorization** layer, server-side sessions with httpOnly cookies, and a pluggable content-filter pipeline on all user-generated text  
- Live at [meta.auaurora.moe](https://meta.auaurora.moe)

---

### Umineko Quote Finder – Full-Text Quote Search Engine  
Repository: https://github.com/VictoriqueMoe/umineko_quote_finder

- Search engine over thousands of dialogue lines across three visual novels (Umineko, Higurashi, Ciconia), with filtering by character, episode/arc/chapter, and truth type  
- **Go (Fiber v3)** backend with a hand-written **lexer → parser → AST → transformer** pipeline for parsing the game scripts, plus a generic store for shared search/browse/random logic  
- Custom **ONS2 format decoder** (XOR substitution cipher + zlib), data embedded at compile time via `go:embed`, and on-the-fly **Open Graph image generation** for shareable quotes  
- **React 19 + TypeScript** frontend with inline audio playback and a voice-clip builder for composing custom dialogue sequences  
- Containerized with **Docker** and shipped via GitHub Actions; live at [quotes.auaurora.moe](https://quotes.auaurora.moe)

---

### ONScripter-RU WASM – Visual Novel Engine in the Browser  
Repository: https://github.com/VictoriqueMoe/onscripter-ru-wasm

- WebAssembly fork of the **C++** ONScripter-RU visual novel engine, cross-compiled to run entirely in the browser via **Emscripten**  
- Replaces multithreaded subsystems (media demux/decode, subtitle rendering, async dispatch) with **single-threaded synchronous** equivalents to fit the browser execution model and WASM memory limits  
- Rewires native synchronous **file I/O to fetch assets over HTTP** on demand, and persists save data to the browser's **IndexedDB** via IDBFS  
- Adapts the graphics and audio pipelines to **WebGL** and the **Web Audio API**, with all changes gated behind compile flags so native builds stay untouched  
- Powers a full PS3-build *Umineko no Naku Koro ni* running in a single browser tab  

*(More projects are available in the pinned repositories section on the profile.)*

---

## GitHub Overview (Text-Focused, Recruiter-Friendly)

- Active contributor to personal and open-source projects  
- Experience working across **multi-repo**, **multi-service** environments  
- Comfortable reading, refactoring, and extending existing codebases in Java, Go, and Node  
- Regular use of GitHub workflows, pull requests, and code review practices  

---

## Contact

- GitHub: [@VictoriqueMoe](https://github.com/VictoriqueMoe)  
- Website: [waifuvault.moe](https://waifuvault.moe)  

---

<div align="center">

  <br/>

  <img src="https://komarev.com/ghpvc/?username=VictoriqueMoe&label=Profile%20Views&color=ff69b4&style=for-the-badge" />

  <br/><br/>

  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/victoriqueMoe/victoriqueMoe/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/victoriqueMoe/victoriqueMoe/output/github-contribution-grid-snake.svg">
    <img alt="GitHub contribution grid snake animation" src="https://raw.githubusercontent.com/victoriqueMoe/victoriqueMoe/output/github-contribution-grid-snake.svg">
  </picture>

  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:3a1c71,50:d76d77,100:ffaf7b&height=100&section=footer" width="100%"/>

</div>
