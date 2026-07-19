<p align="center">
  <img src="https://waxum.imtaqin.id/img/logo.png" alt="IMTAQIN.ID" width="120" />
</p>

<h1 align="center">IMTAQIN.ID</h1>

<p align="center">
  Small, native, fast tools.<br/>
  From Jakarta, for engineers who don't want a 200 MB runtime for a 20-line problem.
</p>

<p align="center">
  <a href="https://imtaqin.id">imtaqin.id</a>
  &nbsp;·&nbsp;
  <a href="https://waxum.imtaqin.id">waxum.imtaqin.id</a>
  &nbsp;·&nbsp;
  <a href="https://maublast.net">maublast.net</a>
  &nbsp;·&nbsp;
  <a href="mailto:taqin2731@gmail.com">taqin2731@gmail.com</a>
</p>

---

### Halo. Hi.

Kami membangun tools yang **kecil, native, cepat** — biasanya di Rust, kadang di Go / TypeScript / C# / PHP kalau memang cocok. Fokus utama saat ini adalah **WhatsApp gateway ecosystem** (protocol translation, VoIP, multi-session ops) dan **workflow automation** untuk operator SMB Indonesia.

We build **small, native, fast** tools — usually in Rust, occasionally in Go / TypeScript / C# / PHP when the shape fits. Current focus: **WhatsApp gateway ecosystem** (protocol translation, VoIP, multi-session ops) and **workflow automation** for Indonesian SMB operators.

---

### ▸ Featured

<table>
<tr>
<td width="50%" valign="top">

**[waxum](https://github.com/imtaqin/waxum)** &nbsp;·&nbsp; Rust &nbsp;·&nbsp; ★ 39+

Multi-session REST API gateway for the WhatsApp Web protocol. Single binary, native MLOW voice codec, browser console + playground, Postgres/MySQL/SQLite. The first production-grade REST layer over `whatsapp-rust`.

`docker pull fdciabdul/waxum`

</td>
<td width="50%" valign="top">

**[waxum-doc](https://github.com/imtaqin/waxum-doc)** &nbsp;·&nbsp; TypeScript

Documentation site at [waxum.imtaqin.id](https://waxum.imtaqin.id) — API reference, deployment, webhooks, VoIP calls, media plane. Docusaurus + offline search.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[MAUBLAST](https://maublast.net)** &nbsp;·&nbsp; Product

Production WhatsApp blast + workflow platform built on top of waxum. Owns the user model, session ownership, per-user quota — the *"thin app in front of the gateway"* pattern in production. Indonesian for now.

</td>
<td width="50%" valign="top">

**[goampp](https://github.com/imtaqin/goampp)** &nbsp;·&nbsp; Go

Native Windows control panel for Apache, MySQL, PHP, Node.js, Python, Go, and 10+ runtimes. Like XAMPP, but faster and lighter. No system tray daemon.

</td>
</tr>
</table>

---

### ▸ Also in the workshop

- **Scrapers + data pipelines** — [Property-API](https://github.com/imtaqin/Property-API) (Mamikos / OLX / Lamudi / Rumah123), [Bank-Capital](https://github.com/imtaqin/Bank-Capital), [MUTASIKU](https://github.com/imtaqin/MUTASIKU), [OLX-SCRAPER](https://github.com/imtaqin/OLX-SCRAPER), [scrapeads](https://github.com/imtaqin/scrapeads)
- **Growth / SMM tooling** — [Youtube-Auto-Uploader](https://github.com/imtaqin/Youtube-Auto-Uploader), [Quora-Video-Generator](https://github.com/imtaqin/Quora-Video-Generator), [YOMEN](https://github.com/imtaqin/YOMEN), [Orbis-Web-Traffic-Generator](https://github.com/imtaqin/Orbis-Web-Traffic-Generator)
- **Utilities** — [CloudfFlare-Tunnel-GUI](https://github.com/imtaqin/CloudfFlare-Tunnel-GUI), [Cloudflare-IP-Updater](https://github.com/imtaqin/Cloudflare-IP-Updater), [LOGS-FINDER](https://github.com/imtaqin/LOGS-FINDER), [NODEPACKER](https://github.com/imtaqin/NODEPACKER)
- **Native / edu** — [ABSENSI-SISWA-DIGITAL](https://github.com/imtaqin/ABSENSI-SISWA-DIGITAL) (fingerprint + face biometrics), [docui](https://github.com/imtaqin/docui) (TUI docker client)

---

### ▸ Stack we ship in

<p>
  <img alt="Rust" src="https://img.shields.io/badge/-Rust-000?style=for-the-badge&logo=rust&logoColor=orange" />
  <img alt="TypeScript" src="https://img.shields.io/badge/-TypeScript-000?style=for-the-badge&logo=typescript" />
  <img alt="Go" src="https://img.shields.io/badge/-Go-000?style=for-the-badge&logo=go" />
  <img alt="Node.js" src="https://img.shields.io/badge/-Node.js-000?style=for-the-badge&logo=node.js" />
  <img alt="C#" src="https://img.shields.io/badge/-C%23-000?style=for-the-badge&logo=csharp" />
  <img alt="PHP" src="https://img.shields.io/badge/-PHP-000?style=for-the-badge&logo=php&logoColor=%23777BB4" />
</p>

<p>
  <img alt="Axum" src="https://img.shields.io/badge/-Axum-000?style=flat-square" />
  <img alt="Tokio" src="https://img.shields.io/badge/-Tokio-000?style=flat-square" />
  <img alt="Postgres" src="https://img.shields.io/badge/-Postgres-000?style=flat-square&logo=postgresql" />
  <img alt="SQLite" src="https://img.shields.io/badge/-SQLite-000?style=flat-square&logo=sqlite" />
  <img alt="Redis" src="https://img.shields.io/badge/-Redis-000?style=flat-square&logo=redis" />
  <img alt="Docker" src="https://img.shields.io/badge/-Docker-000?style=flat-square&logo=docker" />
  <img alt="Cloudflare" src="https://img.shields.io/badge/-Cloudflare-000?style=flat-square&logo=cloudflare" />
  <img alt="NATS" src="https://img.shields.io/badge/-NATS-000?style=flat-square&logo=natsdotio" />
</p>

---

### ▸ How we work

- **Native over abstraction** — a 20 MB Rust binary beats a 400 MB Node runtime for the same job, especially when it will run on a 1-vCPU VPS.
- **REST first, protocol underneath** — expose a boring REST surface, do the ugly protocol work behind it.
- **Docs are shipped code** — API reference lives at [waxum.imtaqin.id](https://waxum.imtaqin.id), CHANGELOG is the source of truth for behaviour, no "TODO: document this later".
- **Multi-tenancy is an app concern, not a gateway concern** — waxum is a gateway; the user model lives in the app that fronts it. See [issue #44](https://github.com/imtaqin/waxum/issues/44) for the rationale.

---

<p align="center">
  <sub>© IMTAQIN.ID &nbsp;·&nbsp; Jakarta, Indonesia &nbsp;·&nbsp; Native tools, small footprints.</sub>
</p>
