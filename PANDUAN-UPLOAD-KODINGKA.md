# Panduan Pengisian Formulir Upload Interactive App — Portal Guru SMART PID (Kodingka)

Panduan ini disusun khusus untuk mengunggah aplikasi **Fundamental Basis Data Relasional** (SMK Antartika 1 Sidoarjo) ke laman **Portal Guru SMART PID (`kodingka.id/model_pid/guru/upload_app.php`)**.

Semua isian di bawah sudah diselaraskan dengan isi 9 halaman aplikasi `index.html`, format batas karakter Kodingka (`maks. 700 karakter` pada kolom Pembelajaran Mendalam), serta syarat file unggahan.

---

## Langkah 01 — Model Pemanfaatan PID

- **Model PID \*:**  
  **Rekomendasi Utama:** `Simulasi dan Eksplorasi Digital`  
  *(Alasan: Aplikasi ini berfokus pada eksplorasi bedah anatomi tabel secara sentuh, simulasi 3 kasir serentak dengan tombol jeda/langkah, uji pindah rak redundansi vs relasi PK–FK, gim rakit skema, dan Lab Maya SQL CRUD secara langsung.)*
  > **Catatan:** Jika Administrator membuka Gallery resmi kelas Anda pada model lain (misalnya `Presentasi Interaktif` atau `Gamifikasi Pembelajaran`), pilih Model PID yang sesuai dengan Gallery resmi dari Administrator.

---

## Langkah 02 — Gallery / Kelas Resmi

- **Gallery \*:**  
  Pilih paket **Gallery / Kelas Resmi** berstatus *Publish* yang telah disediakan oleh Administrator sesuai jenjang SMK / kelompok workshop Anda.

---

## Langkah 03 — Identitas Aplikasi

Silakan salin isian berikut ke formulir:

- **Nama Aplikasi \*:**
  ```text
  Fundamental Basis Data Relasional — Simulasi & Lab Maya SQL
  ```
- **Jenjang Aplikasi \*:**  
  Centang **`SMK`** *(opsional: boleh tambahkan `SMA` jika ingin dipakai juga untuk mapel Informatika)*
- **Mata Pelajaran \*:**
  ```text
  Basis Data (PPLG / RPL)
  ```
- **Tags:**
  ```text
  basis data, sql, crud, primary key, foreign key, simulasi, smk pplg, rpl, interaktif
  ```
- **Versi:**
  ```text
  1.0
  ```

---

## Langkah 04 — Pembelajaran Mendalam

> **Perhatian:** Setiap kolom teks pada Kodingka memiliki batas maksimal **700 karakter**. Teks di bawah sudah dihitung agar **pas, padat, konkret, terukur, dan aman di bawah 700 karakter** (siap *copy-paste* langsung).

### 01. MEMAHAMI \* *(585 / 700 karakter)*
```text
Peserta didik memahami mengapa aplikasi modern membutuhkan basis data terpusat melalui studi kasus kasir minimarket dan simulasi 3 kasir serentak (berkontrol jeda dan per langkah). Selanjutnya peserta didik membedah anatomi basis data relasional (Database, Tabel, Kolom, Baris, Primary Key, Tipe Data, dan Constraint) secara interaktif dengan mengetuk elemen tabel barang. Peserta didik juga membandingkan risiko penumpukan data pada 1 tabel (redundansi dan typo saat uji pindah rak) dengan solusi normalisasi 2 tabel berelasi One-to-Many (PK ke FK) beserta pratinjau query INNER JOIN.
```

### 02. MENGAPLIKASI \* *(569 / 700 karakter)*
```text
Peserta didik menerapkan konsep struktur tabel dan integritas data pada halaman Tantangan Arsitek Data: Rakit Skema Tabel barang (drag-and-drop atau ketuk-pasang untuk layar sentuh PID) guna menentukan Tipe Data dan Constraint (PRIMARY KEY, FOREIGN KEY, NOT NULL, CHECK >= 0) hingga menghasilkan sintaks SQL CREATE TABLE yang valid. Berikutnya peserta didik langsung mempraktikkan 4 misi operasi CRUD (INSERT, SELECT, UPDATE stok kasir, DELETE) serta menguji 4 skenario pelanggaran integritas (PK ganda, NULL, angka minus, dan FK tidak valid) di Lab Maya SQL real-time.
```

### 03. MEREFLEKSI \* *(499 / 700 karakter)*
```text
Peserta didik mengevaluasi penguasaannya melalui 5 studi kasus Detektif Basis Data dengan umpan balik instan serta Mode Bahas Kelas untuk mengulas kesalahan umum (seperti DELETE tanpa klausa WHERE) bersama guru di PID. Pada halaman Ringkasan, peserta didik meninjau rekap otomatis seluruh capaian aktivitas (Anatomi, Rakit Skema, Lab SQL, dan Kuis), memilih tingkat pemahaman diri (skala 1-4), menuliskan konsep bermakna dan rencana proyek basis data berikutnya, lalu mengekspornya ke .txt atau PDF.
```

