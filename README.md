# Analisis Dampak Perubahan Iklim terhadap Pertanian menggunakan Machine Learning

Repositori ini berisi proyek akhir untuk kelas Machine Learning Pemula Dicoding yang disponsori oleh DBS Foundation. Proyek ini mengeksplorasi dampak perubahan iklim terhadap sektor pertanian menggunakan teknik machine learning untuk clustering dan klasifikasi.

## Gambaran Proyek

Dalam proyek ini, saya menerapkan teknik machine learning untuk menganalisis efek perubahan iklim pada data pertanian. Proyek ini terdiri dari dua komponen utama:

1. **Analisis Clustering**: Mengidentifikasi pengelompokan alami dalam data iklim pertanian untuk mengungkap pola dan hubungan.
2. **Analisis Klasifikasi**: Memprediksi hasil pertanian spesifik berdasarkan variabel iklim.

## Dataset

Proyek ini menggunakan dataset [Climate Change Impact on Agriculture](https://www.kaggle.com/datasets/waqi786/climate-change-impact-on-agriculture) dari Kaggle, yang berisi berbagai metrik iklim dan pertanian di berbagai wilayah dan periode waktu.

## Struktur Repositori

```
├── climate_change_impact_on_agriculture_2024.csv    # Dataset untuk analisis clustering
├── climate_agriculture_clustered_optimized.csv      # Dataset untuk analisis klasifikasi
├── [Clustering].ipynb                               # Notebook implementasi clustering
├── [Klasifikasi].ipynb                              # Notebook implementasi klasifikasi
├── README.md                                        # Dokumentasi proyek
├── requirements.txt                                 # Paket Python yang diperlukan
```

## Detail Implementasi

### Analisis Clustering

- Menerapkan pembelajaran tanpa pengawasan untuk mengidentifikasi pola alami dalam data iklim-pertanian
- Melakukan pra-pemrosesan data, penskalaan fitur, dan reduksi dimensi
- Menggunakan algoritma **K-Means clustering** untuk mengelompokkan titik data yang serupa
- Melakukan rekayasa fitur untuk meningkatkan Silhouette Score
- Membuat visualisasi detail distribusi cluster
- Memberikan interpretasi komprehensif untuk setiap cluster yang teridentifikasi

### Analisis Klasifikasi

- Menggunakan hasil clustering sebagai dasar untuk model klasifikasi
- Menerapkan classifier **Random Forest** dan **Gradient Boosting**
- Melakukan penyetelan hyperparameter pada model Gradient Boosting untuk mengoptimalkan performa
- Membandingkan metrik performa model termasuk akurasi, presisi, recall, dan F1-score
- Membuat matriks kebingungan untuk memvisualisasikan hasil klasifikasi

## Instalasi dan Penggunaan

### Menggunakan Google Colab (Direkomendasikan)

1. Buka [Google Colab](https://colab.research.google.com/)
2. Upload notebook yang diinginkan ke Google Colab:
   - `[Clustering].ipynb`
   - `[Klasifikasi].ipynb`
3. Upload dataset yang diperlukan:
   - `climate_change_impact_on_agriculture_2024.csv`
   - `climate_agriculture_clustered_optimized.csv`
4. Jalankan notebook secara berurutan

### Menggunakan Local Environment

1. Clone repositori ini:

```bash
git clone https://github.com/zidanmubarak/climate-agriculture-ml-analysis.git
cd climate-agriculture-ml-analysis
```

2. Buat virtual environment (opsional):

```bash
python -m venv venv
source venv/bin/activate  # Untuk Linux/Mac
# atau
venv\Scripts\activate  # Untuk Windows
```

3. Install paket yang diperlukan:

```bash
pip install -r requirements.txt
```

4. Buka dan jalankan file notebook di VSCode:

```bash
code .
```

## Teknologi yang Digunakan

- Python 3.10
- Pandas untuk manipulasi data
- Scikit-learn untuk algoritma machine learning
- Matplotlib dan Seaborn untuk visualisasi data
- Google Colab sebagai platform utama pengembangan
- Visual Studio Code (VSCode) sebagai alternatif lingkungan pengembangan

## Kontributor

- Zidan Mubarak

## Hubungi Saya

Silakan terhubung dengan saya di LinkedIn untuk mendiskusikan proyek ini atau topik data science lainnya:
[Profil LinkedIn Saya](https://www.linkedin.com/in/zidan-mubarak)

Saya selalu terbuka untuk masukan, peluang kolaborasi, atau sekadar berdiskusi tentang machine learning dan data science!
