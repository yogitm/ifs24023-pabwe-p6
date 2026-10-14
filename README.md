# Praktikum 6 - Pemrograman Aplikasi Berbasis Web (PABWE) 2026

Repositori ini memuat pengerjaan tugas Praktikum 6 (Framework JavaScript: Svelte & SvelteKit) untuk mahasiswa IT Del (NIM: `12S24023`).

## 📁 Sub-Proyek Praktikum 6

| No | Modul / Studi Kasus | Framework & Bahasa | Repositori GitHub | Live Production URL |
|---|---|---|---|---|
| 1 | **SK 1: Delcom Link Tree** | Svelte 5 (JavaScript) + Vite | [ifs24023-pabwe2026-sk-p6-svelte](https://github.com/yogitm/ifs24023-pabwe2026-sk-p6-svelte) | [https://ifs24023-pabwe2026-sk-p6-svelte.yogitrim.my.id](https://ifs24023-pabwe2026-sk-p6-svelte.yogitrim.my.id) |
| 2 | **SK 2: Delcom Courses** | SvelteKit (TypeScript) + Svelte 5 | [ifs24023-pabwe2026-sk-p6-sveltekit](https://github.com/yogitm/ifs24023-pabwe2026-sk-p6-sveltekit) | [https://ifs24023-pabwe2026-sk-p6-sveltekit.yogitrim.my.id](https://ifs24023-pabwe2026-sk-p6-sveltekit.yogitrim.my.id) |

## 🧪 Kualitas Kode & Hasil Pengujian
Kedua studi kasus telah memenuhi seluruh spesifikasi pengujian dengan **100% Code Coverage**:
- **Statements**: 100%
- **Branches**: 100%
- **Functions**: 100%
- **Lines**: 100%

## 🖥️ Infrastruktur & Deployment
- **Hosting**: Private Home Server (`100.76.214.88`)
  - SK 1: Docker Container (`ifs24023-svelte-web`) reverse proxied via Nginx di port `8090`
  - SK 2: Bun runtime via Systemd Service (`ifs24023-sveltekit.service`) di port `8089`
- **Tunneling**: Cloudflare Tunnel (`cloudflared-prak6`) dengan SSL aktif.
