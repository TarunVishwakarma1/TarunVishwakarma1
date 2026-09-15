<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&duration=3200&pause=900&color=E6EDF3&center=true&vCenter=true&width=520&lines=Tarun+Vishwakarma;Rust+%2B+Go+systems+engineer;ORMs%2C+TUIs+and+bare-metal+firmware">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&duration=3200&pause=900&color=1F2328&center=true&vCenter=true&width=520&lines=Tarun+Vishwakarma;Rust+%2B+Go+systems+engineer;ORMs%2C+TUIs+and+bare-metal+firmware" alt="Tarun Vishwakarma — Rust + Go systems engineer">
</picture>

<p>
  <em>I build the layer underneath — database drivers, terminal tools, firmware.<br>
  If it compiles to a single binary, I'm probably interested.</em>
</p>

<a href="https://tarunvishwakarma.dev"><img src="https://img.shields.io/badge/Portfolio-tarunvishwakarma.dev-0D1117?style=for-the-badge&logo=vercel&logoColor=white"></a>
<a href="https://www.linkedin.com/in/tarunvishwakarma28/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
<a href="https://leetcode.com/u/tarunvishwakarma/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black"></a>
<a href="https://x.com/Assassingod5"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white"></a>
<a href="mailto:tarunvishwakarma81@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"></a>

</div>

---

## `$ ls ~/shipped`

Things that are published, installable, and used by people who aren't me.

### 🦀 [rusticx](https://crates.io/crates/rusticx) — async-first ORM for Rust

[![crates.io](https://img.shields.io/crates/v/rusticx?style=flat-square&logo=rust&color=B7410E)](https://crates.io/crates/rusticx)
[![downloads](https://img.shields.io/crates/d/rusticx?style=flat-square&color=success)](https://crates.io/crates/rusticx)
[![docs.rs](https://img.shields.io/docsrs/rusticx?style=flat-square)](https://docs.rs/rusticx)
[![stars](https://img.shields.io/github/stars/TarunVishwakarma1/rustix-orm?style=flat-square&color=yellow)](https://github.com/TarunVishwakarma1/rustix-orm)

Define your models as plain structs, derive the rest. PostgreSQL, MySQL, SQLite and MongoDB behind one async API, with automatic schema generation and typed CRUD.

```toml
rusticx = "1.0"
```
[repo](https://github.com/TarunVishwakarma1/rusticx-orm) · [docs](https://docs.rs/rusticx) · [site](https://github.com/TarunVishwakarma1/rusticx-web)

### 📡 [netspd](https://github.com/TarunVishwakarma1/netspd) — network speed test with a hypercar tachometer

[![crates.io](https://img.shields.io/crates/v/netspd?style=flat-square&logo=rust&color=B7410E)](https://crates.io/crates/netspd)
[![downloads](https://img.shields.io/crates/d/netspd?style=flat-square&color=success)](https://crates.io/crates/netspd)
[![CI](https://img.shields.io/github/actions/workflow/status/TarunVishwakarma1/netspd/ci.yml?style=flat-square&label=ci)](https://github.com/TarunVishwakarma1/netspd/actions)

A Ratatui speed test that grades **bufferbloat** while the link is saturated — the number Ookla's CLI won't show you. Spring-physics needle, four providers, client *and* server in one binary, Prometheus output for the cron-job crowd.

```sh
brew install TarunVishwakarma1/tap/netspd   # or: cargo install netspd
```
Also ships as Nix, `.deb`, `.rpm` and prebuilt binaries.

<details>
<summary>▶ &nbsp;<b>Watch it run</b> &nbsp;<sub>(6 MB gif)</sub></summary>
<br>
<img src="https://raw.githubusercontent.com/TarunVishwakarma1/netspd/main/assets/recording.gif" alt="netspd running a speed test with an animated tachometer dial" width="820">
</details>

### 🐹 [gormicx](https://github.com/TarunVishwakarma1/gormicx) — the Go counterpart

One ORM surface across SQL and NoSQL, written in Go. → [gormicx.tarunvishwakarma.dev](https://gormicx.tarunvishwakarma.dev)

---

## `$ ps aux`

**🏷️ [TrueLabel](https://github.com/TarunVishwakarma1/true-lable)** — open-source barcode scanner backed by a crowdsourced, community-verified nutrition database. On-device OCR fills the gaps, peer verification keeps it honest. Built natively on every platform it runs on:

| | Repo | Stack |
|---|---|---|
| ⚙️ | [true-label-backend](https://github.com/TarunVishwakarma1/true-label-backend) | Rust · Axum · Tokio |
| 🌐 | [true-lable](https://github.com/TarunVishwakarma1/true-lable) | TypeScript · Turborepo |
| 🤖 | [true-label-android](https://github.com/TarunVishwakarma1/true-label-android) | Kotlin |
| 🍎 | [true-label-ios](https://github.com/TarunVishwakarma1/true-label-ios) | Swift · SwiftUI |

**📟 [ai-gated-spatial-radar-rs](https://github.com/TarunVishwakarma1/ai-gated-spatial-radar-rs)** — bare-metal Rust on an ESP32-S3: servo-swept ultrasonic ranging, live ILI9488 display, intrusion detection that keeps working with the network unplugged. Sibling: [esp-vending-machine](https://github.com/TarunVishwakarma1/esp-vending-machine).

---

## `$ ls ~/workshop`

<table>
<tr>
<td width="50%">

**[gotorrent](https://github.com/TarunVishwakarma1/gotorrent)** · Go<br>
BitTorrent client from the wire protocol up.

**[ims](https://github.com/TarunVishwakarma1/ims)** · Go<br>
Inventory system split into real services — [api](https://github.com/TarunVishwakarma1/ims-api), [db util](https://github.com/TarunVishwakarma1/ims-database-util), [messaging](https://github.com/TarunVishwakarma1/ims-messag-util), [web](https://github.com/TarunVishwakarma1/ims-web-app).

</td>
<td width="50%">

**[WLink Key Generator](https://w-link-key-generator.vercel.app)** · TS<br>
Client-side key encryption for Solana and Ethereum wallets — keys never leave the browser.

**[Dynamic Dashboard](https://dashboard-app-mu-drab.vercel.app)** · TS<br>
Configurable charting dashboard with auth baked in.

</td>
</tr>
</table>

---

## `$ cat stack.txt`

<div align="center">

[![My Skills](https://skillicons.dev/icons?i=rust,go,ts,swift,kotlin,java,nextjs,tauri,postgres,mongodb,docker,aws&theme=dark)](https://skillicons.dev)

<sub>Also: Axum · Tokio · Ratatui · embassy/esp-hal · Turborepo · Solana</sub>

</div>

---

## `$ git log --stat`

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=TarunVishwakarma1&theme=github-dark-blue&hide_border=true&date_format=M%20j%5B%2C%20Y%5D">
  <img src="https://streak-stats.demolab.com?user=TarunVishwakarma1&theme=default&hide_border=true&date_format=M%20j%5B%2C%20Y%5D" alt="GitHub streak" height="180">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=TarunVishwakarma1&theme=github_dark_dimmed">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=TarunVishwakarma1&theme=default" alt="Repos per language" height="180">
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=TarunVishwakarma1&theme=github_dark_dimmed">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=TarunVishwakarma1&theme=default" alt="Most commit language" height="180">
</picture>

</div>

---

<div align="center">

**Building something that needs a database layer, a TUI, or firmware?**<br>
[tarunvishwakarma.dev](https://tarunvishwakarma.dev) · [tarunvishwakarma81@gmail.com](mailto:tarunvishwakarma81@gmail.com)

</div>
