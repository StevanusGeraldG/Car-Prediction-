# 🚗 Digging Into Used Car Sales: EDA & Data Cleaning

Proyek ini berfokus pada proses pembersihan data (*data cleaning*) dan analisis data eksploratif (*Exploratory Data Analysis* - EDA) untuk memahami pasar mobil bekas. 

## 📂 Konten Repository
* **Car Prediction.ipynb**: Notebook Jupyer yang mendokumentasikan seluruh alur kerja proyek, mulai dari pengolahan data mentah hingga visualisasi[cite: 1].
* **1B.parquet**: Dataset utama yang digunakan dalam analisis ini[cite: 1].

## 🛠️ Ringkasan Proses yang Dilakukan
Beberapa tahapan penting dalam file `Car Prediction.ipynb` meliputi[cite: 1]:
* **Penanganan Missing Values**: Menghapus baris pada target `selling_price` yang kosong[cite: 1].
* **Perbaikan Tipe Data**: Menormalkan kolom `mileage` ke format numerik dan menangani nilai kosong pada kolom `transmission`[cite: 1].
* **Normalisasi Geografis**: Memperbaiki inkonsistensi data wilayah berdasarkan informasi kota[cite: 1].
* **Feature Engineering**: Mengekstraksi informasi torsi dan RPM dari kolom `torque` yang berformat teks menjadi fitur numerik mandiri[cite: 1].
* **Pembersihan Data Salah Input**: Mengoreksi nilai tenaga mesin (`max_power`) yang negatif dan tahun produksi yang tidak masuk akal[cite: 1].

## 📊 Hasil Analisis (EDA)
Proyek ini memberikan gambaran tentang[cite: 1]:
* Sebaran harga jual mobil bekas di pasar[cite: 1].
* Merek mobil yang paling dominan muncul dalam dataset[cite: 1].
* Hubungan antara spesifikasi teknis mesin dengan harga jual mobil[cite: 1].

## 🚀 Cara Menjalankan
1. Pastikan Anda memiliki Python dan library seperti `pandas`, `matplotlib`, `seaborn`, dan `pyarrow` terinstal[cite: 1].
2. Buka file `Car Prediction.ipynb` menggunakan Jupyter Notebook atau VS Code[cite: 1].
