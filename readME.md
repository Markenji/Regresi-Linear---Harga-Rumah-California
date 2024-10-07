# Regresi Linear dengan California Housing Dataset

Proyek ini mendemonstrasikan cara menerapkan regresi linear menggunakan dataset California Housing dengan scikit-learn. Kode ini memuat contoh pengambilan dataset, preprocessing data, dan melakukan cross-validation untuk mengevaluasi kinerja model.

## Dataset

Dataset yang digunakan dalam proyek ini adalah **California Housing Dataset**, yang berisi informasi tentang harga rumah median di berbagai distrik di California. Variabel target adalah nilai median rumah di distrik-distrik California, yang dinyatakan dalam ratusan ribu dolar.

### Fitur:

- `MedInc`: Pendapatan median dalam kelompok.
- `HouseAge`: Usia median rumah dalam kelompok.
- `AveRooms`: Jumlah rata-rata kamar per rumah tangga.
- `AveBedrms`: Jumlah rata-rata kamar tidur per rumah tangga.
- `Population`: Populasi kelompok.
- `AveOccup`: Rata-rata jumlah anggota rumah tangga.
- `Latitude`: Garis lintang kelompok.
- `Longitude`: Garis bujur kelompok.

### Target:

- `Price`: Nilai median rumah untuk distrik-distrik di California, dalam ratusan ribu dolar.

## Instalasi

Anda memerlukan Python 3.x dan pustaka berikut untuk menjalankan kode:

- `numpy`
- `pandas`
- `seaborn`
- `matplotlib`
- `scikit-learn`

Untuk menginstal pustaka yang dibutuhkan, jalankan perintah berikut:

```bash
pip install numpy pandas seaborn matplotlib scikit-learn
