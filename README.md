# 1. Judul Project
**Image Manipulation - Tugas Pengolahan Sinyal Digital**

## 2. Nama Mahasiswa
* **Nama:** Naufal Ahnafussidqi
* **NIM:** 452024611023
* **Repositori:** [NaufalAhnafussidqi/image-manipulation](https://github.com)

## 3. Deskripsi Singkat Project
Project ini dibuat untuk memenuhi tugas mata kuliah Pengolahan Sinyal Digital (PSD). Fokus utama dari project ini adalah menerapkan berbagai teknik manipulasi dan pemrosesan citra digital secara programatik. Melalui Jupyter Notebook, dilakukan eksperimen interaktif untuk memahami bagaimana operasi matematika dan filter spasial diaplikasikan pada matriks piksel citra dua dimensi.

## 4. Citra yang Digunakan
Eksperimen dalam notebook ini menggunakan beberapa sampel citra digital sebagai input, antara lain:
1. `[Nama_File_Citra_1.jpg/png]` - Foto Mobil Toyota Supra MK4
2. `[Nama_File_Citra_2.jpg/png]` - Foto mobil Nissan Skyline GT-R R32 

## 5. Library yang Digunakan
Project ini mengandalkan beberapa library pihak ketiga Python berikut:
* **OpenCV (`opencv-python`)**: Library utama untuk pemrosesan dan manipulasi citra.
* **NumPy**: Untuk manipulasi array N-dimensi (matriks piksel gambar).
* **Matplotlib**: Untuk menampilkan citra hasil proses serta visualisasi grafik histogram.

## 6. Cara Menjalankan Notebook
Ikuti langkah-langkah berikut untuk menjalankan notebook di komputer lokal Anda:

1. **Clone Repositori**
   ```bash
   git clone https://github.com
   ```
2. **Masuk ke Direktori Project**
   ```bash
   cd image-manipulation
   ```
3. **Instalasi Library Berdasarkan Prasyarat**
   ```bash
   pip install opencv-python numpy matplotlib jupyter
   ```
4. **Jalankan Jupyter Notebook**
   ```bash
   jupyter notebook
   ```
5. **Buka File Notebook**
   Pilih file `image_manipulation.ipynb` pada *interface* Jupyter, lalu jalankan setiap *cell* secara berurutan (`Shift + Enter`).

## 7. Struktur Folder Project
Berikut adalah struktur direktori dari repositori ini:
```text
image-manipulation/
│
├── image_manipulation.ipynb   # Notebook utama tempat kode eksperimen ditulis
├── README.md                  # Dokumentasi panduan project
└── [nama_gambar.jpg]          # File citra sampel yang digunakan sebagai input
```

## 8. Ringkasan Hasil Eksperimen
Berdasarkan pengerjaan di dalam notebook, berikut adalah ringkasan hasil dari setiap manipulasi citra yang dilakukan:
* **Konversi Ruang Warna:** Berhasil mengubah citra RGB menjadi *grayscale* dan citra biner secara akurat menggunakan batas *thresholding* tertentu.
* **Kecerahan & Kontras:** Peningkatan nilai kecerahan membuat visual gambar lebih terang, namun penambahan kontras yang berlebihan dapat memicu *clipping* warna pada piksel ekstrim.
* **Filtering & Deteksi Tepi:** Filter *Gaussian Blur* berhasil mereduksi *noise* pada citra secara halus. Sementara itu, operator deteksi tepi [misal: Canny / Sobel] berhasil mengekstrak kontur dan garis batas objek utama dengan jelas.

## 9. Kesimpulan Singkat
Manipulasi citra digital pada dasarnya adalah operasi matematika (seperti perkalian, penjumlahan, dan konvolusi) yang dilakukan langsung pada matriks piksel. Pemilihan jenis filter, penyesuaian parameter kecerahan, serta ketepatan fungsi library sangat menentukan kualitas akhir dari citra terproses agar sesuai dengan kebutuhan analisis sinyal digital selanjutnya.
