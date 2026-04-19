# Software Requirements Specification (SRS) Ringkas — FishPoint

## 1. Pendahuluan

### 1.1 Tujuan Dokumen
Dokumen ini bertujuan untuk mendefinisikan spesifikasi kebutuhan perangkat lunak bagi sistem FishPoint. Dokumen ini akan menjadi acuan teknis bagi tim pengembang dalam proses implementasi dan pengujian sistem.

### 1.2 Ruang Lingkup
FishPoint adalah platform berbasis web dan mobile untuk berbagi informasi lokasi memancing secara terpusat. Ruang lingkup sistem mencakup manajemen akun pengguna (Member & Admin), pengelolaan data spot mancing, sistem ulasan (rating & review), serta fitur moderasi konten.

### 1.3 Definisi dan Akronim
- **SRS**: *Software Requirements Specification*
- **FR**: *Functional Requirement* (Kebutuhan Fungsional)
- **NFR**: *Non-Functional Requirement* (Kebutuhan Non-Fungsional)
- **MVP**: *Minimum Viable Product*
- **US**: *User Story*

## 2. Deskripsi Umum

### 2.1 Perspektif Produk

### 2.2 Fungsi Produk

### 2.3 Karakteristik Pengguna
1. **Guest**: Pengguna tanpa akun yang hanya bisa melihat data publik.
2. **Member**: Pengguna terdaftar yang memiliki hak akses untuk berkontribusi.
3. **Admin**: Pengelola sistem dengan otoritas penuh atas validitas konten.

### 2.4 Batasan

## 3. Kebutuhan Fungsional

| ID | Deskripsi Fungsi | Prioritas | Ref: US |
| :--- | :--- | :--- | :--- |
| **FR-01** | Sistem menampilkan daftar spot mancing di halaman utama. | High | US-01 |
| **FR-02** | Sistem menyajikan detail lengkap spot termasuk peta dan galeri foto. | High | US-02 |
| **FR-03** | Sistem menyediakan formulir pendaftaran akun Member baru. | High | US-03 |
| **FR-04** | Sistem melakukan otentikasi Member melalui login username & password. | High | US-04 |
| **FR-05** | Sistem memfasilitasi Member untuk mengunggah data spot mancing baru. | High | US-05 |
| **FR-06** | Sistem memproses input rating dan ulasan teks dari Member. | High | US-06 |
| **FR-07** | Sistem mengizinkan Member untuk memperbarui data spot miliknya. | Medium | US-07 |
| **FR-08** | Sistem memberikan akses Admin untuk menghapus spot yang melanggar. | High | US-08 |
| **FR-09** | Sistem memungkinkan Admin menghapus review/gambar yang tidak pantas. | Medium | US-09 |
| **FR-10** | Sistem menyediakan fungsi penonaktifan akun Member oleh Admin. | Medium | US-10 |

## 4. Kebutuhan Non-Fungsional

## 5. Catatan dan Asumsi
- Asumsi: Pengguna memiliki akses ke GPS atau layanan lokasi agar fitur koordinat spot berfungsi akurat.
- Dependensi: Sistem bergantung pada API peta pihak ketiga untuk visualisasi lokasi.
- Batasan Teknis: Foto yang diunggah oleh Member dibatasi maksimal 2MB per file untuk menjaga performa muat halaman.