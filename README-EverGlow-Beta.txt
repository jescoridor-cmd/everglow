EVERGLOW SMP — WEBSITE BETA

File utama: index-everglow-beta.html

CARA MENCOBA
1. Buka file HTML ini di browser modern.
2. Website dapat dijalankan sebagai prototipe statis tanpa instalasi.
3. Untuk GitHub Pages, unggah file ini ke repository GitHub sementara dan ubah namanya menjadi index.html.

FITUR YANG SUDAH ADA DI PROTOTIPE
- Tampilan responsif dengan tema hitam, glassmorphism, dan aksen emas.
- Navigasi Bahasa Indonesia.
- Informasi alamat Java dan Bedrock.
- Ringkasan fitur server.
- Enam kartu rank dan harga.
- Custom Tag, upgrade rank, tautan Discord dan Ticket.
- Formulir simulasi permintaan pendaftaran dengan username/IGN.
- Pengumuman Beta.

PENTING — BELUM SIAP PRODUKSI
Ini adalah frontend/prototipe statis. Form pendaftaran hanya simulasi browser; tidak membuat akun, tidak menyimpan password, dan tidak mengirim permintaan ke Admin. Jangan masukkan password sungguhan. Sebelum dipublikasikan untuk pengguna, wajib dibuat backend dengan:
- autentikasi aman dan penyimpanan password Argon2id/bcrypt;
- pencocokan username website dengan IGN Minecraft;
- status akun pending/approved/rejected dan panel persetujuan Admin;
- role Admin/Member yang diperiksa di server, bukan hanya tampilan;
- database member, pesanan, produk, pengumuman, dan audit log;
- sesi aman, rate limiting, validasi input, dan perlindungan CSRF;
- integrasi webhook/Discord serta integrasi Minecraft di tahap berikutnya.

KONFIGURASI YANG PERLU DICEK SEBELUM RILIS
- Alamat Java: evglow.my.id.
- Alamat Bedrock alternatif: eglow.my.di atau eglow.mcindo.my.id, port 23379. Kedua alamat ditampilkan sesuai instruksi pengguna; pastikan host yang aktif sebelum publikasi.
- Integrasi status server dan pemberian rank otomatis belum tersedia.
- Pembayaran bukan otomatis dianggap lunas; Admin tetap harus memverifikasi bukti melalui Ticket.
- Tidak ada token, password, webhook secret, atau kredensial panel di dalam file.
