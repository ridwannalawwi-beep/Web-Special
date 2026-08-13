# Project: 365 Days With You

Undangan web anniversary 1 tahun, static HTML/CSS/JS (tanpa build tool). Dibuat untuk Rahma Septiani.

## Fakta kunci (jangan diubah tanpa diminta)

- Tanggal: **29 Agustus 2026, 16:00 WIB** (countdown di index.html pakai `2026-08-29T16:00:00`)
- Lokasi: **Kota Bandung**, dresscode: **Dresswell**
- Halaman: `index.html` (amplop → hero + video + surat + konfirmasi) → `confirm.html` (form RSVP)
- Musik: `membasuh.mp3` (index), `who.mp3` (confirm)
- RSVP: Google Apps Script `https://script.google.com/macros/s/AKfycbykF4iQn_8QoNKNNK-Oe10sQHbmjMeMTXdBUKpNzQ_nt958R9yHFNK0z7l8U3wk9YI0dw/exec` + redirect `wa.me/6282115295634`
- Nada bahasa: romantis, hangat, bahasa Indonesia campur Inggris

## Tema & style (WAJIB diikuti semua perubahan)

Vibe: **dark luxury anniversary** — elegan, misterius, mewah, bukan kartu ucapan lucu.

- **Warna**: background `#0c0b0a` (ink), emas `#d4a84b` (gold), `--gold-soft: #f0dfb0`, `--gold-line: rgba(212,168,75,0.25)`, teks `#e8e4dc` / soft `#a8a090` / muted `#7a7260`
- **Font**: `Cinzel` (judul/serif) + `Outfit`/`DM Sans` (body, weight 300)
- **Elemen khas**: glass card (`backdrop-filter: blur(20px)`), grain overlay (SVG noise), partikel emas naik, ornament garis+diamond, animasi shimmerText, reveal on scroll, gold glow shadow
- **Mood**: redup, cinematic, emas menyala di gelap; hindari warna terang lain, hindari emoji berlebihan di halaman utama
- **Konsistensi antar halaman**: 2 halaman harus pakai :root vars yang sama. Jika ubah satu variabel, sinkronkan ke halaman lain.
- Copywriting: singkat, puitis, titik-titik "....." sebagai ciri khas

## Aturan kerja

- Tanpa framework/library eksternal — vanilla HTML/CSS/JS, inline style + script per file
- Fitur baru harus sesuai tema (gold/dark/glass), bukan gaya default browser
- Jika menambah halaman baru, ikuti struktur index.html (envelope/entrance, ornament, reveal)