### Prinsip Pembelajaran Mendalam \*
Centang **ketiganya**:
- [x] **Bermakna** — Mengangkat kasus nyata sistem minimarket, validasi stok gudang, dan rencana proyek RPL.
- [x] **Berkesadaran** — Dilengkapi agenda belajar jelas, timer diskusi 2 menit, kuis diagnostik, dan rekap progres + skala pemahaman diri 1–4.
- [x] **Menggembirakan** — Tampilan 16:9 tanpa scroll bergaya Neo-Brutalist, simulasi interaktif 3 kasir, gim rakit skema, dan efek suara offline.

### Karakteristik / Dimensi Tambahan SMART PID *(jika muncul di bawahnya)*
Centang seluruh yang sesuai:
- [x] **AKTIF** — Siswa langsung merakit skema, mencoba query SQL, dan mengetes skenario error.
- [x] **INTERAKTIF** — 9 halaman 16:9 ramah sentuh PID tanpa scroll vertikal dengan umpan balik instan.
- [x] **ADAPTIF** — 16:9 optimal untuk PID sekaligus responsif di smartphone, ditambah tombol Jeda & +1 Langkah sesuai tempo kelas.
- [x] **KOLABORATIF** — Timer diskusi kelas 2 menit, Mode Bahas Kelas (5 pembahasan serentak), dan catatan refleksi kelompok.
- [x] **INKLUSIF** — Panel aksesibilitas melayang di pojok kiri bawah (Skala Teks 85%–135%, mode Cerah/Gelap/Kontras Tinggi WCAG AAA, Spasi Baca ramah disleksia, dan Text-to-Speech Bahasa Indonesia).
- [x] **BERMAKNA** — Berbasis studi kasus nyata minimarket yang relevan dengan dunia kerja PPLG/RPL.

---

## Langkah 05 — File Aplikasi

### 1. Thumbnail \* *(JPG, PNG, WEBP — maks. 2 MB)*
- Pilih file: **`assets/og-preview.png`**
- Spesifikasi: PNG `1200×630` (proporsi landscape rapi), ukuran hanya **±74 KB** (jauh di bawah batas 2 MB), sudah menampilkan logo kolaborasi **Kemendikdasmen | SMK Antartika 1 Sidoarjo**, judul modul, dan cuplikan tabel + SQL.

### 2. Interactive App \* *(HTML/HTM atau ZIP dengan index.html — maks. 20 MB)*
- **WAJIB pilih file `.zip` (JANGAN hanya upload `index.html` sendirian!)**
- Pilih file yang sudah disiapkan: **`paket-kodingka-fundamental-basis-data.zip`**
- Ukuran: **±1,25 MB** (sangat ringan, jauh di bawah batas 20 MB).

#### Kenapa wajib `.zip` dan bukan `.html` saja?
Karena `index.html` membutuhkan 7 aset lokal di dalam folder `assets/` (logo Kemendikdasmen, logo SMK Antartika 1, 3 diagram SVG, dan favicon). Jika hanya mengunggah `index.html`, gambar dan logo tidak akan muncul.

#### Struktur isi `paket-kodingka-fundamental-basis-data.zip` (Sudah Bersih & Sesuai Syarat Kodingka):
```text
paket-kodingka-fundamental-basis-data.zip
├── index.html                  <-- Langsung di root ZIP (tanpa folder pembungkus tambahan!)
└── assets/
    ├── favicon.svg
    ├── gambar-1-manual-vs-db.svg
    ├── gambar-2-anatomi-tabel.svg
    ├── gambar-3-relasi-erd.svg
    ├── LOGO-ANTARTIKA.png
    ├── logo-kemindikdasmen.png
    └── og-preview.png
```
*(Folder `.git`, `.gemini`, `.impeccable`, dan dokumen guru sengaja **tidak** dimasukkan ke dalam ZIP agar paket bersih, aman, dan 100% langsung berjalan di server Kodingka.)*

---

## Checklist Sebelum Klik **"Kirim untuk Review"**

1. [ ] Pastikan `Model PID` dan `Gallery` sesuai arahan panitia/Administrator.
2. [ ] Pastikan `Thumbnail` memakai `assets/og-preview.png`.
3. [ ] Pastikan `Interactive App` memakai `paket-kodingka-fundamental-basis-data.zip`.
4. [ ] Jika nanti Anda mengubah `index.html` lagi di masa depan, buat ulang file `.zip` dengan memilih **`index.html` + folder `assets/` bersama-sama** lalu klik kanan → *Compress to ZIP* (jangan menge-zip folder luarnya).
5. [ ] Dokumen guru terpisah tersedia di `PERANGKAT-AJAR-CP-TP.md` apabila panitia meminta lampiran CP/TP terpisah, dan versi live web tersedia di: `https://pid-fundamental-basis-data-ant1.vercel.app/`.
