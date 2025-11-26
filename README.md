# Stokastik_03_RB

## 📘 Implementasi Rantai Markov Waktu Diskrit untuk Pemodelan Pola Kunjungan Perpustakaan GKU 2

Repository ini berisi laporan dan hasil penelitian mengenai pemodelan pola kunjungan perpustakaan GKU 2 Institut Teknologi Sumatera menggunakan Rantai Markov Waktu Diskrit (DTMC). Penelitian dilakukan sebagai bagian dari tugas mata kuliah Pemodelan Stokastik.

### 📌 Ringkasan Penelitian

Penelitian ini bertujuan untuk:

- Menganalisis pola perubahan jumlah pengunjung perpustakaan dalam interval waktu 10 menit.
- Mengklasifikasikan jumlah pengunjung ke dalam tiga state: Sepi (0–33), Sedang (34–66), dan Ramai (67–100).
- Menyusun matriks peluang transisi dan mengevaluasi distribusi jangka panjang (steady state) menggunakan model Rantai Markov.
- Pengumpulan data dilakukan melalui observasi primer selama satu hari penuh (08:00–16:00) dengan total 49 titik data.

### 📊 Hasil Utama

- Nilai diagonal matriks transisi didominasi oleh probabilitas tinggi (retensi state), menunjukkan pengunjung cenderung bertahan dalam kondisi yang sama.
- State Ramai memiliki retensi terbesar (0.94), menandakan perpustakaan cenderung stabil dalam kondisi penuh.
- Model menunjukkan bahwa dalam jangka panjang, kondisi perpustakaan akan berada:
  - 0.0026% pada state Sepi
  - 16% pada state Sedang
  - 84% pada state Ramai
- Prediksi jangka pendek (30 menit ke depan) menunjukkan kecenderungan peningkatan kepadatan terutama dari state Sedang → Ramai.

### 🧠 Metode

Penelitian menggunakan beberapa komponen utama DTMC, yaitu:

- Ruang Keadaan (State Space)
- Matriks Peluang Transisi
- Diagram Transisi
- Distribusi Stasioner (steady state distribution)
- Prediksi n-langkah (n-step transition probability)
- Klasifikasi State (recurrent, transient)

Semua perhitungan dilakukan menggunakan data observasi lapangan dan disajikan dalam bentuk tabel, grafik, serta analisis matematis.

### 📂 Isi Repository
📁 / (root directory)
│
├── README.md                
├── Poster_3_RB.pdf         
├── Kelompok 3_PemStok.pdf  
└── Dataset_3_RB.xlsx       

### 👥 Tim Peneliti

Kelompok 3 – Pemodelan Stokastik:

- Dwi Ratna Anggraini (122450008)
- Meira Listyaningrum (122450011)
- Tessa Kania Sagala (122450040)
- Priska Silvia Ferantiana (122450053)

Dosen Pembimbing:

Mika Alvionita S., M.Si
Indah Suciati, M.Mat
