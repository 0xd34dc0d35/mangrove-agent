# Sistem Informasi Perlindungan dan Pengelolaan Ekosistem Mangrove

## Daftar Isi
- [Pendahuluan](#pendahuluan)
- [Konteks dan Mandat Regulasi](#konteks-dan-mandat-regulasi)
- [Fitur Sistem Informasi](#fitur-sistem-informasi)
  - [1. Fitur Peta Geospasial Interaktif](#1-fitur-peta-geospasial-interaktif)
  - [2. Fitur Basis Data dan Profil Ekosistem](#2-fitur-basis-data-dan-profil-ekosistem)
  - [3. Fitur Pemantauan Kondisi dan Evaluasi Kerusakan](#3-fitur-pemantauan-kondisi-dan-evaluasi-kerusakan)
  - [4. Fitur Rekomendasi Pengelolaan dan Pemulihan](#4-fitur-rekomendasi-pengelolaan-dan-pemulihan)
  - [5. Fitur Partisipasi dan Pelaporan Masyarakat](#5-fitur-partisipasi-dan-pelaporan-masyarakat)
- [Peran Pengguna dalam Sistem](#peran-pengguna-dalam-sistem)
- [Referensi Dokumen](#referensi-dokumen)

## Pendahuluan

Sistem Informasi Perlindungan dan Pengelolaan Ekosistem Mangrove merupakan platform digital yang dirancang untuk mendukung pelaksanaan mandat pemerintah dalam melindungi dan mengelola ekosistem mangrove di tingkat nasional. Sistem ini mengintegrasikan data spasial, informasi ekologis, data sosial-ekonomi, dan fitur partisipasi masyarakat untuk memastikan pengelolaan ekosistem mangrove yang berkelanjutan, berbasis sains, dan inklusif.

Dokumen ini menjabarkan komponen utama sistem informasi, fitur-fitur yang diusulkan, serta peran berbagai pemangku kepentingan dalam memanfaatkan sistem ini.

## Konteks dan Mandat Regulasi

Berdasarkan peraturan yang berlaku, pengelolaan data inventarisasi mangrove diamanatkan untuk menggunakan **sistem informasi berbasis spasial**. Oleh karena itu, dalam merancang sistem informasi perlindungan dan pengelolaan ekosistem mangrove, dirancang fitur-fitur berikut yang mengacu pada kebutuhan data, analisis, dan pelibatan masyarakat yang diwajibkan oleh undang-undang:

## Fitur Sistem Informasi

### 1. Fitur Peta Geospasial Interaktif (Sistem Informasi Geografis)
Sistem harus mampu menampilkan data spasial (keruangan) secara interaktif, yang meliputi:
*   **Peta Mangrove Nasional dan Peta Kesatuan Lanskap Mangrove (KLM)** yang disajikan dengan skala minimal 1:25.000 atau tingkat ketelitian lebih tinggi.
*   Visualisasi **sebaran, koordinat geometri, luas area, dan delineasi batas** ekosistem mangrove.
*   **Peta Fungsi Ekosistem Mangrove**, untuk membedakan secara visual area mana yang ditetapkan sebagai fungsi lindung dan mana yang memiliki fungsi budidaya.

### 2. Fitur Basis Data dan Profil Ekosistem (Dashboard Informasi)
Fitur ini digunakan untuk menyajikan profil atau kumpulan data komprehensif mengenai ekosistem mangrove dari tingkat nasional hingga desa. Atribut yang dimuat meliputi:
*   **Karakteristik Fisik:** Informasi mengenai jenis substrat, tingkat keasaman (pH), salinitas perairan, hidrologi, gelombang, dan tipe pasang surut.
*   **Karakteristik Biologis:** Data mengenai komposisi spesies/jenis vegetasi mangrove (mayor, minor, asosiasi), tingkat kerapatan (jarang, sedang, lebat), serta status keanekaragaman flora dan fauna di lokasi tersebut.
*   **Karakteristik Sosial-Ekonomi dan Kelembagaan:** Menampilkan informasi kependudukan, mata pencaharian dominan (seperti nelayan atau petani tambak), kearifan lokal, dan kelembagaan lokal (misal: Kelompok Sadar Wisata) yang berinteraksi dengan mangrove.

### 3. Fitur Pemantauan Kondisi dan Evaluasi Kerusakan (Monitoring)
Sistem perlu memiliki fitur untuk memantau perubahan lingkungan, yang mencakup:
*   **Analisis Tren Waktu (Time-series):** Memantau perubahan tutupan lahan dan tingkat kerapatan pohon dari waktu ke waktu (misalnya membandingkan data saat ini dengan perubahannya selama 10 tahun terakhir).
*   **Indikator Kriteria Baku Kerusakan:** Sistem dapat memberikan peringatan jika ekosistem melampaui ambang batas kerusakan, seperti terjadinya penurunan persentase tutupan tajuk dan kerapatan pohon sebesar $\ge25\%$ untuk fungsi lindung, atau $\ge50\%$ untuk fungsi budidaya. 
*   **Pencatatan Status Kerusakan:** Menampilkan status kondisi ekosistem (baik, terganggu, rusak) beserta penyebab utama kerusakannya (misalnya konversi menjadi tambak atau abrasi laut).
*   **Pemutakhiran Data Berkala:** Mengakomodasi update data secara berkala, di mana pemutakhiran diwajibkan paling sedikit 1 (satu) kali dalam 5 (lima) tahun.

### 4. Fitur Rekomendasi Pengelolaan dan Pemulihan
Sistem informasi dapat menyediakan modul perencanaan yang berisi arahan pengelolaan lahan, meliputi:
*   **Rekomendasi Fungsi Kawasan:** Penetapan usulan area untuk tetap menjadi fungsi lindung atau fungsi budidaya berdasarkan analisis kerentanan dan jasa ekosistem.
*   **Peta Indikatif Pemulihan:** Menyajikan titik lokasi rekomendasi kegiatan pemulihan mangrove (seperti rehabilitasi, restorasi, suksesi alami, atau perlindungan habitat).
*   **Penyimpanan Dokumen Perencanaan:** Menyimpan dokumen Rencana Perlindungan dan Pengelolaan Ekosistem Mangrove di tingkat nasional, provinsi, dan kabupaten/kota.

### 5. Fitur Partisipasi dan Pelaporan Masyarakat
Sebagai bentuk pemberdayaan dan pelibatan masyarakat luas, sistem dapat mengusulkan layanan interaktif publik yang meliputi:
*   Formulir elektronik untuk **penyampaian informasi, laporan, pengaduan kerusakan, serta pemberian saran atau keberatan** terkait perlindungan dan pengelolaan ekosistem mangrove di wilayah mereka.

## Peran Pengguna dalam Sistem

Sistem Informasi Perlindungan dan Pengelolaan Ekosistem Mangrove dirancang untuk melayani berbagai pemangku kepentingan dengan peran dan tanggung jawab yang berbeda. Terdapat 12 peran utama dalam sistem ini:

1. **Admin Sistem** – Mengelola operasional sistem, basis data nasional, kualitas data, dan publikasi informasi resmi.
2. **Pengambil Kebijakan** – Menggunakan sistem sebagai dasar penetapan kebijakan dan prioritas program perlindungan mangrove.
3. **Perencana dan Evaluator** – Menyusun perencanaan PPEM dan memantau capaian berbasis data.
4. **Pelaksana / Petugas Survey (Enumerator)** – Mendukung operasional pendataan di lapangan dan input data survei.
5. **Pengawas** – Melakukan verifikasi, pengawasan kepatuhan, dan dukungan penegakan hukum.
6. **Publik (Pengguna Umum / Tamu)** – Mengakses informasi publik untuk transparansi dan partisipasi masyarakat.
7. **Pengguna Terdaftar** – Menyampaikan pengaduan masyarakat melalui sistem.
8. **Pemerintah Daerah Provinsi** – Melakukan koordinasi dan validasi data tingkat provinsi.
9. **Pemerintah Daerah Kabupaten** – Mengelola operasional dan validasi data tingkat kabupaten/kota.
10. **Pemrakarsa Kegiatan Usaha** – Melakukan pelaporan dan pemenuhan kewajiban pengelolaan lingkungan.
11. **Badan Perlindungan Ekosistem Gambut dan Mangrove (BPEGM)** – Mengkoordinasikan program pemulihan lintas wilayah.
12. **Kementerian / Lembaga** – Melakukan konsolidasi dan sinkronisasi data lintas sektoral.

Untuk deskripsi lengkap tentang fungsi dan tugas masing-masing peran, lihat dokumen [Roles dan Tanggung Jawab](./roles.md).

## Referensi Dokumen

Dokumen ini merupakan bagian dari rangkaian dokumentasi Sistem Informasi Perlindungan dan Pengelolaan Ekosistem Mangrove:

- **[README.md](../readme.md)** – Pengenalan umum tentang repositori Mangrove Agent
- **[Roles.md](./roles.md)** – Deskripsi lengkap peran pengguna, fungsi, dan tanggung jawab dalam sistem
- **[RPPEM/index.md](../RPPEM/index.md)** – Informasi tentang Rencana Perlindungan dan Pengelolaan Ekosistem Mangrove

## Kesimpulan

Sistem Informasi Perlindungan dan Pengelolaan Ekosistem Mangrove merupakan instrumen penting dalam mewujudkan pengelolaan ekosistem mangrove yang berkelanjutan, transparan, dan berbasis bukti ilmiah. Melalui integrasi fitur geospasial, monitoring, analisis, dan partisipasi masyarakat, sistem ini mendukung pengambilan keputusan yang lebih baik di semua tingkat pemerintahan, serta memberdayakan masyarakat untuk berperan aktif dalam perlindungan ekosistem mangrove.