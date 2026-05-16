# Sistem Pakar Diagnosis TBC Tulang Belakang - Metode Forward Chaining
## Studi Kasus: Puskesmas Warung Jambu

[![N|Solid](https://img.shields.io/badge/PHP-7.4-blue.svg)](https://php.net)
[![N|Solid](https://img.shields.io/badge/MySQL-RDBMS-orange.svg)](https://mysql.com)

[cite_start]Sistem pakar ini merupakan aplikasi berbasis web yang dirancang untuk membantu tenaga medis dalam melakukan diagnosis awal penyakit TBC Tulang Belakang secara sistematis[cite: 43, 67]. [cite_start]Menggunakan metode **Forward Chaining**, sistem ini melakukan penalaran dari sekumpulan fakta (gejala) menuju sebuah kesimpulan diagnosis[cite: 66, 74].

## 🛠 Fitur Utama
- [cite_start]**Diagnosis Otomatis**: Mengolah 32 jenis gejala untuk mengidentifikasi 6 jenis penyakit tulang belakang[cite: 96, 97].
- [cite_start]**Mesin Inferensi**: Implementasi algoritma Forward Chaining untuk penelusuran aturan (IF-THEN)[cite: 75, 107].
- [cite_start]**Perhitungan Akurasi**: Menggunakan rumus Probabilitas Klasik untuk menentukan tingkat keyakinan hasil diagnosis[cite: 81, 88].
- [cite_start]**Laporan Digital**: Menghasilkan rekapitulasi hasil diagnosis pasien beserta rekomendasi tindakan medis dari pakar[cite: 134, 138].

## 🧪 Metodologi Sistem
[cite_start]Sistem ini memetakan gejala-gejala klinis berdasarkan basis pengetahuan yang divalidasi oleh pakar[cite: 44, 103].

### Daftar Penyakit yang Terdeteksi:
1. [cite_start]**P1**: TBC Tulang Belakang[cite: 100].
2. [cite_start]**P2**: Spondilitis Degeneratif[cite: 100].
3. [cite_start]**P3**: Osteomielitis Non-TBC[cite: 100].
4. [cite_start]**P4**: Tumor Tulang Belakang[cite: 100].
5. [cite_start]**P5**: Hernia Nukleus Pulposus (HNP)[cite: 100].
6. [cite_start]**P6**: Spondilitis Ankylosing[cite: 100].

## 💻 Spesifikasi Teknologi
Aplikasi ini dibangun dengan menggunakan *stack* teknologi berikut:
- [cite_start]**Bahasa Pemrograman**: PHP[cite: 68, 92].
- [cite_start]**Database**: MySQL[cite: 68, 92].
- [cite_start]**Frontend**: HTML, CSS, JavaScript[cite: 92].

## 📂 Struktur Database
Sistem menggunakan basis data untuk mengelola informasi berikut:
- [cite_start]`data_users`: Informasi identitas pasien[cite: 134, 135].
- [cite_start]`data_gejala`: Daftar 32 indikator medis[cite: 102, 134].
- [cite_start]`data_penyakit`: Katalog penyakit tulang belakang[cite: 100, 134].
- [cite_start]`data_solusi`: Rekomendasi penanganan medis (S1-S6)[cite: 108, 134].

---
> [cite_start]**Disclaimer**: Sistem ini berfungsi sebagai alat skrining awal (*early screening*) dan bukan merupakan pengganti diagnosis medis formal dari dokter spesialis atau pemeriksaan laboratorium[cite: 145].

**Dikembangkan oleh:**
**Faisal Akbar**
[cite_start]*Teknik Informatika - Universitas Indraprasta PGRI* [cite: 36, 37]