Nama : Naufal Ahnafussidqi Perdana

NIM : 452024611023

# Image Manipulation - Tugas Pengolahan Sinyal Digital

Repositori ini berisi tugas mata kuliah Pengolahan Sinyal Digital (PSD) yang berfokus pada manipulasi dan pemrosesan citra digital menggunakan **Jupyter Notebook**.

## 📌 Tentang Proyek
Proyek ini mendemonstrasikan berbagai teknik dasar hingga lanjut dalam memanipulasi gambar digital secara programatik. Pemrosesan dilakukan langkah demi langkah di dalam file `image_manipulation.ipynb` untuk memberikan visualisasi yang jelas pada setiap operasi sinyal dua dimensi (citra).

## Citra yang Digunakan

* Image 1 : Foto Mobil Toyota Supra MK 4
* Image 2 : Foto Mobil Nissan Skyline R32

## 🛠️ Prasyarat & Library yang Digunakan
Untuk menjalankan notebook di repositori ini, pastikan Anda telah menginstal beberapa library Python berikut:
* **Python 3.x**
* **Jupyter Notebook / Lab**
* **OpenCV** (`opencv-python`) - Untuk pemrosesan citra utama.
* **NumPy** - Untuk manipulasi array dan matriks piksel.
* **Matplotlib** - Untuk visualisasi citra dan grafik histogram.

Anda bisa menginstal library yang diperlukan sekaligus dengan menjalankan perintah berikut di terminal:
```bash
pip install jupyter opencv-python numpy matplotlib
```

## 💻 Cara Menjalankan
1. Clone repositori ini ke komputer lokal Anda:
   ```bash
   git clone https://github.com/NaufalAhnafussidqi/image-manipulation.git
   ```
2. Masuk ke direktori proyek:
   ```bash
   cd image-manipulation
   ```
3. Jalankan Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Buka dan jalankan file `image_manipulation.ipynb`.

## 📁 Struktur Repositori
* `image_manipulation.ipynb`: Notebook utama tempat seluruh kode implementasi manipulasi citra ditulis.
* `README.md`: Dokumentasi panduan proyek ini.

## Ringkasan Hasil

Eksperimen menunjukkan bahwa setiap teknik manipulasi citra memiliki fungsi yang berbeda. Image blending digunakan untuk menggabungkan dua citra, image negative membalik nilai pixel, transformasi logaritmik meningkatkan detail area gelap, dan transformasi gamma digunakan untuk koreksi pencahayaan.

## Kesimpulan

Manipulasi citra digital menggunakan OpenCV dapat dilakukan dengan berbagai metode sesuai kebutuhan. Pemilihan teknik yang tepat dapat meningkatkan kualitas visual dan informasi yang terkandung dalam citra.
