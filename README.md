# syam-apk-release

Repo rilis APK SYAM (BASE SYAM). Aplikasi cek versi terbaru dari sini
(`GET /releases/latest`), lalu unduh & pasang APK-nya langsung dari dalam app.

## Versi terbaru: v2.0.79 — WAJIB UPDATE

- Unduh APK: https://github.com/yaitata01-ux/syam-apk-release/releases/latest/download/app-release.apk
- Halaman rilis: https://github.com/yaitata01-ux/syam-apk-release/releases/latest
- Mirror MediaFire (folder paten, isinya selalu 1 APK terbaru): https://www.mediafire.com/folder/dcaoqpttmpkd0

APK dual-ABI (arm 32-bit + arm64), ~97 MB.

## Catatan rilis v2.0.79 (wajib)

- Tag Scam (menu baru di Tools Gateway): report scam langsung dari HP — pilih profil,
  kelola daftar akun yang dilaporkan, dialog saat di luar jam report (Tetap Kirim / Lewati Email),
  plus notifikasi jam report & hasil MT.
- Spam OTP: pengulangan (ronde) bisa diatur sendiri — preset 1x/2x/3x/5x/10x/25x atau isi manual
  sampai 999 ronde, progres menampilkan ronde ke berapa, dan bisa dihentikan di tengah.
- Pembaruan halaman tools: Vercel deploy & admin token, Web RAT inject payload,
  OSINT domain (subdomain, SOA, sertifikat SSL/TLS), Web HTML Aide, Spam Report WA, Upload ke URL.
- Profil & dashboard: kartu profil dengan telemetry perangkat real-time (baterai & kecepatan internet).

## Cara update

1. Buka aplikasi — popup update muncul otomatis (di login: WAJIB, tidak bisa di-skip;
   di halaman lain: tombol NANTI / UPDATE).
2. Tekan UPDATE → aplikasi mengunduh dan memasang APK-nya sendiri.
3. Manual: unduh dari link di atas, pasang seperti biasa.

## Catatan teknis

- Catatan rilis yang diawali `[FORCE]` / `[WAJIB]` membuat client menampilkan popup wajib
  dan memblokir pemakaian sampai user update.
- Asset rilis selalu bernama `app-release.apk` (client ambil dari asset pertama yang berakhiran `.apk`).
- Rilis sebelumnya: v2.0.78 — perbaikan AM Premium & 9router.
