# State Management Codelabs

## Ephemeral State Management
- **Metode**: Menggunakan StatefulWidget dan `setState`.
- **Cakupan**: State hanya tersedia untuk widget tertentu (lokal).
- **Kelebihan**:
  - Mudah diimplementasikan.
  - Cocok untuk widget sederhana.
- **Kekurangan**:
  - Sulit diatur jika state diperlukan di banyak widget.
- **Sering Digunakan**
- Digunakan dengan StatefulWidget.
- State lokal untuk widget tertentu.
- Cocok untuk elemen interaktif kecil.

## App State Management
- **Metode**: Menggunakan Scoped Model untuk state global.
- **Cakupan**: State tersedia di seluruh aplikasi.
- **Kelebihan**:
  - Mudah berbagi state di berbagai widget.
  - Cocok untuk aplikasi besar seperti autentikasi atau keranjang belanja.
- **Kekurangan**:
  - Membutuhkan lebih banyak konfigurasi.
- **Sering Digunakan**
- Digunakan dengan Scoped Model. 
- State global untuk seluruh aplikasi.
- Cocok untuk manajemen aplikasi kompleks.

## Cara Menjalankan
1. Clone repositori ini.
2. Jalankan proyek "ephemeral_state_codelab" untuk Ephemeral State Management:
   ```bash
   cd ephemeral_state_codelab
   flutter run
