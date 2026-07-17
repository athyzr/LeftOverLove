# LeftOverLove

LeftOverLove adalah aplikasi Android berbasis Kotlin dan Jetpack Compose yang ditujukan untuk membantu mengurangi pemborosan makanan melalui fitur donasi, pemesanan, serta interaksi antara pengguna dan restoran.

## Fitur Utama

- Splash screen saat aplikasi dimulai
- Login dan registrasi pengguna
- Halaman beranda untuk melihat restoran dan makanan
- Detail makanan dan detail restoran
- Fitur donasi makanan
- Halaman aktivitas, donasi, dan favorit pengguna
- Profil pengguna beserta opsi edit profil

## Teknologi yang Digunakan

- Kotlin
- Jetpack Compose
- Navigation Compose
- Material 3
- Firebase Authentication
- Firebase Realtime Database
- Firebase Firestore
- Gradle Kotlin DSL

## Prasyarat

Sebelum menjalankan proyek, pastikan Anda telah menginstal:

- Android Studio
- JDK 11
- Android SDK dengan API level yang sesuai
- Emulator atau perangkat Android yang terhubung

## Cara Menjalankan

1. Clone repository ini.
2. Buka project di Android Studio.
3. Tunggu proses sync Gradle selesai.
4. Pilih emulator/perangkat Android.
5. Jalankan project dengan salah satu perintah berikut:

### Windows
```bash
gradlew.bat assembleDebug
```

### Linux/macOS
```bash
./gradlew assembleDebug
```

Alternatif lain, jalankan langsung dari Android Studio dengan tombol Run.

## Struktur Project

- app/src/main/java: kode utama aplikasi
- app/src/main/res: resource seperti drawable, layout, string, dan tema
- app/google-services.json: konfigurasi Firebase untuk aplikasi

## Catatan Firebase

Project ini telah dilengkapi dengan file Firebase config di [app/google-services.json](app/google-services.json). Pastikan Anda menggunakan project Firebase yang sesuai agar fitur autentikasi dan database dapat berjalan dengan benar.

## Lisensi

Proyek ini dibuat untuk kebutuhan pengembangan aplikasi Android dan dapat dikembangkan lebih lanjut sesuai kebutuhan tim.
