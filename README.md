<div align="center">

# Ditzzx Tools

**A personal collection of web tools — built clean, deployed fast.**

[![Live](https://img.shields.io/badge/status-live-4ade80?style=flat-square&labelColor=0a0a0a)](https://ditzzx.my.id)
[![Vercel](https://img.shields.io/badge/deployed_on-vercel-ffffff?style=flat-square&labelColor=0a0a0a)](https://vercel.com)
[![Made with Claude](https://img.shields.io/badge/coded_by-Claude_AI-D97757?style=flat-square&labelColor=0a0a0a)](https://claude.ai)

</div>

---

## Overview

**ditzzx.my.id** adalah personal website milik Ditzzx — sebuah koleksi tools yang dibuat dengan filosofi sederhana: *kalau bisa diotomasi, otomasi aja.*

Semua dibuat dari nol. No framework besar. Hanya HTML, CSS, Vanilla JS di frontend, dan Vercel Serverless Functions di backend.

---

## Tools

### 01 — Downloader
Download konten dari berbagai platform media sosial hanya dengan paste URL.

| Platform | Support |
|---|---|
| YouTube | Video (multi-quality) + Audio (MP3) |
| Instagram | Foto & Video |
| TikTok | Video |
| Twitter / X | Video & Media |
| Others | Facebook, Reddit, dan platform lainnya |

**Fitur:**
- Tab per platform dengan auto-detect URL
- Quality selector untuk YouTube (360p, 720p, 1080p, dst)
- Audio-only mode (MP3) untuk YouTube
- Progress indicator real-time

---

### 02 — Generator
Generate konten visual secara instan langsung dari browser.

| Tab | Deskripsi |
|---|---|
| **Brat Image** | Generate brat-style image dengan custom teks & blur level |
| **Sticker Meme** | Upload foto + tambah caption atas & bawah dengan font Impact/Anton |
| **iPhone Chat** | Buat screenshot percakapan iPhone yang realistis |
| **Carbon Code** | Generate code screenshot estetik via Carbon |
| **Ustadz Meme** | Generate meme dengan template foto ustadz + auto word wrap & font InterMedium |
| **Brat Anime** | Generate brat-style image dengan background anime + font Poppins Bold, pure client-side |
| **Bang Jago** | Generate fake Bank Jago screenshot dengan nama & nominal saldo custom |

**Catatan:** Semua tab Generator berjalan pure client-side (Canvas API) — tidak ada request ke backend.

---

### 03 — Image Tools
Pengolah gambar bertenaga AI langsung dari browser.

| Fitur | Deskripsi |
|---|---|
| **HD Upscale** | Perbesar resolusi gambar 2x atau 4x dengan AI |
| **Remove Background** | Hapus background gambar secara otomatis |
| **Watermark Remover** | Hapus watermark dari gambar |
| **AI Image Editor** | Edit gambar dengan perintah teks berbasis AI |

---

### 04 — Deployer
Deploy website HTML ke Vercel dalam hitungan detik — tanpa akun, tanpa setup.

**Fitur:**
- Upload file HTML via drag & drop
- Custom subdomain `.vercel.app`
- Quota harian 50 deploy dengan cooldown 5 menit per deploy
- Auto-delete project terlama saat mencapai limit 180 project
- Persistent quota & cooldown tracking via Upstash Redis

---

## Tech Stack

```
Frontend      → HTML · CSS · Vanilla JavaScript
Backend       → Vercel Serverless Functions
Canvas API    → Sticker Meme, Ustadz Meme, Brat Anime, Bang Jago (pure client-side, no backend)
Database      → Upstash Redis (quota & cooldown tracking)
Fonts         → Syne · DM Mono · Anton · Inter Medium · Poppins Bold (Google Fonts + jsDelivr + GitHub Raw)
Hosting       → Vercel
Analytics     → Vercel Analytics
```

---

## Pages

```
/index.html        → Homepage + About + Tools listing
/downloader.html   → Multi-platform media downloader
/generator.html    → Visual content generator
/image-tools.html  → AI-powered image processing
/deployer.html     → Instant HTML deployer to Vercel
/developer.html    → Credits & colophon
```

---

## Team

| | Name | Role |
|---|---|---|
| 👤 | **Ditzzx** | Publisher & Owner — ide, arah, dan semua keputusan product |
| 🤖 | **Claude** (Anthropic) | AI Code Writer — semua HTML, CSS, JS, dan serverless functions |

---

## Philosophy

> *"Dua entitas, satu tujuan — bikin tools yang berguna dan keren."*

Website ini bukan dibuat untuk terlihat sibuk. Setiap tool ada karena ada kebutuhan nyata, dan setiap baris kode ditulis dengan tujuan yang jelas.

---

<div align="center">

**© 2026 Ditzzx** · [ditzzx.my.id](https://ditzzx.my.id) · *Precision in every pixel*

</div>
