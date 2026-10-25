# Rama — rmjz

Saya membangun dan mengoperasikan sistem yang mengubah pekerjaan manual berulang jadi proses otomatis: **CRM, pelaporan, dan web** yang dipakai harian oleh orang yang bukan teknisi.

Lumajang, Jawa Timur — bekerja remote untuk klien seluruh Indonesia.

[rmjz.my.id](https://rmjz.my.id) · [Telegram](https://t.me/ramajz) · [LinkedIn](https://linkedin.com/in/rmjz)

---

## Yang sudah berjalan

Bukan mockup, bukan repo contoh. Tiga sistem produksi yang saya bangun sendiri dari kode sampai server.

| Sistem | Apa itu | Status |
| --- | --- | --- |
| **[KulinerLumajang](https://kulinerlumajang.id)** | Direktori & storefront UMKM. Warung punya halaman sendiri, pesanan masuk ke WhatsApp penjual dalam format rapi, tanpa potongan komisi. | Live |
| **[CRM-Utapes](https://crm.rmjz.my.id)** | CRM follow-up tim CS. Memantau ribuan lead per bulan dan mengirim rekap otomatis tiap pagi ke Telegram. | Live |
| **[rmjz.my.id](https://rmjz.my.id)** | Katalog produk digital & portofolio. Etalase, halaman layanan, dan pelacakan pengunjung — dikelola tanpa developer. | Live |

## Repo yang bisa dilihat

- **[crm-utapes](https://github.com/ramajz/crm-utapes)** — Laravel + Livewire + PostgreSQL (NeonDB). Lead management, dashboard kohort bulanan, webhook.
- **[crm-followup-audit](https://github.com/ramajz/crm-followup-audit)** — Python. Cron harian: tarik data Google Sheets via Apps Script, hitung status follow-up per CS, kirim rekap ke Telegram.
- **[rrfamily22_bot](https://github.com/ramajz/rrfamily22_bot)** — Node.js di Cloudflare Workers + Hono + D1. Bot keuangan: input bahasa natural, konfirmasi tombol, laporan budget otomatis.
- **[kulinerlumajang-id](https://github.com/ramajz/kulinerlumajang-id)** — struktur proyek & aturan kerja KulinerLumajang.

## Stack

**Bahasa** — PHP, Python, JavaScript, TypeScript, SQL

**Backend** — Laravel, Livewire, Hono, Node.js, REST API

**Frontend** — Astro, Alpine.js, Tailwind CSS, Blade

**Infrastruktur** — Docker, Coolify, Cloudflare Workers / D1 / R2, VPS Linux, Nginx, PostgreSQL, SQLite

**Otomasi** — cron & scheduler, Google Apps Script, Telegram Bot API, WhatsApp API, n8n

## Cara saya bekerja

1. **Audit 30 menit** — lihat alur kerja yang sekarang, cari tiga pemborosan terbesar.
2. **Rancangan 3 hari** — ruang lingkup, alur, dan harga tertulis. Setuju dulu, baru mulai.
3. **Bangun & uji** — bertahap, progres terlihat tiap minggu.
4. **Serah terima** — server atas nama klien, data milik klien, damping 30 hari.

Prinsip yang saya pegang: **jangan menambah aplikasi baru kalau masalahnya bisa diselesaikan dengan menghapus pekerjaan manual.** Guard keamanan dan validasi ditaruh di kode, bukan di prompt.

---

Butuh sistem yang berhenti dikerjakan manual? Mulai dari audit — gratis, tanpa komitmen.

**[Hubungi saya](https://rmjz.my.id)** · [Telegram](https://t.me/ramajz)
