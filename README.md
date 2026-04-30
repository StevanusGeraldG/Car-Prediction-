# 🚗 Digging Into Used Car Sales: EDA & Data Cleaning

Proyek ini berfokus pada proses pembersihan data (*data cleaning*) dan analisis data eksploratif (*Exploratory Data Analysis* - EDA) untuk memahami pasar mobil bekas. 

## 📂 Konten Repository
* **Car Prediction.ipynb**: Notebook Jupyer yang mendokumentasikan seluruh alur kerja proyek, mulai dari pengolahan data mentah hingga visualisasi.
* **1B.parquet**: Dataset utama yang digunakan dalam analisis ini.

## 🛠️ Ringkasan Proses yang Dilakukan
Beberapa tahapan penting dalam file `Car Prediction.ipynb` meliputi:
* **Penanganan Missing Values**: Menghapus baris pada target `selling_price` yang kosong.
* **Perbaikan Tipe Data**: Menormalkan kolom `mileage` ke format numerik dan menangani nilai kosong pada kolom `transmission`.
* **Normalisasi Geografis**: Memperbaiki inkonsistensi data wilayah berdasarkan informasi kota.
* **Feature Engineering**: Mengekstraksi informasi torsi dan RPM dari kolom `torque` yang berformat teks menjadi fitur numerik mandiri.
* **Pembersihan Data Salah Input**: Mengoreksi nilai tenaga mesin (`max_power`) yang negatif dan tahun produksi yang tidak masuk akal.

## 📊 Hasil Analisis (EDA)
Proyek ini memberikan gambaran tentang:
* Sebaran harga jual mobil bekas di pasar.
* Merek mobil yang paling dominan muncul dalam dataset.
* Hubungan antara spesifikasi teknis mesin dengan harga jual mobil.

## 🚀 Cara Menjalankan
1. Pastikan Anda memiliki Python dan library seperti `pandas`, `matplotlib`, `seaborn`, dan `pyarrow` terinstal.
2. Buka file `Car Prediction.ipynb` menggunakan Jupyter Notebook atau VS Code.
