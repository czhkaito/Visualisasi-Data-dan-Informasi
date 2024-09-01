# Tugas 1 : Resume
```
Nama : Ridho Lailatul Akbar
NIM : 122140136
Kelas : RB
```

## 1. **Pendahuluan**
- **Visualisasi Data**: Penting untuk pengambilan keputusan di dunia bisnis yang berorientasi data. Visualisasi mengubah data abstrak menjadi bentuk visual, membantu dalam interpretasi dan komunikasi wawasan berbasis data.
- **Tantangan**: Permintaan tinggi untuk memproses volume data besar memerlukan teknik visualisasi data yang efisien dan dapat diskalakan.

## 2. **Pipeline Visualisasi Data**
- **Langkah-langkah**:
  1. **Impor Data**: Mengambil data dari sumber yang diinginkan.
  2. **Persiapan Data**: Membersihkan dan menyiapkan data untuk visualisasi.
  3. **Manipulasi Data**: Memfilter dan mengelompokkan data untuk visualisasi.
  4. **Pemetaan**: Memetakan data ke bentuk geometris seperti titik dan garis.
  5. **Rendering**: Mengubah data geometris menjadi representasi visual.

## 3. **Fokus Utama**
- **Spesifikasi Visualisasi**: Menentukan bagaimana pengguna dapat menentukan kebutuhan mereka untuk menghasilkan visualisasi.
- **Visualisasi Data yang Efisien**: Teknik untuk memproses data dan spesifikasi visualisasi secara efisien, memastikan skalabilitas pada kecepatan interaktif.
- **Rekomendasi Visualisasi Data**: Secara otomatis melengkapi atau menyarankan visualisasi berdasarkan spesifikasi yang tidak lengkap atau preferensi pengguna.

## 4. **Spesifikasi Visualisasi**
- **Komponen**: Data, tanda (petunjuk visual), dan pemetaan keduanya.
- **Kategorisasi**:
  - **Bahasa Tingkat Rendah**: Pengguna harus menentukan semua elemen pemetaan.
  - **Bahasa Tingkat Tinggi**: Merangkum detail konstruksi visualisasi, menawarkan pendekatan yang lebih mudah diakses.

## 5. **Pendekatan Efisien**
- **Terjemahan Query**: Mengonversi query visualisasi ke SQL untuk pemrosesan yang efisien.
- **Integrasi dengan DBMS**: Penggabungan erat antara pengambilan data dan rendering untuk meningkatkan kinerja.
- **Penyimpanan Kolom dan Indeks**: Teknik untuk meningkatkan kinerja dengan mengoptimalkan tata letak dan metode akses data.
- **Komputasi Paralel**: Mempercepat pemrosesan melalui eksekusi tugas secara paralel.
- **Prediksi dan Prefetching**: Teknik untuk mengantisipasi dan memuat data yang diperlukan sebelum tindakan pengguna, meningkatkan interaktivitas.

## 6. **Visualisasi Data Pendekatan Aproksimatif**
- **Berbasis AQP**: Menggunakan Pengolahan Query Aproksimatif untuk menghasilkan visualisasi cepat dengan kompromi pada akurasi.
- **Pengambilan Sampel Inkremental**: Secara bertahap meningkatkan kualitas visualisasi dengan meningkatkan ukuran sampel dari waktu ke waktu.
- **Berbasis Persepsi Manusia**: Menghentikan pengambilan sampel ketika peningkatan lebih lanjut tidak lagi dapat dipersepsikan oleh pengguna.

## 7. **Visualisasi Data Progresif**
- **Agregasi Hierarkis**: Menyediakan visualisasi pada berbagai tingkat detail dengan mengagregasikan data secara berbeda berdasarkan interaksi pengguna.

## 8. **Rekomendasi Visualisasi**
- **Berbasis Spesifikasi**: Secara otomatis menghasilkan visualisasi berdasarkan spesifikasi pengguna yang tidak lengkap atau perilaku sebelumnya.
- **Berbasis Perilaku**: Belajar dari interaksi pengguna untuk merekomendasikan visualisasi.
- **Rekomendasi yang Dipersonalisasi**: Menyesuaikan saran dengan preferensi pengguna individu.
