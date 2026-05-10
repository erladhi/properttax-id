# Panduan Aplikasi Properttax ID

Panduan ini dibuat berdasarkan file HTML aplikasi kalkulator pajak properti yang diupload. 
Aplikasi ini digunakan untuk membantu menghitung estimasi pajak transaksi properti di Indonesia seperti jual beli, hibah, dan waris. 

---

# 1. Gambaran Umum

Aplikasi bernama:
**Properttax ID – Kalkulator Pajak Properti Indonesia**

Fitur utama aplikasi:
* Kalkulator Pajak Jual Beli Properti
* Kalkulator Pajak Hibah
* Kalkulator Pajak Waris
* Mode Tampilan Terang/Gelap (Light/Dark Mode)
* Responsive untuk Desktop & Mobile
* Riwayat Perhitungan
* Detail perhitungan pajak

---

# 2. Tampilan Utama

Saat aplikasi dibuka, pengguna akan melihat beberapa bagian utama:

## A. Sidebar Menu

Menu di sisi kiri digunakan untuk berpindah fitur:

| Menu             | Fungsi                               |
| ---------------- | ------------------------------------ |
| Jual Beli        | Menghitung pajak transaksi jual beli |
| Pajak Hibah      | Menghitung pajak hibah properti      |
| Pajak Waris      | Menghitung pajak warisan             |
| Tentang Aplikasi | Informasi aplikasi                   |

---

## B. Header Atas

Bagian atas menampilkan:

* Nama modul aktif
* Tombol menu mobile
* Tombol ganti tema terang/gelap

---

## C. Area Form Input

Digunakan untuk mengisi data transaksi properti seperti:

* Jenis properti
* Harga transaksi
* Status penjual
* Status pembeli
* NJOP
* Tanggal transaksi

---

## D. Area Hasil Perhitungan

Menampilkan hasil kalkulasi:

* PPh
* PPN
* BPHTB
* Total pajak
* Detail perhitungan

---

# 3. Cara Menggunakan Modul Jual Beli

## Langkah 1 — Pilih Menu “Jual Beli”

Klik menu:

**🤝 Jual Beli**

---

## Langkah 2 — Isi Informasi Properti

Pilih jenis properti:
* Rumah Subsidi (FLPP)
* Rumah Komersial
* Tanah

---

## Langkah 3 — Pilih Status Penjual

Pilihan:
* Developer / PKP
* Orang Pribadi (OP)
* Badan Usaha

Fungsi:
Menentukan tarif PPh yang berlaku.

---

## Langkah 4 — Pilih Status Pembeli

Pilihan:
* Orang Pribadi
* Badan Usaha

Fungsi:
Mempengaruhi insentif PPN.

---

## Langkah 5 — Isi Tanggal Transaksi

Tanggal digunakan untuk menentukan tarif PPN:

* Sebelum 2025 → PPN 11%
* Mulai 2025 → PPN 12%

---

## Langkah 6 — Isi Nilai Properti

Masukkan:
* Harga transaksi
* NJOP
* NPOPTKP (jika tersedia)

Format input menggunakan mata uang Rupiah.

---

## Langkah 7 — Klik Tombol Hitung

Sistem akan otomatis menghitung:

| Jenis Pajak | Keterangan                                |
| ----------- | ----------------------------------------- |
| PPh         | Pajak Penghasilan                         |
| PPN         | Pajak Pertambahan Nilai                   |
| BPHTB       | Bea Perolehan Hak atas Tanah dan Bangunan |
| Total       | Total keseluruhan pajak                   |

---

## Langkah 8 — Lihat Detail Perhitungan

Klik bagian hasil pajak untuk membuka detail:
* Dasar hukum
* Rumus perhitungan
* Langkah kalkulasi

---

# 4. Cara Menggunakan Modul Hibah

## Langkah Penggunaan

1. Klik menu:
   **🎁 Pajak Hibah**

2. Isi data:

   * Nilai properti
   * Hubungan keluarga
   * NJOP
   * Lokasi

3. Klik:
   **Hitung Pajak**

Sistem akan menentukan:

* Apakah hibah bebas pajak
* Apakah terkena BPHTB
* Estimasi pajak hibah

---

# 5. Cara Menggunakan Modul Waris

## Langkah Penggunaan

1. Klik menu:
   **📜 Pajak Waris**

2. Isi data warisan:
   * Nilai aset
   * NJOP
   * Hubungan ahli waris

3. Klik:
   **Hitung**

Hasil akan menampilkan:

* BPHTB waris
* Potensi pembebasan pajak
* Total biaya

---

# 6. Mode Terang & Gelap

Aplikasi mendukung dua tampilan:

| Mode   | Fungsi                        |
| ------ | ----------------------------- |
| Terang | Tampilan standar              |
| Gelap  | Tampilan nyaman di malam hari |

Cara mengganti:

* Klik tombol tema di sidebar
* Atau klik ikon tema di mobile

---

# 7. Penggunaan di Mobile

Aplikasi sudah responsive untuk HP/tablet.

Fitur mobile:
* Hamburger menu
* Sidebar slide
* Tampilan form otomatis 1 kolom
* Tombol full width

---

# 8. Informasi Hasil Pajak

Setiap hasil pajak memiliki indikator warna:

| Warna  | Arti        |
| ------ | ----------- |
| Merah  | PPh         |
| Biru   | PPN         |
| Hijau  | BPHTB       |
| Kuning | Total Pajak |

---

# 9. Fitur Tambahan

## A. Tooltip Bantuan

Ikon ℹ️ akan menampilkan penjelasan tambahan ketika diarahkan mouse.

---

## B. Toast Notification

Aplikasi menampilkan notifikasi otomatis untuk:

* Berhasil menghitung
* Menyalin hasil
* Kesalahan input

---

## C. Riwayat Perhitungan

Riwayat transaksi akan tersimpan sementara di aplikasi.

---

# 10. Tips Penggunaan

## Disarankan:

✅ Isi nilai transaksi sesuai AJB/NJOP
✅ Pastikan tanggal transaksi benar
✅ Gunakan NJOP terbaru
✅ Cek detail perhitungan sebelum finalisasi

---

# 11. Catatan Penting

Aplikasi ini bersifat:
* Simulasi / estimasi
* Bukan pengganti konsultasi resmi
* Tetap perlu verifikasi ke:
  * Notaris/PPAT
  * Kantor Pajak
  * Bapenda daerah

---

# 12. Kesimpulan

Properttax ID adalah aplikasi kalkulator pajak properti modern yang membantu pengguna menghitung estimasi pajak transaksi properti secara cepat dan mudah, baik melalui desktop maupun perangkat mobile.

Fitur unggulan:
* Interface modern
* Responsive mobile
* Multi-modul pajak
* Dark mode
* Detail kalkulasi lengkap
* Mudah digunakan oleh pengguna umum maupun profesional properti

