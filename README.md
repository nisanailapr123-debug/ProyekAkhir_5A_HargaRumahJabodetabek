# README – Analisis Data dan Preprocessing Properti

## 1. Informasi Proyek

**Nama Proyek:** Analisis Eksplorasi dan Preprocessing Data Properti Rumah di Jabodetabek

**Deskripsi:**

Proyek ini bertujuan untuk melakukan Exploratory Data Analysis (EDA) dan preprocessing terhadap dataset properti rumah di wilayah Jabodetabek yang diperoleh dari Rumah123.

Analisis dilakukan untuk memahami karakteristik data, mengidentifikasi permasalahan kualitas data, serta mempersiapkan dataset agar dapat digunakan pada tahap pemodelan Machine Learning.

## 2. Anggota Kelompok

| No. | Nama Anggota | NIM |
|---|---|---|
| 1 | [Nama Anggota 1] | [NIM] |
| 2 | [Nama Anggota 2] | [NIM] |
| 3 | [Nama Anggota 3] | [NIM] |
| 4 | [Nama Anggota 4] | [NIM] |

## 3. Tools dan Paket yang Digunakan

**Bahasa pemrograman:**
- Python

**Platform:**
- Google Colab
- Jupyter Notebook (opsional)

**Library Python:**
- `pandas` – manipulasi dan pengolahan data.
- `numpy` – operasi numerik.
- `matplotlib` – visualisasi data.
- `seaborn` – visualisasi statistik.
- `scikit-learn` – preprocessing data, imputasi, encoding, dan pembagian dataset.

## 4. Metode yang Digunakan

### A. Exploratory Data Analysis (EDA)

Tahapan EDA meliputi:

1. Memahami struktur dan dimensi dataset.
2. Memeriksa tipe data setiap kolom.
3. Mengidentifikasi missing values.
4. Mengidentifikasi data duplikat.
5. Menganalisis distribusi data numerik dan kategorikal.
6. Menganalisis outlier menggunakan metode Interquartile Range (IQR).
7. Menganalisis hubungan antarvariabel menggunakan korelasi Spearman.
8. Menganalisis karakteristik harga properti berdasarkan wilayah.

### B. Data Preprocessing

Tahapan preprocessing meliputi:

1. Menghapus duplikasi data yang teridentifikasi.
2. Normalisasi URL dan data fasilitas.
3. Memperbaiki inkonsistensi data kategorikal.
4. Menangani missing values menggunakan imputasi median untuk data numerik dan kategori pengganti untuk data kategorikal.
5. Melakukan feature engineering pada data fasilitas.
6. Melakukan Frequency Encoding pada kolom district.
7. Melakukan One-Hot Encoding pada fitur kategorikal.
8. Melakukan Multi-Label Binarization pada fitur fasilitas.
9. Membagi dataset menjadi data training dan testing.

**Catatan:** Proyek ini berfokus pada EDA dan preprocessing. Pelatihan serta evaluasi model Machine Learning berada di luar ruang lingkup pengerjaan ini.

## 5. Dataset

**Sumber dataset:** Rumah123

**Wilayah:** Jabodetabek

**Jumlah data awal:** 3.553 baris

**Jumlah data setelah penghapusan duplikasi identik:** 3.470 baris

Dataset memuat informasi properti, antara lain:

- Harga properti.
- Lokasi dan koordinat.
- Luas tanah dan luas bangunan.
- Jumlah kamar tidur dan kamar mandi.
- Fasilitas properti.
- Sertifikat dan daya listrik.
- Kondisi serta kelengkapan properti.

## 6. Tautan Aplikasi dan Proyek

- **Google Colab / Notebook:** [Masukkan tautan Google Colab]
- **GitHub Repository:** [Masukkan tautan GitHub]
- **Dataset:** [Masukkan tautan dataset jika tersedia]

## 7. Cara Menjalankan Proyek

### Menggunakan Google Colab

1. Buka tautan Google Colab yang tersedia.
2. Login menggunakan akun Google.
3. Pilih menu **File → Save a copy in Drive** untuk membuat salinan notebook.
4. Siapkan dataset sesuai lokasi dan nama file yang digunakan dalam notebook.
5. Pastikan seluruh library yang diperlukan telah tersedia.
6. Jalankan setiap sel kode secara berurutan menggunakan tombol **Run**.
7. Perhatikan hasil output pada setiap tahapan EDA dan preprocessing.
8. Setelah selesai, dataset hasil preprocessing dapat digunakan untuk tahap analisis atau pemodelan selanjutnya.

### Menggunakan Jupyter Notebook

1. Pastikan Python sudah terinstal.
2. Unduh atau clone repository proyek.
3. Instal library yang diperlukan dengan perintah:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

4. Jalankan Jupyter Notebook:

```bash
jupyter notebook
```

5. Buka file notebook proyek.
6. Sesuaikan lokasi dataset pada kode.
7. Jalankan seluruh sel kode secara berurutan.

## 8. Hasil Proyek

Hasil dari proyek ini meliputi:

- Informasi karakteristik dan kualitas dataset.
- Hasil analisis missing values dan duplikasi.
- Hasil analisis distribusi serta outlier.
- Hasil analisis korelasi antarvariabel.
- Dataset yang telah dibersihkan dan dinormalisasi.
- Dataset yang telah melalui proses imputasi dan encoding.
- Dataset training dan testing yang siap digunakan untuk pemodelan lanjutan.

## 9. Penutup

Proyek ini diharapkan dapat memberikan pemahaman mengenai karakteristik data properti di wilayah Jabodetabek serta menghasilkan dataset yang lebih terstruktur dan siap digunakan untuk analisis lanjutan maupun pengembangan model Machine Learning.
