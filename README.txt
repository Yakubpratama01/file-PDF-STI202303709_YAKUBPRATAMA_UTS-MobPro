# Personal Journal - UTS Mobile Programming

**Nama:** ILHAM ANDI SENTANA  
**NIM:** STI202303345

## Deskripsi
Aplikasi sederhana untuk mencatat kegiatan harian (judul, deskripsi, tanggal, waktu, foto).
Data disimpan secara lokal menggunakan File I/O (path_provider).

## Struktur
- lib/
  - main.dart
  - models/journal.dart
  - pages/
    - home_page.dart
    - add_journal_page.dart
    - gallery_page.dart
    - detail_page.dart
  - utils/
    - file_storage.dart
- pubspec.yaml

## Cara menjalankan
1. Pastikan Flutter SDK sudah terinstal dan Android Studio / emulator siap.
2. Buat project Flutter baru (contoh): `flutter create personal_journal`
3. Hapus isi folder `lib` pada project baru, lalu salin seluruh folder `lib` dari repo ini ke project.
4. Ganti `pubspec.yaml` pada project baru dengan file `pubspec.yaml` dari folder ini, atau tambahkan dependency:
   - image_picker
   - path_provider
   lalu jalankan `flutter pub get`.
5. Jalankan aplikasi: `flutter run` pada emulator atau perangkat.

## Catatan penting
- File gambar disimpan sebagai path file dari image_picker; permission dan pengaturan emulator mungkin diperlukan.
- Jika ingin menyertakan project penuh (android/ios), jalankan langkah pada bagian "Cara menjalankan" lalu replace `lib` + `pubspec.yaml`.

## Screenshot & PDF
Silakan jalankan di emulator dan ambil screenshot untuk melengkapi PDF tugas (format nama file: NIM_NAMA_UTS MobPro.pdf).