NILLAN AUDIO PRO EQ — PROYEK ANDROID AWAL

Fitur versi ini:
- Pemutar file audio lokal melalui pemilih file Android.
- Equalizer perangkat (hingga 10 slider antarmuka; jumlah band efek nyata bergantung pada perangkat Android).
- Bass Boost dan Loudness Enhancer jika efek didukung perangkat.
- Workflow GitHub Actions untuk membangun APK debug.

BATASAN PENTING:
Aplikasi ini memproses audio yang diputar di dalam aplikasi. Android biasa tidak mengizinkan aplikasi ini menerapkan EQ secara global ke audio Brave yang diputar aplikasi lain. Jadi versi ini BELUM memproses langsung audio Brave. Untuk jalur Brave -> EQ -> V8, diperlukan dukungan sistem/root atau perubahan sumber audio agar diputar dari aplikasi ini.

Build:
1. Upload ZIP ini ke root repositori GitHub.
2. Pastikan workflow ada di .github/workflows/build-apk.yml.
3. Buka tab Actions/Tindakan, pilih workflow, lalu jalankan.
4. Jika berhasil, unduh Artifact NILLAN-AUDIO-PRO-EQ-debug-apk.
