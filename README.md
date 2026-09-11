# 26-577148-TK-65636_Muhammad-Rehan-Syarif-Daniel_MagangGMRTDay3
# Laporan Tugas Simulasi Robotik: State Machine & Redundansi Sensor

## 1. Link Simulasi Tinkercad
* [Klik untuk Buka Simulasi Tinkercad](https://www.tinkercad.com/things/hSuQ8OhGRwz/editel)

## 2. Dokumentasi & Video Demonstrasi
* **Video Demo**: [Buka Video Demonstrasi](https://drive.google.com/file/d/1f7XQGv6r_fecHlF5JHwztpEGW2V2ziNx/view?usp=sharing)

## 3. Penjelasan Fitur Teknis
* **Emergency Unlatch State**: Menggunakan interupsi Hardware (Pin 2) untuk mengunci seluruh kontrol navigasi hingga tombol 'A' ditekan kembali.
* **Visualisasi NeoPixel (8 LED)**: Menampilkan tingkat kecepatan secara proporsional dan warna arah pergerakan (Maju/Mundur).
* **Fault Detection Algorithm**: Memantau pulsa encoder saat motor aktif (`PWM > 0`). Jika pulsa tidak terdeteksi dalam durasi tertentu, mode otomatis beralih ke *Open-Loop Fallback* berbasis nilai PWM.
