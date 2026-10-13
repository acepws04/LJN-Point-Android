LJN POINT ANDROID - PEMBUATAN APK TANPA ANDROID STUDIO

Aplikasi Android berbasis WebView untuk membuka:
http://www.ljnpoint.online

CARA BUILD DARI HP ANDROID MENGGUNAKAN GITHUB ACTIONS
1. Ekstrak ZIP ini di HP.
2. Buat repository GitHub baru bernama LJN-Point-Android.
3. Upload seluruh ISI folder LJN_Point_Android_WebView ke repository (bukan folder pembungkusnya).
4. Pastikan file .github/workflows/build-apk.yml ikut ter-upload. Jika menu Upload Files tidak menampilkan folder .github, buat workflow tersebut melalui tab Actions atau gunakan GitHub Desktop/website dengan Add file.
5. Buka tab Actions di repository.
6. Pilih workflow "Build LJN Point APK" lalu tekan Run workflow.
7. Tunggu sampai workflow selesai dengan tanda hijau.
8. Buka hasil run, cari bagian Artifacts, lalu unduh "LJN-Point-APK".
9. Ekstrak ZIP artifact dan pasang app-debug.apk di HP. Jika diminta, izinkan pemasangan dari sumber ini.

CATATAN
- Aplikasi hanya membungkus website; data login dan poin tetap dikelola website.
- Memerlukan internet.
- Jika website memiliki sertifikat HTTPS bermasalah, perbaiki SSL situs terlebih dahulu. Aplikasi tidak melewati error sertifikat.
- Upload foto di halaman website didukung melalui pemilih file Android.
- APK hasil workflow adalah debug APK untuk pengujian. Untuk publikasi Play Store diperlukan signing/release build.
