# Sistem Rekapitulasi Nilai Siswa – SMPN 10 Depok

Sistem Rekapitulasi Nilai Siswa adalah aplikasi web modern, terintegrasi, dan responsif yang dirancang untuk mempermudah pendidik dan pihak sekolah dalam mengelola, menganalisis, memantau, serta mengekspor data capaian nilai akademik peserta didik secara akurat dan efisien.

Aplikasi ini terhubung langsung dengan sumber data spreadsheet sekolah, menyajikan visualisasi data komprehensif, dan dirancang dengan standar aksesibilitas serta performa tinggi pada berbagai perangkat, mulai dari komputer desktop, tablet, hingga ponsel pintar.

---

## Fitur-Fitur Utama Aplikasi

### 1. Autentikasi dan Keamanan Pengguna
* **Sistem Masuk Berbasis NIP & PIN**: Mekanisme autentikasi terverifikasi khusus bagi tenaga pendidik dan staf resmi sekolah.
* **Aktivasi & Pembuatan PIN Mandiri**: Guru baru dapat melakukan aktivasi akun secara mandiri menggunakan kode aktivasi dari administrator serta membuat PIN 6 digit dengan konfirmasi pengulangan.
* **Fitur Tampilkan / Sembunyikan PIN**: Mempermudah pengguna memeriksa kebenaran input PIN saat proses login maupun aktivasi.
* **Sesi Aman & Terkendali**: Pengelolaan sesi berbasis token dengan masa kedaluwarsa otomatis dan penyimpanan lokal yang aman (*secure client-side storage*).

### 2. Dashboard Eksekutif & Pemantauan Akademik
* **Indikator Progres Ganda (Dual Progress Ring)**:
  * **Ketuntasan Belajar**: Menampilkan persentase peserta didik yang telah mencapai Kriteria Ketuntasan Minimal (standar KKM 75).
  * **Kelengkapan Data**: Memantau persentase kelengkapan pengisian nilai dari seluruh komponen mata pelajaran yang ada.
* **Statistik Kunci Sekolah**: Kartu ringkasan metrik utama mencakup total siswa, rata-rata nilai umum sekolah, nilai tertinggi, nilai terendah, dan tren capaian.
* **Panel "Perlu Perhatian" (Deteksi Intervensi Dini)**: Mengidentifikasi secara instan siswa yang memerlukan bimbingan remedial dengan label prioritas otomatis (*Kritis*, *Bimbingan*, dan *Hampir*) beserta jumlah mata pelajaran yang belum tuntas.
* **Peta Nilai Interaktif (Heatmap & Mobile Accordion)**:
  * **Tampilan Desktop/Tablet (Matriks Peta Nilai)**: Matriks kelas × mata pelajaran lengkap dengan header kolom lengket (*sticky*), kolom nama kelas lengket di sisi kiri, kolom rata-rata per kelas di sisi kanan, serta baris rata-rata tiap mata pelajaran di bagian bawah.
  * **Tampilan Ponsel (Kartu Akordion Bebas Geser)**: Menghilangkan kebutuhan geser horizontal pada layar kecil dengan menyajikan kartu akordion per kelas, daftar mata pelajaran terurut dari nilai terendah, dan pembukaan otomatis pada kelas yang memerlukan perhatian.
  * **Skema Warna Semantik 3 Tingkat**: Pembedaan visual yang jelas antara kategori Di Bawah KKM (merah muda lembut dengan penanda ▼), Mendekati KKM (netral terang), Tuntas (hijau toska lembut), serta tanda strip putus-putus untuk sel tanpa data.
  * **Penyaringan Cepat & Saring KKM**: Filter berdasarkan tingkatan kelas (Kelas 7, 8, dan 9) serta tombol filter cepat *"Hanya di bawah KKM"* untuk memusatkan evaluasi pada mata pelajaran bermasalah.
  * **Navigasi Terintegrasi**: Setiap sel nilai, nama mata pelajaran, dan nama kelas dapat diklik untuk langsung mengarahkan ke halaman analisis rinci yang relevan.
