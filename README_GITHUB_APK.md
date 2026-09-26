# Werkudara Betta — GitHub → APK

Project ini sudah dilengkapi GitHub Actions untuk membuat APK otomatis di cloud.

## Cara pakai

1. Buat repository baru di GitHub, misalnya `WerkudaraBetta`.
2. Upload **seluruh isi folder project ini** ke repository.
3. Commit ke branch `main` atau `master`.
4. Buka tab **Actions** di repository.
5. Pilih workflow **Build Werkudara Betta APK**.
6. Klik **Run workflow** jika build belum otomatis berjalan.
7. Setelah selesai, buka hasil run tersebut.
8. Di bagian **Artifacts**, download `WerkudaraBetta-debug-apk`.
9. Extract ZIP artifact, lalu ambil file `.apk` untuk dipasang di HP Android.

Workflow juga otomatis berjalan setiap kali ada push ke `main`/`master`.

Catatan:
- Ini menghasilkan **debug APK** untuk testing/pemasangan pribadi.
- Untuk Play Store nanti perlu build **release AAB/APK** dengan signing key.
- Project memakai Android SDK 35 dan JDK 17 sesuai konfigurasi workflow.
