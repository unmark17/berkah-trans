# Berkah Trans Indonesia — Website (Static)

Website landing page modern (1 file) untuk layanan **Sewa Mobil Elf** (Pariwisata, City Tour/Ziarah, Antar Jemput) dan **Rombongan Haji/Umrah**.

## Cara Pakai (paling gampang)
1. Buka folder ini.
2. Klik dua kali `index.html` → otomatis terbuka di browser.

## Upload ke Hosting
Karena ini **static website**, tinggal upload isi folder ini ke:
- cPanel (public_html)
- Netlify
- Cloudflare Pages
- Vercel (static)

## Yang perlu diganti (penting)
Di bagian paling bawah `index.html`, cari:
```js
const WHATSAPP_NUMBER = '6281234567890';
```
Ganti dengan nomor WA admin (format internasional, tanpa +, tanpa 0 di depan).
Contoh: `0811-3216-2221` → `6281132162221`

Lalu update:
- Alamat garasi/kantor
- Area layanan
- Daftar armada dan paket harga (jika ingin ditampilkan)

## Assets
- `assets/logo.jpg` → logo dari Anda
- `assets/favicon.png` → ikon tab

---
Dibuat untuk kebutuhan branding & promosi Berkah Trans Indonesia.
