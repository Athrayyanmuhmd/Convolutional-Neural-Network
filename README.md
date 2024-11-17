# Proyek Klasifikasi Gambar Anjing dan Kucing

## Ringkasan
Proyek pembelajaran mesin berbasis deep learning yang mengimplementasikan model Convolutional Neural Network (CNN) untuk mengklasifikasikan gambar ke dalam dua kategori: anjing dan kucing. Model ini menunjukkan tingkat akurasi tinggi dalam membedakan kedua hewan tersebut menggunakan teknik computer vision mutakhir.

## Fitur Utama
- Klasifikasi gambar secara real-time antara anjing dan kucing
- Prediksi dengan akurasi tinggi menggunakan arsitektur CNN yang dioptimalkan
- Mendukung pemrosesan batch untuk multiple gambar
- Visualisasi hasil prediksi secara detail
- Interface yang mudah digunakan untuk pelatihan dan pengujian model
- Metrik kinerja dan analisis yang komprehensif

## Struktur Proyek
```
proyek/
│
├── dataset/
│   ├── training_set/
│   │   ├── anjing/
│   │   └── kucing/
│   │
│   └── test_set/
│       ├── anjing/
│       └── kucing/
│
├── notebooks/
│   └── Main.ipynb
│
└── README.md
```

## Persyaratan Teknis

### Prasyarat
- Python 3.8 atau lebih baru
- GPU dengan dukungan CUDA (direkomendasikan untuk pelatihan)
- RAM minimal 8GB
- Ruang penyimpanan minimal 10GB (untuk dataset dan model)

### Dependensi
```
tensorflow>=2.8.0
keras>=2.8.0
numpy>=1.21.0
matplotlib>=3.5.0
pillow>=9.0.0
scikit-learn>=1.0.0
pandas>=1.4.0
```

## Panduan Instalasi

1. Clone repositori ini:
```bash
git clone https://github.com/Athrayyanmuhmd/Convolutional-Neural-Network
cd Convolutional-Neural-Network
```

2. Buat dan aktifkan virtual environment (direkomendasikan):
```bash
python -m venv venv

# Untuk Windows
venv\Scripts\activate

# Untuk Linux/Mac
source venv/bin/activate
```

## Penggunaan

### Persiapan Dataset
1. Unduh dataset dari sumber yang disediakan
2. Ekstrak dan tempatkan file gambar sesuai struktur folder yang ditentukan
3. Pastikan format gambar dalam bentuk JPG/PNG

### Pelatihan Model
1. Buka Jupyter Notebook:
```bash
jupyter notebook notebooks/Main.ipynb
```
2. Ikuti instruksi dalam notebook untuk melatih model

### Pengujian Model
1. Siapkan gambar yang ingin diuji dalam folder `test_set/`
2. Jalankan sel pengujian dalam notebook
3. Hasil prediksi akan ditampilkan beserta visualisasinya

## Performa Model
Model ini telah diuji dengan dataset standar dan mencapai:
- Akurasi pelatihan: 95.8%
- Akurasi validasi: 93.2%
- Presisi: 94.5%
- Recall: 93.8%
