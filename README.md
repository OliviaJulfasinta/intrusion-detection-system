# intrusion-detection-system

Sistem deteksi serangan (IDS) menggunakan deep learning dengan dataset NSL-KDD.

## Dataset
Program ini menggunakan dataset NSL-KDD yang diunduh otomatis dari:
- [KDDTrain+.txt](https://raw.githubusercontent.com/defcom17/NSL_KDD/master/KDDTrain%2B.txt)
- [KDDTest+.txt](https://raw.githubusercontent.com/defcom17/NSL_KDD/master/KDDTest%2B.txt)

## Cara menggunakan

### Menggunakan Google Colab
1. Buka file [intrusion_detection_system.ipynb](intrusion_detection_system.ipynb) di GitHub
2. Klik tombol "Open in Colab" di bagian atas notebook atau buka [link Colab langsung](LINK_COLAB_ANDA)
3. Jalankan semua sel kode secara berurutan

### Menjalankan secara lokal
1. Clone repositori ini:
git clone https://github.com/OliviaJulfasinta/intrusion-detection-system.git
cd intrusion-detection-system

2. Instal dependensi:
pip install -r requirements.txt

3. Jalankan kode Python:
python intrusion_detection_system.py

## Fitur
- Preprocessing data NSL-KDD
- Model deep learning menggunakan TensorFlow/Keras
- Visualisasi kurva ROC
- Evaluasi performa dengan laporan klasifikasi
