# Mangrove Agent

## Tentang Proyek

**Mangrove Agent** adalah repository komprehensif yang mengumpulkan data, informasi, regulasi, dan dokumentasi teknis terkait perlindungan dan pengelolaan ekosistem mangrove di Indonesia. Repository ini dikembangkan dalam lingkup kewenangan Kementerian Lingkungan Hidup dan Kehutanan (KLHK) / Badan Perlindungan Lingkungan Hidup (BPLH) serta mengacu pada mandat regulasi nasional.

Proyek ini dirancang untuk mendukung implementasi Sistem Informasi Perlindungan dan Pengelolaan Ekosistem Mangrove (SIPM) yang mengintegrasikan data spasial, informasi ekologis, data sosial-ekonomi, dan fitur partisipasi masyarakat dalam satu platform digital terpadu.

## Daftar Isi

- [Tentang Proyek](#tentang-proyek)
- [Latar Belakang dan Konteks](#latar-belakang-dan-konteks)
- [Tujuan Proyek](#tujuan-proyek)
- [Struktur Repository](#struktur-repository)
- [Fitur Utama](#fitur-utama)
- [Dokumentasi](#dokumentasi)
- [Kontribusi](#kontribusi)
- [Lisensi dan Kontak](#lisensi-dan-kontak)

## Latar Belakang dan Konteks

### Pentingnya Ekosistem Mangrove

Ekosistem mangrove merupakan aset ekologis strategis yang memiliki fungsi penting:

- **Fungsi Ekologis:** Penyedia habitat bagi berbagai spesies flora dan fauna, termasuk ikan, krustasea, dan burung air
- **Fungsi Sosial-Ekonomi:** Sumber penghidupan bagi ribuan masyarakat melalui perikanan, tambak, pariwisata, dan produk hutan
- **Fungsi Perlindungan:** Pelindung pantai dari abrasi, badai, dan banjir rob serta penyimpan karbon biru (*blue carbon*)

### Mandat Regulasi

Perlindungan dan pengelolaan ekosistem mangrove diamanatkan melalui berbagai peraturan perundang-undangan:

- **Undang-Undang Lingkungan Hidup** – Menetapkan prinsip-prinsip dasar perlindungan lingkungan
- **Undang-Undang Kehutanan** – Mengatur klasifikasi, pemanfaatan, dan perlindungan hutan, termasuk mangrove
- **Peraturan Pemerintah Perlindungan dan Pengelolaan Ekosistem Mangrove** – Mengatur sistem informasi berbasis spasial, kriteria kerusakan, dan mekanisme pemulihan
- **Peraturan Menteri Lingkungan Hidup** – Mengoperasionalisasi kebijakan perlindungan mangrove di tingkat nasional, provinsi, dan kabupaten/kota

Peraturan ini mewajibkan setiap penyelenggara negara untuk:
- Mengelola inventarisasi mangrove menggunakan sistem informasi berbasis spasial
- Melakukan pemantauan kondisi mangrove secara berkala (minimal setiap 5 tahun)
- Menyimpan dokumen perencanaan perlindungan dan pengelolaan mangrove
- Memberdayakan masyarakat dalam perlindungan dan pengelolaan mangrove

## Tujuan Proyek

**Tujuan Umum:**
Menyediakan fondasi data, informasi, dan dokumentasi teknis yang komprehensif untuk mendukung implementasi Sistem Informasi Perlindungan dan Pengelolaan Ekosistem Mangrove yang berkelanjutan, transparan, dan berbasis sains.

**Tujuan Khusus:**
1. Mendokumentasikan kebutuhan sistem informasi dan fitur-fitur yang diusulkan
2. Menguraikan peran dan tanggung jawab berbagai pemangku kepentingan
3. Menyediakan panduan teknis untuk Rencana Perlindungan dan Pengelolaan Ekosistem Mangrove (RPPEM)
4. Menjadi referensi untuk pengembangan sistem dan regulasi terkait
5. Memfasilitasi koordinasi lintas sektor dalam perlindungan mangrove

## Struktur Repository

```
mangrove-agent/
├── readme.md                    # Dokumentasi utama (file ini)
├── Sistem Informasi/           # Dokumentasi Sistem Informasi SIPM
│   ├── index.md               # Deskripsi fitur dan arsitektur sistem
│   └── roles.md               # Peran pengguna dan tanggung jawab
└── RPPEM/                      # Rencana Perlindungan dan Pengelolaan Ekosistem Mangrove
    └── index.md               # Panduan dan template RPPEM
```

### Penjelasan Direktori

#### **Sistem Informasi/**
Direktori ini berisi dokumentasi lengkap tentang Sistem Informasi Perlindungan dan Pengelolaan Ekosistem Mangrove (SIPM), yang mencakup:

- **Fitur Geospasial:** Peta interaktif, peta kesatuan lanskap mangrove (KLM), visualisasi spasial
- **Basis Data:** Profil ekosistem, karakteristik fisik, biologis, dan sosial-ekonomi
- **Monitoring:** Pemantauan kondisi, analisis tren, deteksi kerusakan
- **Rekomendasi:** Saran pengelolaan dan pemulihan berdasarkan analisis data
- **Partisipasi:** Fitur untuk pelaporan masyarakat dan pengaduan

Dokumen di direktori ini juga menjabarkan 12 peran pengguna utama sistem, mulai dari admin sistem hingga publik umum.

#### **RPPEM/**
Direktori ini menyediakan panduan dan template untuk menyusun Rencana Perlindungan dan Pengelolaan Ekosistem Mangrove (RPPEM) yang merupakan dokumen wajib di tingkat nasional, provinsi, dan kabupaten/kota.

## Fitur Utama

Sistem Informasi Perlindungan dan Pengelolaan Ekosistem Mangrove yang didokumentasikan dalam repository ini menawarkan fitur-fitur berikut:

### 1. **Peta Geospasial Interaktif**
- Visualisasi peta mangrove nasional dengan skala minimal 1:25.000
- Peta Kesatuan Lanskap Mangrove (KLM)
- Peta fungsi ekosistem (lindung vs. budidaya)
- Tools interaktif: zoom, identifikasi, filter, cetak peta

### 2. **Dashboard Informasi Komprehensif**
- Profil ekosistem dari tingkat nasional hingga desa
- Data karakteristik fisik (substrat, pH, salinitas, hidrologi)
- Data biologis (spesies, kerapatan, keanekaragaman)
- Data sosial-ekonomi (kependudukan, mata pencaharian, kearifan lokal)

### 3. **Sistem Monitoring dan Evaluasi**
- Analisis tren waktu (time-series) perubahan kondisi mangrove
- Indikator kriteria baku kerusakan
- Pencatatan status kondisi (baik, terganggu, rusak)
- Update data berkala (minimal 5 tahun sekali)

### 4. **Modul Perencanaan dan Rekomendasi**
- Rekomendasi fungsi kawasan berdasarkan analisis kerentanan
- Peta indikatif pemulihan mangrove
- Penyimpanan dokumen perencanaan nasional-desa

### 5. **Platform Partisipasi Masyarakat**
- Formulir pelaporan kerusakan, pengaduan, dan saran
- Map tagging untuk penandaan lokasi spasial
- Notifikasi tindak lanjut kepada masyarakat

## Dokumentasi

Repository ini menyediakan dokumentasi komprehensif yang mencakup:

### Dokumen Utama
- **[Sistem Informasi/index.md](./Sistem%20Informasi/index.md)** – Deskripsi fitur sistem informasi, arsitektur, dan kebutuhan data
- **[Sistem Informasi/roles.md](./Sistem%20Informasi/roles.md)** – Peran pengguna, fungsi, dan tanggung jawab dalam sistem
- **[RPPEM/index.md](./RPPEM/index.md)** – Panduan menyusun Rencana Perlindungan dan Pengelolaan Ekosistem Mangrove

### Konten Tersedia
- Kebutuhan fungsional sistem
- Spesifikasi data dan metadata
- Deskripsi peran dan akses pengguna
- Template dan panduan perencanaan

## Kontribusi

Repository ini terbuka untuk kontribusi dan masukan dari berbagai pemangku kepentingan, termasuk:

- **Praktisi Lingkungan & Konservasi** – Untuk memberikan perspektif teknis dan lapangan
- **Profesional Teknologi Informasi** – Untuk pengembangan dan implementasi sistem
- **Pemerintah dan Pemerintah Daerah** – Untuk keselarasan dengan kebijakan dan operasional
- **Masyarakat dan Organisasi Lokal** – Untuk memastikan responsivitas terhadap kebutuhan lokal

Jika Anda ingin berkontribusi atau memiliki saran perbaikan, silakan:
1. Buat *issue* untuk mendiskusikan ide atau masalah
2. Submit *pull request* dengan perbaikan atau penambahan konten
3. Hubungi pihak penyelenggara melalui kontak di bawah

## Lisensi dan Kontak

### Lisensi
Repository ini tersedia di bawah lisensi [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/deed.id), memungkinkan penggunaan, modifikasi, dan distribusi dengan atribusi yang sesuai.

### Kontak dan Informasi Lebih Lanjut
Untuk informasi lebih lanjut, pertanyaan, atau masukan mengenai Mangrove Agent, silakan menghubungi:

- **Kementerian Lingkungan Hidup dan Kehutanan (KLHK)**
- **Badan Perlindungan Lingkungan Hidup (BPLH)**

---

**Versi:** 1.0  
**Tanggal Update:** April 2026  
**Status:** Development
