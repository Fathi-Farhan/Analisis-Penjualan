# 📊 Analisis Strategis Penjualan Ritel Global

### Mengubah Data Transaksi Menjadi Rekomendasi Bisnis untuk Pertumbuhan

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3B79DE?style=for-the-badge&logo=matplotlib&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4B8BBE?style=for-the-badge&logo=seaborn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

> **Ringkasan Proyek:** Proyek ini adalah studi kasus analisis data end-to-end yang menginvestigasi data penjualan historis selama dua tahun. Tujuannya adalah untuk mengungkap wawasan tersembunyi mengenai perilaku pelanggan, kinerja produk, dan dinamika pasar. Hasil analisis ini dikemas menjadi rekomendasi strategis yang dapat langsung diimplementasikan untuk mendorong pertumbuhan pendapatan dan efisiensi operasional.

---

### 🎯 **Tantangan Bisnis**

Di tengah persaingan ritel yang ketat, perusahaan perlu membuat keputusan yang cerdas dan berbasis data. Tanpa memahami **'kapan'**, **'di mana'**, dan **'apa'** yang mendorong penjualan, perusahaan berisiko kehilangan peluang pertumbuhan dan mengalokasikan sumber daya secara tidak efisien.

### ❓ **Pertanyaan Kunci yang Dipecahkan**

Analisis ini dirancang untuk menjawab pertanyaan-pertanyaan fundamental berikut:

- [x] **Tren Musiman:** Kapan periode puncak dan terendah penjualan dalam setahun?
- [x] **Pasar Utama:** Di kota mana basis pelanggan kita yang paling kuat?
- [x] **Waktu Emas:** Jam berapa pelanggan paling aktif melakukan pembelian?
- [x] **Produk Juara:** Lini produk apa yang menjadi mesin pendapatan utama?
- [x] **Pelanggan VIP:** Siapa pelanggan korporat yang paling loyal dan bernilai?
- [x] **Pola Belanja:** Produk apa saja yang sering dibeli bersamaan oleh pelanggan?

---

### 🚀 **Alur Kerja Analisis**

Proyek ini mengikuti metodologi analisis data yang terstruktur:

1.  **Pembersihan & Pra-pemrosesan Data:** Memastikan data akurat, konsisten, dan siap dianalisis dengan menangani nilai yang hilang, mengoreksi tipe data, dan melakukan standarisasi.
2.  **Analisis Data Eksplorasi (EDA):** Menggali data menggunakan statistik deskriptif dan agregasi untuk menemukan pola, anomali, dan hubungan antar variabel.
3.  **Visualisasi Data:** Menceritakan kisah di balik data melalui grafik yang jelas dan berdampak menggunakan Matplotlib dan Seaborn.
4.  **Sintesis Wawasan & Rekomendasi:** Menerjemahkan temuan teknis menjadi kesimpulan dan rekomendasi bisnis yang strategis dan dapat ditindaklanjuti.

---

### 💡 **Wawasan Utama & Temuan Kunci**

* 📈 **Ledakan Penjualan di Kuartal Keempat**
    Penjualan melonjak drastis di bulan **Oktober dan November**, menandakan momentum kuat menjelang musim liburan yang harus dimanfaatkan secara maksimal.

    *[Gambar Grafik Penjualan Bulanan]*

* 🌍 **Madrid sebagai Jantung Penjualan**
    Dengan kontribusi **lebih dari $1 Juta**, **Madrid** terbukti sebagai pasar paling vital. Ini menunjukkan dominasi kuat di pasar Spanyol yang perlu dipertahankan.

    *[Gambar Grafik Penjualan per Kota]*

* 🚗 **"Classic Cars" Tak Tergoyahkan**
    **'Classic Cars'** adalah lini produk andalan yang menyumbang pendapatan lebih dari **$3.9 Juta**, menjadikannya aset paling berharga dalam portofolio produk perusahaan.

    *[Gambar Grafik Penjualan per Lini Produk]*

* 🏢 **Kekuatan Pelanggan Korporat**
    Pelanggan B2B seperti **'Euro Shopping Channel'** dan **'Mini Gifts Distributors Ltd.'** adalah pendorong pendapatan utama, menggarisbawahi pentingnya strategi manajemen akun khusus untuk klien korporat.

    *[Gambar Grafik Top 10 Pelanggan]*

* 🌙 **Misteri Aktivitas Tengah Malam**
    Analisis mengungkap pola unik di mana jumlah pesanan mencapai puncaknya pada **tengah malam**. Fenomena ini membuka peluang untuk kampanye pemasaran non-tradisional yang menargetkan audiens malam hari.

    *[Gambar Grafik Pesanan per Jam]*

### 🏆 **Rekomendasi Strategis untuk Pertumbuhan**

1.  **Maksimalkan Momentum Q4:** Luncurkan kampanye pemasaran terintegrasi mulai bulan September. Alokasikan budget iklan terbesar dan siapkan inventaris produk terlaris untuk periode **Oktober-November**.
2.  **Strategi Penetrasi Pasar:**
    * **Untuk Madrid:** Implementasikan program loyalitas eksklusif untuk mempertahankan dominasi pasar.
    * **Untuk Kota Lain:** Tawarkan promosi agresif seperti "gratis ongkir" atau diskon untuk pembelian pertama guna meningkatkan pangsa pasar.
3.  **Optimalkan Penawaran Produk:** Manfaatkan temuan produk yang sering dibeli bersamaan (*market basket analysis*) untuk menciptakan penawaran **paket (bundle)** yang menarik. Contoh: Tawarkan diskon untuk 'Vintage Cars' bagi pelanggan yang membeli 'Classic Cars'.
4.  **Kampanye "Midnight Sale":** Uji coba kampanye iklan digital (misalnya di media sosial) yang spesifik menargetkan audiens antara pukul 22:00 - 02:00 untuk menangkap segmen pelanggan yang aktif pada malam hari.

---

### 🛠️ **Cara Mereplikasi Analisis Ini**

Tertarik untuk menjalankan analisis ini sendiri?

1.  **Prasyarat:** Pastikan Anda memiliki Python dan library berikut terpasang.
    ```bash
    pip install pandas matplotlib seaborn jupyterlab
    ```
2.  **Clone Repositori:**
    ```bash
    git clone [URL_REPOSITORI_ANDA_DI_SINI]
    ```
3.  **Jalankan Jupyter:** Navigasikan ke direktori proyek dan jalankan Jupyter Lab.
    ```bash
    cd [NAMA_DIREKTORI_PROYEK]
    jupyter lab
    ```
4.  **Buka Notebook:** Buka file `projectDataAnalyst.ipynb` dan jalankan sel-sel kode di dalamnya.