* **Distribusi Frekuensi Nilai**: Grafik histogram sebaran interval nilai untuk mengetahui pola capaian belajar secara menyeluruh.
* **Peringkat Capaian Mata Pelajaran**: Diagram batang horizontal yang menyajikan perbandingan rata-rata capaian nilai antar seluruh mata pelajaran.

### 3. Modul Nilai per Kelas
* **Rekapitulasi Rombongan Belajar**: Penyajian tabel nilai seluruh mata pelajaran untuk kelas yang dipilih.
* **Pencarian Instan Siswa**: Fasilitas pencarian data siswa secara cepat berdasarkan nama lengkap maupun nomor urut/absen.
* **Perhitungan Nilai Rata-Rata Otomatis**: Menghitung nilai rata-rata tiap siswa serta rata-rata kumulatif kelas pada masing-masing mata pelajaran.
* **Ekspor Data Nilai Kelas**: Fitur pengunduhan rekap nilai kelas ke dalam format dokumen spreadsheet Microsoft Excel (`.xlsx`).

### 4. Modul Nilai per Mata Pelajaran
* **Analisis Mendalam per Mapel**: Menelaah performa akademik pada satu mata pelajaran pilihan, baik untuk satu kelas tertentu maupun lintas seluruh kelas.
* **Statistik Deskriptif Lengkap**: Perhitungan otomatis rata-rata mata pelajaran, nilai tertinggi, nilai terendah, median, persentase kelulusan, dan jumlah siswa yang berada di bawah KKM.
* **Grafik Sebaran Nilai Mapel**: Histogram distribusi frekuensi nilai spesifik pada mata pelajaran yang dipilih.
* **Komparasi Antarkelas**: Tabel perbandingan rata-rata nilai dan tingkat kelulusan antarkelas.
* **Daftar Siswa Remedial**: Rekapitulasi terfokus untuk siswa di bawah KKM dilengkapi selisih kekurangan nilai (*gap*) guna mempermudah tindak lanjut bimbingan belajar.
* **Ekspor Nilai Mata Pelajaran**: Fitur pengunduhan data nilai mata pelajaran terkait ke dalam format file `.xlsx`.

### 5. Ekspor Data Menyeluruh
* **Unduh Seluruh Basis Data Nilai**: Tombol pengunduhan satu pintu untuk mengunduh seluruh data rekap nilai sekolah ke dalam berkas Excel (`.xlsx`).

### 6. Desain Antarmuka, Responsivitas, dan Aksesibilitas
* **Desain Adaptif Sepenuhnya**: Tampilan tertata rapi dan optimal di berbagai ukuran layar, mulai dari ponsel (360px–440px), tablet (768px), hingga monitor komputer (1366px–1920px).
* **Dukungan Tema Terang dan Gelap**: Beradaptasi otomatis mengikuti preferensi sistem operasi pengguna (*prefers-color-scheme*) dengan kontras warna yang nyaman bagi mata.
* **Standar Aksesibilitas Web (WCAG)**: Rasio kontras warna tinggi (memenuhi standar $\ge 4.5:1$), navigasi penuh dengan papan ketik (*keyboard navigation*), tautan lewati ke konten (*skip to main content*), dan label aksesibilitas ARIA.
* **Kinerja Cepat dan Perlindungan Beban Server**: Sistem pendingin tombol pembaruan (*refresh cooldown*) dan penyimpanan cache lokal untuk menjaga stabilitas dan efisiensi pengambilan data.

---

## Informasi Pengembang dan Ketentuan Penggunaan

Aplikasi ini dikembangkan oleh **muhammaddoank**.

> **PERINGATAN PENGGUNAAN:**  
> Aplikasi, struktur data, dan seluruh kode sumber yang ada di dalam sistem ini dikembangkan secara eksklusif oleh **muhammaddoank**.  
> **Dilarang keras menggunakan, menggandakan, memodifikasi, menyebarluaskan, atau memanfaatkan aplikasi ini secara sembarangan** tanpa izin resmi dan tertulis dari pengembang. Segala bentuk pelanggaran dan penggunaan tanpa hak akan diproses sesuai dengan ketentuan hukum yang berlaku.
