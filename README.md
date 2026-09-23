[![Sponsor](https://img.shields.io/badge/Sponsor-%E2%9D%A4-ea4aaa?logo=github-sponsors)](https://github.com/sponsors/MattJackson)

### Hi, I'm Matthew 👋

Systems & infrastructure engineer — I write low-level software in **Rust, C/C++, and Go**:
virtualization, storage, protocol implementations, and firmware tooling. I like making
things run where they're not supposed to, and shipping single-binary tools that just work.

🏢 I work on **[GetBusbar](https://github.com/GetBusbar/busbar)**, and contribute across a
few orgs and open-source projects including **[FreeMKV](https://github.com/freemkv)** and
**[tiberius-rs](https://github.com/tiberius-rs)**.

---

#### 🦀 Rust systems & protocol code
- **[tiberius-ng](https://github.com/MattJackson/tiberius-ng)** — actively-maintained TDS 7.2–8.0 (Microsoft SQL Server) driver for Rust.
- **[oauth-as](https://github.com/MattJackson/oauth-as)** — embeddable OAuth 2.1 Authorization Server library, incl. the RFC 8628 device grant.
- **[lsi-flash](https://github.com/MattJackson/lsi-flash)** — single-binary Linux CLI for cross-flashing LSI SAS2008 HBAs (Dell H200/H310, IBM M1015) between IT/IR firmware.
- **[thumb-asm](https://github.com/MattJackson/thumb-asm)** — ARM Thumb/Thumb-2 decoder, disassembler, assembler and detour installer in pure safe Rust; decodes and re-encodes the instruction set against Arm's own architecture reference manuals, relocates instructions, and installs trampolines over live code in a firmware image. Zero dependencies, `forbid(unsafe_code)`.
- **[firmware-extractor](https://github.com/MattJackson/firmware-extractor)** — any firmware download → one raw firmware `.bin` + JSON label; signature-based, deterministic, offline.
- **[usagio](https://github.com/MattJackson/usagio)** — juggle multiple Claude/Codex logins, see usage across every AI coding CLI, auto-swap before you hit the wall. macOS menu bar.
- **[muri](https://github.com/MattJackson/muri)** — a themeable, custom-drawn menu + tray crate for Rust (a drop-in alternative to muda/tray-icon). One consistent look on every OS, with true flush-right alignment and embedded logos. macOS usable today; Windows/Linux in progress.

#### 🏗️ Infrastructure & homelab
- **[basement](https://github.com/MattJackson/basement)** — multi-backend storage control plane + S3 gateway.
- **[host-agent](https://github.com/MattJackson/host-agent)** — adaptive Dell PowerEdge fan controller + Prometheus exporters + vmagent in one drop-in container.

#### 🖥️ Running macOS where it isn't supposed to run
A full stack for booting macOS guests on non-Apple hosts.
- **[libapplegfx-vulkan](https://github.com/MattJackson/libapplegfx-vulkan)** — Linux implementation of Apple's ParavirtualizedGraphics framework, accelerated via Vulkan/lavapipe.
- **[mos-docker](https://github.com/MattJackson/mos-docker)** — macOS in Docker: QEMU + OpenCore, built from source, zero third-party runtime deps.
- **[mos-qemu](https://github.com/MattJackson/mos-qemu)** · **[mos-opencore](https://github.com/MattJackson/mos-opencore)** · **[mos-patcher](https://github.com/MattJackson/mos-patcher)** — QEMU/OpenCore patches and a Lilu-style kernel-hook framework for macOS 15 VMs.

#### 🔧 Supporting
- **[lsi-flash-firmware](https://github.com/MattJackson/lsi-flash-firmware)** — community mirror of LSI SAS2008 firmware for `lsi-flash`.
- **[homebrew-tap](https://github.com/MattJackson/homebrew-tap)** — Homebrew tap for my tools (`brew install MattJackson/tap/...`).

---

<sub>📫 matthew@pq.io</sub>
