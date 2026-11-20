# Dokumen Perangkat Ajar Guru (Terpisah dari Konten PID)

**Topik:** Fundamental Basis Data Relasional  
**Satuan Pendidikan:** SMK Antartika 1 Sidoarjo  
**Program / Konsentrasi Keahlian:** PPLG / RPL  
**Media:** Konten Interaktif Papan Interaktif Digital (PID) — 9 Halaman (16:9)  
**URL Produksi:** https://pid-fundamental-basis-data-ant1.vercel.app/

---

## 1. Capaian Pembelajaran (CP)

Pada akhir fase F, peserta didik mampu memahami, merancang, dan mengimplementasikan basis data relasional (struktur tabel, tipe data, relasi antartabel, aturan integritas, serta operasi manipulasi data dasar CRUD/SQL) sebagai fondasi pengembangan perangkat lunak yang terstruktur dan akurat.

## 2. Tujuan Pembelajaran (TP)

Setelah mengikuti pembelajaran interaktif menggunakan media PID ini, peserta didik diharapkan mampu:

1. **Mengidentifikasi & Menganalisis** struktur fundamental basis data relasional (*Database, Tabel, Kolom, Baris, Tipe Data, Primary Key, Foreign Key, dan Constraint*).
2. **Membandingkan** dampak penumpukan data pada satu tabel tunggal (redundansi & inkonsistensi) dengan solusi normalisasi dua tabel berelasi (*One-to-Many / 1:N*).
3. **Merakit** skema tabel `barang` dengan pemilihan tipe data dan constraint integritas (`PRIMARY KEY`, `FOREIGN KEY`, `NOT NULL`, `CHECK >= 0`) secara tepat.
4. **Mensimulasikan** operasi manipulasi data dasar (**CRUD**: `INSERT`, `SELECT`, `UPDATE`, `DELETE`) serta membuktikan fungsi validasi integritas data saat terjadi pelanggaran.
5. **Mengevaluasi** studi kasus nyata kesalahan pengelolaan data dan menyusun catatan rencana perancangan basis data untuk proyek aplikasi berikutnya.

---

## 3. Pemetaan Pengalaman Pembelajaran (9 Halaman PID)

| Pengalaman Belajar | Prinsip Pembelajaran | Halaman di Konten PID | Aktivitas Kelas di PID |
|---|---|---|---|
| **Pendahuluan & Pemantik** | Berkesadaran & Bermakna | **Halaman 1** (*Topik Hari Ini*) & **Halaman 2** (*Studi Kasus*) | Membahas agenda belajar (*"Apa yang Akan Kita Pelajari Saat Ini?"*), diskusi pertanyaan pemantik dengan Timer 2 Menit, dan simulasi interaktif 3 Kasir Serentak (dengan kontrol Jeda & +1 Langkah). |
| **Memahami** | Bermakna & Menggembirakan | **Halaman 3** (*Anatomi Tabel*), **Halaman 4** (*Masalah 1 Tabel*), & **Halaman 5** (*Relasi PK & FK*) | Bedah anatomi tabel `barang` secara sentuh, simulasi pindah rak pada tabel redundan (ekspos typo), lalu membandingkan dengan relasi 2 tabel (`kategori` → `barang`) + preview SQL `INNER JOIN`. |
| **Mengaplikasi** | Bermakna & Menggembirakan | **Halaman 6** (*Rakit Skema*) & **Halaman 7** (*Lab Maya SQL*) | Gim edukasi merakit tipe data & constraint (Drag-and-Drop / Ketuk) hingga menghasilkan SQL `CREATE TABLE`, dilanjutkan praktik langsung CRUD & 4 uji pelanggaran (PK ganda, NULL, CHECK negatif, Foreign Key). |
| **Evaluasi & Merefleksi** | Berkesadaran & Metakognitif | **Halaman 8** (*Kuis Kasus*) & **Halaman 9** (*Ringkasan*) | Penyelesaian 5 studi kasus *Detektif Basis Data* + Mode Bahas Kelas bersama guru, dilanjutkan pengisian skala pemahaman diri (1–4), catatan singkat, dan ekspor ringkasan (`.txt` / PDF). |

---

## 4. Kriteria Ketercapaian Tujuan Pembelajaran (KKTP)

- **86 – 100 (Sangat Baik):** Sudah mencapai TP; siap diberi tantangan lanjutan merancang ERD multi-tabel (misal menambahkan tabel `transaksi` & `detail_transaksi`).
- **70 – 85 (Baik):** Sudah mencapai TP; disarankan memperdalam ketelitian pada aturan `CHECK`, `FOREIGN KEY`, dan klausa `WHERE` pada `UPDATE`/`DELETE`.
- **< 70 (Perlu Pendampingan):** Ulangi eksplorasi Halaman 3–7 secara terbimbing lalu ulangi kuis pada Halaman 8.
