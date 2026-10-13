# ExxGoYT APK

1. Buat repo baru di GitHub, upload SEMUA isi folder ini (termasuk folder .github).
2. Tab Actions > "Build APK" > Run workflow.
3. Download artifact "ExxGoYT-APK" (app-debug.apk) dan install di HP.

Di Appwrite Console > Settings > Platforms, pastikan ada Web platform hostname: localhost

CATATAN: login Google/Yahoo/Facebook lewat WebView bisa ditolak (Google blokir login di dalam WebView),
dan embed player YouTube kadang error di origin localhost. Cek dua hal ini pas pertama dicoba.

LOGIN APK: di APK loginnya pakai email + OTP (dikirim otomatis Appwrite, kayak Switch Akun), bukan Google/Yahoo/Facebook.
Pastikan Email OTP aktif di Appwrite (Auth > Settings) dan email Appwrite jalan. Akun dibuat dulu lewat versi web.
